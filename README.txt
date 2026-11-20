CLIPNOVA AI — FREE STARTER

WHAT THIS VERSION DOES
- Installable mobile website (PWA)
- Upload a video stored on your phone
- Preview it and choose start/end times
- Record/export the selected segment as WebM where the browser supports captureStream + MediaRecorder
- Preview YouTube links using the official YouTube embed player

IMPORTANT LIMITATIONS
- A YouTube URL is preview-only. This app does not download YouTube videos or bypass restrictions.
- To clip a video, upload a video file that you own or have permission to use.
- This first version does not yet have automatic AI highlight detection, automatic subtitles, MP4 encoding, or guaranteed 1080p output.
- Browser support for video capture varies. Latest Android Chrome is recommended. Keep the page open while exporting.
- This app processes uploaded video locally in the browser; no upload server is used.

HOW TO PUT IT ON YOUR ANDROID PHONE
1. Extract this ZIP.
2. Host the folder on an HTTPS static host. GitHub Pages is one free option:
   - Sign in to GitHub and create a new public repository named clipnova-ai.
   - Upload index.html, manifest.webmanifest, sw.js, and icon.svg to the repository root.
   - Open repository Settings > Pages.
   - Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
   - Wait for the Pages URL, usually https://YOUR-USERNAME.github.io/clipnova-ai/
3. Open that HTTPS URL in Chrome on Android.
4. Tap Chrome menu (⋮) > Add to Home screen or Install app.
5. Open ClipNova AI from your home screen.

QUICK TEST
- Choose Upload video and select a short MP4.
- Set start and end seconds.
- Tap Create clip and keep the page open.
- Tap Download your clip when it finishes.

If export fails, try a shorter MP4 clip and the latest Chrome. Some Android browser/device combinations do not support captureStream recording.
