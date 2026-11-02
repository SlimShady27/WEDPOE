# ST10442302POE
 ## Security Implementation
To protect the website from common web vulnerabilities (such as XSS and clickjacking), the following security measures were implemented:
- **Content Security Policy (CSP):** Configured via meta tags to restrict resource loading to trusted sources.
- **X-Content-Type-Options:** Set to `nosniff` to prevent MIME-type confusion attacks.
- **X-Frame-Options:** Set to `DENY` to protect against clickjacking attempts.
- **Input Validation:** Client-side JavaScript validation is enforced on user input fields (such as phone numbers and enquiry quantities) to ensure data integrity and prevent injection issues.
- **HTTPS Enforcement:** Deployed over secure HTTPS channels via the hosting provider.

## Part 3 Changelog & Features Added
- **Visuals & Layout:** Upgraded the homepage hero section with a side-by-side Flexbox layout (left-aligned text, right-aligned logo) and standardized font sizes and solid black text contrast (`#000000`) across all pages.
- **Interactive JavaScript Features:** Implemented dynamic cost calculation and a pop-up confirmation alert upon submitting the enquiry form, alongside form validation on contact inputs.
- **Search Engine Optimization (SEO):** 
  - Added on-page SEO metadata (unique title tags and meta descriptions) across all HTML pages.
  - Included technical SEO files (`robots.txt` and `sitemap.xml`) in the root directory.
- **Version Control & Deployment:** Managed project versions using Git/GitHub Desktop and prepared the repository for live deployment.

## References
- HTML & CSS Documentation: W3Schools, MDN Web Docs.
- JavaScript Form Handling & Alerts: MDN Web Docs.