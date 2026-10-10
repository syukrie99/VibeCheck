# ⚡ VibeCheck – Smart Inventory & Reorder Agent

An AI-powered inventory management agent for small local businesses (cafes, restaurants, and shops). VibeCheck watches stock levels, predicts run-outs from daily usage speed, negotiates with suppliers, drafts purchase orders, and tracks deliveries, all from one board.

Built for a hackathon (Idea 24: Smart Local Inventory & Reorder Management Agent). Powered by **Tencent WorkBuddy AI**.

## Features

- **Stock usage scan:** detects items below their safety buffer and estimates days of stock left
- **AI vendor multi-bidding:** WorkBuddy compares distributors and negotiates price and lead time
- **PO draft generation:** purchase orders with SST, ready to approve, exportable as **PDF** or TXT
- **EasyParcel tracking:** courier dispatch and live delivery progress (picked up → delivered)
- **POS CSV import and export:** update usage speeds from sales logs, with preset scenarios (Friday rush, rainy day, catering event)
- **Auto-Restock mode:** autonomous negotiation for all low-stock items
- **Crisis simulator:** trigger a stockout and pick an AI recovery plan
- **Gamification:** XP, levels, daily quests and badges to keep managers engaged

## Workflow

Usage Watch → AI Vendor Bidding → PO Draft Approval → EasyParcel Transit → Restocked & Closed

## Tech Stack

- HTML, vanilla JavaScript, Tailwind CSS (CDN)
- html2pdf.js (client-side PDF export)
- Font Awesome icons
- Tencent WorkBuddy AI (agent runtime, simulated for demo)
- EasyParcel API (shipping, simulated for demo)

## Run Locally

No build step needed. Clone the repo and open `index.html` in your browser:

    git clone https://github.com/YOUR-USERNAME/vibecheck.git
    cd vibecheck
    open index.html

## Demo Notice

WorkBuddy and EasyParcel integrations are **simulated** with sample data for demonstration purposes. No real API calls are made and no real orders are placed. Do not commit real API keys to this repository.

## Author

Built by VibeCoder.
