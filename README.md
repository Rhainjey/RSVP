# Reiner & Myrvic — Wedding Invitation

A static invitation prepared for GitHub Pages. No Python, installation, build step, or backend is required by guests.

## Publish using GitHub Desktop

1. Extract the supplied ZIP. Keep the entire `github-pages` folder together.
2. In GitHub Desktop, create a new repository named **rm-wedding** in an empty local folder.
3. Copy the **contents** of `github-pages` into that repository folder. `index.html`, `.nojekyll`, `_assets`, and the four page folders must be directly inside it, not inside another `github-pages` folder.
4. Commit the added files, then choose **Publish repository**. For a free GitHub account, publish it as a public repository.
5. Open the repository on GitHub. Go to **Settings → Pages**.
6. Under **Build and deployment**, set Source to **Deploy from a branch**. Choose **main** and **/(root)**, then Save.
7. When GitHub finishes publishing, click **Visit site**. Share that exact link with your family. It normally looks like `https://YOUR-USERNAME.github.io/rm-wedding/`.

Use GitHub Desktop for the upload: the asset folder contains more than 100 files, beyond GitHub's single browser-upload batch limit. Do not upload the ZIP itself as the website.

## Before sharing

- Photos and music are still demo placeholders, except for your supplied couple illustration.
- The original timeline remains a draft, including a 4 PM ceremony placeholder. Your confirmed wedding time is 1 PM Philippine time on November 27, 2026. Review the timeline before sending the link.
- The RSVP deadline is November 20, 2026. The form opens the guest's email app with their name(s); they must press Send themselves. It does not store guest responses on GitHub.
- The published site includes the phone number and email address you supplied. GitHub Pages is publicly accessible.
- Travel/accommodation details remain unconfirmed.

## Structure

`index.html` is the TV welcome page. `invitation/`, `rsvp/`, `details/`, and `our-story/` hold the other pages. `countdown.html` and `rsvp-form.html` provide the local widgets. `_assets` contains the images, music, animations, fonts, and page runtime. `.nojekyll` ensures underscore-prefixed assets are published.

The site automatically detects its repository path and supports directly opening or refreshing page URLs. Keep `.nojekyll` in the repository. Do not upload any `.git` directory from an older package.

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
