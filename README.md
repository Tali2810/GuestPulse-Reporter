# GuestPulse Report Generator

A static, browser-only report generator for GuestPulse / Dify JSON output.

## Run locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` (and this README if desired) to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.

Paste the JSON response from Dify and select **Generate report**. If Dify output contains two JSON objects pasted consecutively, the app reads the first complete object. Use **Print / Save PDF** to save the report as a PDF.

All processing happens locally in the browser; the pasted feedback is not sent to a server.
