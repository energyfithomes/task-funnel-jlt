Task Funnel PWA GPT

Built pieces:
- fast static home-screen capture interface
- NOW/LATER
- Type / Photo / Voice Recorder
- screenshot/file attachment
- link capture
- Google Apps Script backend that writes to the existing Task Funnel GPT sheet and Drive capture folder
- service worker for cached fast startup

Remaining deployment step:
1. Put Task_Funnel_Backend_GPT.gs into the Apps Script project attached to Task Funnel GPT.
2. Deploy it as a Web App and copy the URL.
3. Replace PASTE_APPS_SCRIPT_WEB_APP_URL_HERE in index.html with that URL.
4. Host index.html + manifest.webmanifest + sw.js on static hosting.
5. Add hosted page to Android home screen.
