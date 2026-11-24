# Restaurant Billing Application

A lightweight browser-based restaurant POS/billing app. The menu, restaurant details, tax rate and saved orders are stored in `localdb.json`.

## Requirements
- Node.js 18+ recommended

## Run
1. Open a terminal in this project folder.
2. Run `npm install`.
3. Run `npm start`.
4. Open http://localhost:3000 in your browser.

## Customize menu and restaurant
Edit `localdb.json`: restaurant name, address, phone, taxRate and menu entries (id, name, category, price). Restart the server after edits.

## Features
- Search and category-filter the menu
- Add items and adjust quantities
- Automatic subtotal, tax and total
- Customer details
- Save order records in JSON
- Printable receipt

**Note:** This is a local demo intended for one local server/user at a time. JSON file writes are not designed for concurrent users or production-grade accounting.
