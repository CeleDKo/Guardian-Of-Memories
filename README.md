# Guardian of Memories — GitHub Pages site

This folder contains the public homepage and Privacy Policy for the Guardian of Memories app.

## Before publishing

1. Replace every occurrence of `REPLACE_WITH_SUPPORT_EMAIL` in `index.html` and `privacy/index.html` with a real support/privacy email address that you monitor.
2. Verify that the descriptions match the app as actually shipped:
   - Google Sign-In is used for authentication.
   - The app receives basic account information (name, email, Google account identifier).
   - User-created memories are stored in the Firebase database configured for the app.
3. Confirm whether the project uses Firebase Realtime Database or Cloud Firestore, and name the exact product in the policy if known.
4. Confirm the actual deletion process. The current policy describes an email-based request; make sure you can fulfill deletion requests for both the Firebase Authentication account and associated database records.
5. Review Firebase Database / Firestore Security Rules. Each user must only be able to read and write data they are authorized to access.
6. If the app collects additional data (for example analytics, crash reports, device identifiers, voice recordings, location, or uploaded files), update the policy before publishing.
7. Confirm your Google OAuth scopes do not request additional Google data beyond basic sign-in.

## Publish with GitHub Pages

1. Copy the contents of this folder into the root of the `Guardian-Of-Memories` repository.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select your publishing branch (usually `main`) and folder `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site.

Expected URLs:

- Homepage: `https://celedko.github.io/Guardian-Of-Memories/`
- Privacy Policy: `https://celedko.github.io/Guardian-Of-Memories/privacy/`

These URLs are based on the repository and account names supplied in the conversation. Confirm the actual published URLs in GitHub Pages settings.

## Google verification

GitHub Pages on `github.io` may not be accepted as proof that you own the website/domain for Google's verification requirement. If Search Console cannot verify the GitHub Pages URL-prefix property, use a custom domain that you control, connect it to GitHub Pages, and verify that domain in Google Search Console. Do not claim ownership of `github.io`.

After the site is public, add the homepage and Privacy Policy URLs to Google Auth Platform → Branding. Ensure the app name is exactly **Guardian of Memories**.

## Important

This is a practical starter site and policy draft, not legal advice and not proof of compliance by itself. Publish only after checking the text against the real app behavior, Firebase configuration, applicable law, and Google's current OAuth verification requirements.
