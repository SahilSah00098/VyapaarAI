**Live Demo:** https://vyapaarai-bysahilsahktt40.netlify.app/

# VyapaarAI
"Your next sale starts with your next smart action."
Track: Entrepreneurship & Local Business. An offline growth assistant for Indian local shops: it turns sales, customer and udhaar (pay-later) data into prioritised, explainable next actions.

## Problem and users
Small shopkeepers record sales but rarely notice which regular customers have gone quiet or who still owes money. VyapaarAI shows these as a short, prioritised action list with the reason for each.

## Run
Unzip and double-click `index.html`. No install, no internet, no backend. (Or open the deployed link.)

## Features
- Overview: period filter, sales, expenses, estimated profit, udhaar pending, active vs lapsed customers, charts
- Customer CRM: add, edit, view, search, sort, delete with confirmation, duplicate-phone check, udhaar per customer
- Sales and expenses (INR, validated); udhaar tracking with Mark paid
- Follow-up tasks: create, edit, complete, reopen, filter, overdue flags
- Growth Advisor (rule-based, rules explained on screen): lapsed customers, high-value customers going quiet, overdue tasks, unpaid udhaar, category sales drops
- Message writer: English and Hinglish templates (win-back, thanks, offer, payment reminder); Copy, or open WhatsApp pre-filled. Nothing is sent automatically
- Guided 6-step demo; demo data with Reset; Start empty; backup/restore (JSON); sales CSV export; light/dark mode; mobile-first

## Data and safety
All data stays in the browser (localStorage). Demo data is fictional. No API keys, accounts or personal data are used.

## AI tools used
The code was written with Claude (Anthropic) using prompts to plan, build and test the app. The app itself calls no AI model: recommendations and messages are deterministic rules and templates, clearly labelled in the UI.

## Limitations
Single device and browser; no login or cloud sync; no LLM integration yet (next step); CSV/JSON download may not work inside embedded viewers. Tested on limited browsers only.

## Testing report
Executed and passed: JavaScript syntax check and `node smoke-test.js` (every screen renders with demo and empty data, udhaar KPI and recommendation, payment drafts in English and Hinglish, WhatsApp link, mark-paid effect, guided tour, rules explainer, backup buttons).
Not verified by automated tests: real-browser interaction, clipboard, file download/restore, phone devices. Verify manually before submitting.

## Originality declaration
I built this project during the event with AI assistance, I used only fictional sample data, and I can explain the code.
