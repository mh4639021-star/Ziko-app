# ZIKO Android App

This repository now includes a basic Android app shell that opens a web app in a full-screen `WebView`.

What it does:
- Loads your web app in Android
- Supports JavaScript and local storage
- Keeps a browser-like experience for mobile
- Works as a foundation for APK production

Quick setup:
1. Open the project in Android Studio.
2. Install Android SDK 34 and Gradle 8.5+ if prompted.
3. Replace this URL in `app/src/main/java/com/ziko/app/MainActivity.kt`:
   - `https://example.com`
   - with your real deployed ZIKO web app URL, for example `https://your-domain.com`.
4. Build -> Generate Signed Bundle / APK.

If you want a fully native Android version instead of a web wrapper, send me the complete app source files (not just snippets) and I can convert it into a real Android app with native screens, auth, uploads, and Supabase integration.
