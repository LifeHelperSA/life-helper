# Life Helper — public launch starter

This is a working, mobile-first Progressive Web App (PWA) starter. It is built with plain HTML, CSS and JavaScript, so it does not need a build system or paid software to edit.

## Included
- Six guided categories: Money, Work, Relationships, Stress & Wellbeing, Goals, and Daily Life
- A step-by-step action plan and progress checklist
- Save, reopen and delete plans in the current browser
- Export saved plans to a JSON file
- PWA manifest, icons and a basic service worker for offline reuse after the first visit
- Privacy note: problem text is processed in the browser; there is no AI backend or account system

## Important limitation
The first version uses prewritten category guidance, not a live AI model. Saved plans stay in the user's browser/device and do not sync between devices. Do not market it as an AI therapist, professional adviser, or emergency service.

## Free publishing option: GitHub Pages
1. Create or sign in to a GitHub account.
2. Create a **public** repository, for example `life-helper`.
3. Upload the files in this folder to the repository root (`index.html`, `manifest.json`, `service-worker.js`, `icon-192.png`, `icon-512.png`).
4. In the repository, open **Settings → Pages**.
5. Under build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
6. Wait for the published URL shown in Settings → Pages. Test that URL on your phone.
7. In Android Chrome, open the URL and use the browser menu → **Install app** or **Add to Home screen** (the wording depends on device/browser).

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Public-launch checklist
- Test on Android Chrome and at least one desktop browser.
- Try each category, saving/reopening/deleting plans, and exporting.
- Review wording for safety, accessibility and local support resources.
- Publish a privacy notice before adding analytics, accounts, AI APIs, or any server-side collection.
- Ask a small group of testers for feedback before promoting widely.
- Keep a backup of the source files.
- GitHub Pages is designed for static project sites, not for running a commercial SaaS service. If the project becomes a commercial service, check the host's current terms and choose suitable hosting.

## Google Play later
A PWA can be installable directly from a supported browser without being listed in Google Play. A Play Store release is a separate project: packaging, developer account, policy/privacy requirements, testing and review may be required. Do not promise a Play Store launch until those steps are completed.
