# Samuel Grosz CV website

Ready for GitHub Pages. After publishing, the CV page will be at:

https://samuelgrosz.co.uk/cv/

Entering /cv will automatically redirect to /cv/.

## Publish

1. Create a GitHub repository (for example, samuelgrosz.co.uk).
2. Upload everything inside this folder to the repository root.
3. In Settings > Pages, choose Deploy from a branch, main, /(root).
4. In Settings > Pages > Custom domain, enter samuelgrosz.co.uk and save.
5. At GoDaddy, delete only the two existing A records for @ (3.33.130.190 and 15.197.148.33). Add four A records for @:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
6. Change the www CNAME from samuelgrosz.co.uk to YOUR-GITHUB-USERNAME.github.io.
7. Do not alter MX or TXT records. They operate the Microsoft 365 email setup.
8. Once GitHub confirms the domain, enable Enforce HTTPS.

DNS commonly updates within an hour but can take up to 48 hours globally.

## Updating the CV

Replace cv/samuel_grosz_cv.pdf with a new PDF using exactly the same filename, then commit the change.
