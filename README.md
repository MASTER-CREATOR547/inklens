# InkLens

InkLens is a responsive image-to-text tool. Choose an image, select a language, extract text in your browser, edit the result, and copy or download it as a `.txt` file.

## Run / host

This version is a static website and can be served directly from the repository root. OCR uses Tesseract.js and downloads the OCR engine/language data from a CDN, so an internet connection is needed.

## GitHub Pages

A workflow is included at `.github/workflows/deploy.yml`. In the repository, open **Settings → Pages** and select **GitHub Actions** as the Build and deployment source. After saving, each push to `main` triggers deployment.

## Privacy

The selected image is processed locally in the browser and is not uploaded to an InkLens application server. OCR engine and language files are loaded from a CDN.
