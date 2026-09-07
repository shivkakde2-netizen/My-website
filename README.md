# 10 Minute Mail — Free Hosting Ready

This is a static GitHub Pages-ready project. Upload `index.html` to a repository and enable GitHub Pages.

## GitHub Pages
1. Create a repository on GitHub (for example `ten-minute-mail`).
2. Upload `index.html` to the repository root.
3. Open Settings → Pages.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Open the published Pages URL after GitHub finishes deploying.

GitHub Pages is free for public repositories. The site uses Mail.tm directly from the browser; it does not proxy or mirror the Mail.tm API.

## Important
- This is intended for testing/demo use.
- Mail.tm attribution is included in the footer.
- The 10-minute expiry is enforced by the page timer; the mailbox is not a guarantee of deletion if the browser is closed.
- If Mail.tm rejects browser-origin requests, a different email API/service that explicitly permits browser use would be needed. Do not proxy/mirror Mail.tm's API, because its current terms prohibit proxy services.
