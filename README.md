# WAYBRIDGE Prototype

A static, responsive, browser-based prototype for the WAYBRIDGE ground transportation platform.

## Included workspaces
- Corporate: dashboard, booking search/review, manager approval inbox, budgets, employees and reports.
- Agency: dashboard, booking search/review, bookings, customers, agents, credit/wallet and reports.
- Operations: control tower, booking monitor, exceptions, suppliers, notifications and reports.

## Run locally
Open `index.html` in a modern browser. No build step or package installation is required.

## Publish with GitHub Pages
1. Create a new public GitHub repository, for example `waybridge-prototype`.
2. Upload `index.html` and this `README.md` to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. The public URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/waybridge-prototype/`

## Important
This is a front-end demo with illustrative data and browser-session state only. It does not connect to a database, AWS, supplier APIs, payment gateways, Microsoft Graph, Twilio or Meta WhatsApp. Do not use it for real bookings or financial decisions. Production requires backend APIs, authentication, tenant isolation, audit logging, secure secrets, payment integration and supplier certification.
