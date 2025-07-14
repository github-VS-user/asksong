# 🎶 AskSong

AskSong is a super simple web app that lets anyone suggest a song to be added to a shared playlist or music pool. The idea is to collect good vibes, crowd-curated.

## 🚀 What It Does

- Displays a clean, modern form with two fields:
  - **Song Title + Artist**
  - **Why you recommend it**
- Submits suggestions via [FormSubmit](https://formsubmit.co) — no backend needed.
- Automatically redirects users to a fun **thank-you page** with animated confetti 🎉
- Fully responsive and offline-previewable — works right in your browser.

## 🌐 Tech Used

- HTML + CSS only (no JavaScript frameworks)
- Confetti animation via pure JavaScript canvas
- Hosted via GitHub Pages / Netlify
- Form powered by [FormSubmit](https://formsubmit.co) to send results to your email

## 🧠 How to Use

1. Edit the `index.html` file:
   - Replace `YOUR_EMAIL_HERE` with your real email address in the form `action`.
   - Optionally customize your `_next` redirect link to point to your thank-you page.
2. Upload the site to GitHub or Netlify.
3. First time a form is submitted, FormSubmit will ask you to verify the email.
4. Boom — you're ready to collect songs! 🎧

## 📂 Files

- `index.html` – Main song suggestion form
- `thankyou.html` – Confirmation screen with celebration
- No external libraries. Everything works offline.

## ❤️ Credits

Created with love by [Dario](https://github.com/github-VS-user)  
Feel free to fork, remix, or turn it into something wilder.
