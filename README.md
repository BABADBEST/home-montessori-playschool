# Home Montessori Play-School — Official Website & Enrollment Portal

A modern, mobile-responsive website and client portal tailored for **Home Montessori Play-School** (Oak Grove Manor, Burlingame, CA · CA License `#414004784`).

## Features
- **Brand Story, Daily Rhythm & Classroom Gallery:** Showcases Miss Leah's 14-area Montessori & play-based curriculum, small 4–6 child community, homemade meals, multilingual English/Tagalog environment, and verified 5.0-star parent reviews.
- **Direct Email Inquiry & Tour Request Form:** Parents can book morning/afternoon tours or ask questions directly without third-party listing middlemen.
- **4-Step Online Child Enrollment Application:** Structured enrollment wizard collecting child details, program tier (`$2,800/mo` Full-Time, `$2,000/mo` Part-Time, After Care, Drop-In), family/emergency contacts, allergies, feeding/nap schedules, and potty-training stage—with printable receipts.
- **New Family Account Registration & Portal:** Prospective and current families can register an account, auto-fill forms, and track submitted inquiries and enrollment applications.
- **Owner Portal & Email Settings:** Click **Owner Portal & Email Settings** in the website footer (default PIN: `4784`) to view all submissions, update statuses, and set your exact business email address & phone number.

## Quick Start

```powershell
cd C:\Users\BABA\.gemini\antigravity\scratch\home-montessori-playschool
npm install
npm start
```

Then open **http://localhost:3000** in your browser.

## Connecting Your Email Inbox
1. **Zero-Config Email Delivery (Default):** Open the site, scroll to the footer, click **Owner Portal & Email Settings** (PIN `4784`), and enter your real email address (e.g., your Gmail or domain email). On the first parent inquiry or enrollment submission, **FormSubmit.co** sends you a one-click activation email—confirm once and all future inquiries & enrollment packets arrive formatted in your inbox automatically.
2. **Direct SMTP (Optional):** Copy `.env.example` to `.env` and add your Gmail App Password or SMTP credentials (`SMTP_USER`, `SMTP_PASS`) for direct server-side email delivery via `nodemailer`.
