# Account Record Generator

A static Firebase web app for creating, saving, editing, and printing personal account information.

## Setup
1. In Firebase Console, open project `account-record-generator`.
2. In Authentication > Sign-in method, enable **Email/Password**.
3. In Firestore Database, create a database.
4. Publish the contents of `firestore.rules` in Firestore Rules.
5. In GitHub, open Settings > Pages, choose **Deploy from a branch**, select the default branch and `/(root)`, then Save.

The site uses Firebase Web SDK configuration in `index.html`. The web config is intended for client-side use; database access is restricted by the Firestore rules to each signed-in user's own records.

## Print
The print layout is landscape, compact, and positioned at the right side of the page. Only entered fields are printed.

## Privacy
Account information can be sensitive. Use a strong password, do not share your login, and do not enter PINs, passwords, OTPs, CVV, or other authentication secrets.