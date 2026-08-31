MARUTI CLINIC PWA V2 — CLOUD SYNC

This version uses Firebase Authentication + Cloud Firestore for private cloud sync.

1. Host this folder on HTTPS (Firebase Hosting, Netlify, Vercel, GitHub Pages, etc.).
2. In Firebase Console for project maruti-clinic-5d157:
   - Authentication > Sign-in method > enable Email/Password.
   - Firestore Database > Create database.
   - Firestore Rules: paste the contents of firestore.rules and publish.
3. Open the hosted app on Android Chrome.
4. Open Backup > Cloud sync.
5. Create an account or sign in.
6. The app saves locally first and automatically syncs to that user's private Firestore document when online.

Important: The Firebase web config is not a password. Security comes from Firebase Authentication and Firestore Rules.
Patient information is sensitive: keep the Firebase account credentials private and use a strong password.
