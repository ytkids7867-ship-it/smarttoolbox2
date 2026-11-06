# SmartToolbox — GitHub Pages starter website

A responsive static website with seven browser-based tools:
- Age calculator
- Percentage calculator
- Word counter
- BMI calculator
- Password generator
- Text case converter
- Length converter

## 1. Before publishing
1. Choose a final site name after checking domain and social-handle availability. "SmartToolbox" is a suggested working name, not a verified available trademark or domain.
2. Replace `YOUR-USERNAME`, `YOUR-REPOSITORY` in `index.html`, `robots.txt`, and `sitemap.xml`.
3. Replace `YOUR-EMAIL@example.com` in `contact.html`.
4. Review and customize `privacy.html`. It is a starter template, not legal advice.
5. Update the page title, descriptions, social metadata and canonical URL if you use a custom domain.

## 2. Publish with GitHub Pages
1. Create a new public repository on GitHub (for example, `smarttoolbox`).
2. Upload all files and folders in this package to the repository root. Do not upload only the ZIP.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Your address will look like `https://YOUR-USERNAME.github.io/smarttoolbox/`.

GitHub Pages is static hosting. Check GitHub's current terms and confirm that your intended advertising-supported use is permitted before relying on it for monetization. A static host also cannot run server-side code or securely store secrets.

## 3. Adsterra preparation
There is deliberately no ad code in the starter website. First publish and test the site, complete the pages, and check the hosting provider's terms. Then:
1. Register/login to Adsterra as a publisher.
2. Add the live site URL and follow the provider's verification/review process.
3. Generate the ad unit code from your Adsterra dashboard.
4. Read the current ad format instructions and paste the exact code in the placement you choose (for example, in the marked area below the hero or between content sections).
5. Update the privacy policy and add any consent mechanism or disclosures required for your audience and the ad products used.

Never click your own ads, buy fake traffic, use forced redirects, or ask visitors to click ads. Invalid traffic can lead to withheld earnings or account restrictions. Do not promise earnings: revenue depends on genuine traffic, audience geography, ad format, advertiser demand and other factors.

## 4. SEO launch checklist
- Use a descriptive title and unique meta description on every page.
- Replace the canonical URL and sitemap URLs with the actual public URL.
- Add genuinely useful original content and explanations for each tool.
- Verify the site in Google Search Console and submit the sitemap.
- Test mobile usability, page speed, broken links and all tool calculations.
- Do not expect instant indexing or guaranteed rankings.

## 5. Local testing
Open `index.html` in a modern browser. For a local server, run:
`python -m http.server 8000`
Then visit `http://localhost:8000`.

## Notes
- Fonts are loaded from Google Fonts; the site falls back to system fonts if unavailable.
- Tool calculations run in the browser. The password generator uses the Web Crypto API.
- BMI output is general adult screening information and is not medical advice.
