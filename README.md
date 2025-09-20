
# AIYRA Jewellery Collections - Complete Website (GitHub-ready)

This repository contains a complete, ready-to-deploy static website for **AIYRA Jewellery Collections**.
The site is dark-themed, mobile-friendly, and includes an Admin panel that stores product data in the browser's `localStorage`.

## What's included
- `index.html` — Main website (dark theme) with Admin features.
- `images/` — Pre-made JPG product images used as placeholders.
- Admin password (default): `1234`
- WhatsApp number used for orders: `+00923462800563` (change inside `index.html` if needed)

## How to make the site live (GitHub Pages)
1. Create a GitHub account (if you don't have one): https://github.com
2. Create a new repository (e.g., `aiyra-jewellery`), set it to **Public**.
3. Upload all files from this repository (drag & drop `index.html` and the `images/` folder).
4. Go to the repository **Settings → Pages**.
5. Under **Source**, select branch `main` (or `master`) and folder `/ (root)` and click **Save**.
6. Wait a minute — GitHub will provide a live URL like:
   `https://YOUR-USERNAME.github.io/aiyra-jewellery/`

## Alternative: Netlify (simpler drag-and-drop)
1. Create an account at https://app.netlify.com/
2. Choose "Sites → Add new site → Deploy manually" and drag the site folder (all files) into the upload area.
3. Netlify will deploy and give you a live link immediately.

## How admin works
- Click **Admin Login** and enter the admin password (default `1234`).
- After login, you can **Add**, **Edit**, and **Delete** products. Changes are saved in your browser (localStorage).
- If you upload an image via Admin, the image is saved as a Data URL in localStorage and will show for visitors on your computer/browser. To make images permanent across devices, upload the images to the `images/` folder in the repository and commit them to GitHub (or host them publicly) and update the product `image` field accordingly.

## Change WhatsApp number or admin password
- Open `index.html` in a text editor.
- Search for `WA_NUMBER` and change the phone number.
- Search for `ADMIN_PASSWORD` to change the password.

## Need help?
If you'd like, I can:
- Provide step-by-step screenshots for deploying to GitHub Pages or Netlify.
- Prepare a deployment-ready repository on your behalf **if you give me a GitHub repository link and add me as a collaborator** (I cannot access your account directly).

---
Good luck! Share the live link once deployed and I'll help test it and make quick improvements.
