# testing

Clean Android project for opening the official University of Petra MENA-ME portal securely.

Portal:
https://hr.uop.edu.jo/production/application/HRMS/mename/

## Build with GitHub Actions
Create a NEW empty GitHub repository, upload the CONTENTS of this ZIP to the repository root, and commit to `main`.

Then open:

Actions → Build Android APK

After a successful run, download:

Artifacts → testing

Inside it you will find:

testing.apk

## Security
- HTTPS only
- No SSL bypass
- No custom TrustManager
- No credential storage
- Portal host is restricted to hr.uop.edu.jo
- Android 7+ support
