Ledger — Personal Finance Dashboard
A single-file, self-contained personal finance dashboard that runs entirely in your browser. No backend, no account creation on a server, no data leaving your device — everything is stored locally.
Features
Track income and expenses with description, category, amount, and date & time
₹ Indian Rupee formatting with proper Indian digit grouping
Category spending chart — a doughnut chart breaking down where your money goes
Budget tracking per category with visual progress bars
CSV import — bring in transaction history exported from UPI apps (GPay, PhonePe, Paytm) or your bank
Local login screen — a simple email + phone number gate to keep the file from opening straight to your data (not encryption — a privacy screen, not a security system)
Light/dark theme toggle, responsive layout for mobile and desktop
How it works
The entire app is one HTML file (finance-dashboard.html) with inline CSS and JavaScript. Data is saved to your browser's localStorage, scoped to wherever you open the file from — so it's private to that browser/device.
Getting started
Download finance-dashboard.html
Open it in any modern browser (Chrome recommended)
Set up your login (email + phone) on first launch
Start adding transactions, or import a CSV export from your bank/UPI app
Hosting it online (optional)
To get a shareable link instead of just a local file, enable GitHub Pages for this repository:
Go to Settings → Pages
Under Source, select the main branch and root folder
Save — GitHub will publish the file at https://<atharvpatil2647-spec>.github.io/<repo-name>/finance-dashboard.html
Tech
Plain HTML, CSS, and JavaScript. Uses Chart.js for the spending chart and PapaParse for CSV parsing, both loaded from a CDN.
Privacy note
All data stays in your browser's local storage. Nothing is sent to any server. The login screen is a local convenience, not verified authentication — treat this as a personal tool, not a place to store anything highly sensitive.
