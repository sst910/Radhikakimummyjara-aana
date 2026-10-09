# Future Mrs. ❤️ — Interactive Love Quiz

A single-file Hindi/Hinglish romantic quiz with shuffled multiple-choice options, suspense tones, retry-until-correct gameplay, and a personal note form.

## Run locally
Open `index.html` in a browser. Tap **Chalo shuru karein** to enable audio; browsers require a user gesture before playing sound.

## Publish on GitHub Pages
1. Sign in to GitHub and create a new **public** repository (for example, `future-mrs-quiz`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for the Pages URL to appear in the Pages section (usually `https://YOUR-USERNAME.github.io/future-mrs-quiz/`).

## Notes
- No external libraries, images, or audio files are required. The suspense and success sounds are generated in-browser.
- The note is not uploaded or sent anywhere. It stays in the page until the user copies it.
- Correct answers are designed as the affectionate/relationship-minded responses in this playful quiz; change the `ok: true` options in `index.html` if you want different intended answers.
