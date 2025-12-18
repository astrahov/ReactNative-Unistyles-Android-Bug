Steps to reproduce:

- Project:
  - `npm ci`
  - `npm run clear:android:build`
  - `npm run clear:android:gradle` (BUILD SUCCESSFUL)
  - `npm run fix:nitro`
- Android Studio:
  - Open Android Studio and run Gradle Sync (with fix - BUILD SUCCESSFUL)
- Project:
  - `npm run run:server:start--with-reset-cache`
  - `npm run run:android` (ERROR)
