# PES Arena Gaza — Android

This project packages the current PES Arena Gaza HTML site inside an Android WebView.
The HTML file is bundled locally in `app/src/main/assets/index.html`, so the app does
not depend on the public website to render the UI. Internet access is still required
for Supabase/Gemini-backed features.

## Build without a computer

Upload this project to GitHub, open the Actions tab, choose **Build PES Arena Gaza APK**,
and run it with **Run workflow**. The workflow builds a debug APK and publishes it as
an artifact named `PES-Arena-Gaza-debug`.

## Important

This first build is unsigned/debug. Android can install it for testing, but it is not
a Play Store release package. A release signing key should be added before publishing.
