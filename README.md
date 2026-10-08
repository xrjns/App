# My Dashboard

All-in-one personal dashboard (notes, tasks, groceries, spending, journal). Web app in `www/index.html`, packaged as an Android APK with Capacitor.

## Get the APK (no Android Studio needed)
1. Push this folder to a GitHub repo (keep the hidden `.github` folder).
2. Open the repo's **Actions** tab, pick **Build APK**, press **Run workflow** (it also runs on every push to `main`).
3. After ~5-10 minutes open the finished run, download **my-dashboard-apk** under *Artifacts*, unzip it, and install `app-debug.apk` on the phone (allow "install unknown apps" when asked).

## Not done yet
- Gmail unread/notification checks need a Google sign-in (your own Google Cloud OAuth client). Until then the Gmail tile shows "Sign-in needed".
- Cloud sync for a shared grocery list.
