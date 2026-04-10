# n8n Automation Templates

A collection of practical n8n workflows I built to automate the boring parts of job hunting — and anything else worth automating.

Each template is plug-and-play: import the JSON, swap in your credentials, and you're done.

---

## Templates

### [LinkedIn Job Alert → Telegram](./linkedin-job-alert-telegram/)
Scrapes LinkedIn for jobs posted in the last 24 hours, scores each one against your resume using OpenAI, and sends only the relevant ones to your Telegram. No more doomscrolling job boards.

### [Recruiter Email Outreach](./email-outreach/)
Reads leads from a Google Sheet and sends personalized cold emails via Gmail — one at a time, on a randomized timer so it looks human. Marks each contact as done when sent.

---

Built with [n8n](https://n8n.io) — open source workflow automation.
