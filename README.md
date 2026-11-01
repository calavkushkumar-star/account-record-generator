# Account Record Generator — Windows app

This repository includes a Windows desktop wrapper for the hosted Account Record Generator website.

## Build the Windows installer
1. Open the repository's Actions tab.
2. Select Build Windows Application.
3. Click Run workflow on the main branch.
4. When the run completes, download the Account-Record-Generator-Windows artifact.
5. Extract the ZIP and run the EXE installer.

The app opens the hosted website, so an internet connection is required. Firebase Authentication continues to use the GitHub Pages domain.

## Local development
Run `npm install`, then `npm start`.

## Notes
- This is a desktop wrapper, not an offline version.
- Do not put Firebase Admin SDK service-account keys in this repository.
