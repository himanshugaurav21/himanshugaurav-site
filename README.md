# Himanshu Gaurav — Personal Website

Production URL: https://himanshugaurav.com

A static, responsive, accessible personal website featuring professional biography, writing themes, and links to Medium, Substack, LinkedIn, and GitHub.

## Local preview

Run `python3 -m http.server 8080` from the repository root and visit http://localhost:8080.

## Cloudflare Pages deployment

1. Open Cloudflare Dashboard → Workers & Pages → Create application → Pages → Connect to Git.
2. Authorize GitHub and choose `himanshugaurav21/himanshugaurav-site`.
3. Select branch `main`; use no framework preset and no build command; output directory `.` (repository root).
4. Deploy and test the generated `*.pages.dev` URL.
5. Under Pages → Custom domains, add `himanshugaurav.com`; follow Cloudflare's DNS instructions and verify HTTPS.

This first release links to Medium and Substack. It does not import articles automatically. Review biography and links before announcing publicly.
