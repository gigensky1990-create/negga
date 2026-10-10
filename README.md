# Budget Buddy (Android, fully offline)

A budget calculator with a calendar. Tap any day to log:

- **I spent**: money you spent (Food, Snacks, Drinks, Transport, Other). Counts against your monthly budget.
- **I saved**: money you did NOT spend, like skipping snacks or milk tea. Adds to your Saved totals.

You get a monthly budget, how much is left, a suggested per-day amount, a monthly Saved total and an all-time Saved total.
Everything is stored on your phone. The app has no internet permission, so it never sends anything anywhere.

## Get the APK (pick ONE way)

### Way 1: GitHub builds it for you (no computer software needed)
1. Make a free account at github.com and create a **new repository**.
2. Upload everything in this folder (keep the folders, including the hidden `.github` folder) to the repository.
   Easiest: unzip this project on a computer and drag all the files into the "Add file > Upload files" page.
3. Open the **Actions** tab. The "Build APK" job runs by itself (about 3-5 minutes).
   If it doesn't start, click "Build APK" then **Run workflow**.
4. When it finishes, open the run and download **BudgetBuddy-apk** at the bottom. Unzip it to get `app-debug.apk`.
5. Send the APK to your phone, tap it, and allow "Install unknown apps" when asked.

### Way 2: Android Studio (on a Windows or Mac computer)
1. Install Android Studio (free) from developer.android.com/studio.
2. **Open** this folder as a project and let it finish syncing.
3. Menu: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Click "locate" in the popup to find `app-debug.apk`, then copy it to your phone and install it.

## Notes
- Your data lives inside the app. Uninstalling the app erases it.
- Change the currency symbol by editing `var CUR = '₱';` in `app/src/main/assets/index.html`.
