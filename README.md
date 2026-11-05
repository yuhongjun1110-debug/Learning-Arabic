# Bahraini Arabic Coach — iPhone web app

## What is included
- Mobile-first 180-day course roadmap
- Daily 45-minute study routine
- Day 1 and Day 2 lesson content
- Vocabulary, dialogues, quizzes, and lesson completion tracking
- Local progress storage and JSON export
- Installable PWA manifest and offline service worker

## Important content note
This is a starter course app. Days 3–180 include the structured roadmap and a reusable practice lesson template; they are not yet fully authored, bespoke lessons. Continue requesting each day's lesson in ChatGPT to get a complete, tailored lesson and use the app to track your progress.

## Publish it so you can add it to your iPhone
The app must be served from an HTTPS website for iPhone Home Screen installation and offline caching. This ZIP does not publish or host the app.

### Simple option: GitHub Pages
1. Sign in to GitHub and create a new public repository, e.g. `bahraini-arabic-coach`.
2. Upload all files in this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the HTTPS address.

### Add to iPhone Home Screen
1. Open the published HTTPS address in **Safari** on your iPhone.
2. Tap **Share**.
3. Choose **Add to Home Screen**.
4. Edit the name if desired, then tap **Add**.

## Data and limitations
- Lesson completion is saved in the browser on that device.
- There is no account, cloud sync, push notification, or automatic lesson delivery inside this app.
- The preferred study time setting is a local preference only; it does not schedule notifications.
- For speaking feedback, use ChatGPT Voice Mode alongside the app.
