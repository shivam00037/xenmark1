# XENMARK — GitHub Upload (No Images Folder Required)

This version keeps every image beside `index.html`, so you can upload all files through GitHub's **Add file → Upload files** page without needing to upload a folder.

## Files
- `index.html` — website homepage, styling, and scripts
- `*.webp` — all local website images
- `README.md` — setup notes
- `.gitignore` — common local/editor files to ignore

## Upload using GitHub in your browser
1. Extract this ZIP on your computer.
2. Open your GitHub repository and click **Add file → Upload files**.
3. In File Explorer, open the extracted `XENMARK_GitHub_No_Folder` folder.
4. Select `index.html`, all `.webp` images, `README.md`, and `.gitignore` together and drag them into GitHub's upload area (or select the files with the file chooser).
5. Commit the changes to your branch. Do not upload the ZIP file itself as website source.
6. Vercel should redeploy after the commit; otherwise trigger a redeploy from the Vercel Deployments tab.

## Important
Keep all `.webp` images in the same directory as `index.html`. This version references images at the root level; do not put them in an `images/` folder.

## Business links
- Instagram: https://www.instagram.com/xenmark_/
- WhatsApp: +91 6387731661

This is a static site. Enquiry forms prepare a WhatsApp message for the visitor to review and send; they do not store submissions in a database.
