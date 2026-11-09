# ClipGenius AI — Free MVP starter

This is a static, browser-based video trimmer/exporter. It is not an Opus Clip clone yet.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser, or serve this folder with a local static server.
3. Internet access is required on first load because FFmpeg.wasm is loaded from public CDNs.
4. Choose a small MP4, set start/end seconds, choose aspect ratio, and click **Make clip**.

## Publish free with GitHub Pages
1. Create a GitHub account and a new public repository named `clipgenius-ai`.
2. Upload `index.html` and this README to the repository root.
3. In the repository, open Settings → Pages.
4. Under Build and deployment, select Deploy from a branch, choose `main` and `/ (root)`, then Save.
5. GitHub Pages will provide a free address similar to `https://YOUR-USERNAME.github.io/clipgenius-ai/`.

No custom domain is required. GitHub Pages hosts the frontend only.

## Current limits
- Manual start/end clipping only; no AI highlight detection.
- No accounts, database, server-side uploads, captions, face tracking, or payments.
- FFmpeg.wasm processing happens on the visitor's device. Large files may fail, especially on phones.
- CDN access and browser support are required.
- This project is an original starter and is not affiliated with Opus Clip.

## Next development milestone
Add transcription and speech-based highlight suggestions, then caption styling and persistent user projects. Those features require a separate processing architecture; do not advertise them as available until implemented and tested.
