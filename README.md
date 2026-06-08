# 🌿 PEI Parks — Supply Management System

A free, browser-based supply distribution tracker for PEI Provincial Parks and Visitor Information Centres. No server required — runs entirely in the browser and stores data locally.

---

## 🚀 How to Host on GitHub Pages (Free)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it: `pei-parks-supply` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the file
1. Click **Add file** → **Upload files**
2. Drag and drop `index.html` into the box
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings**
2. Scroll to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**

### Step 5 — Get your link
After 1–2 minutes, your app is live at:
```
https://YOUR-USERNAME.github.io/pei-parks-supply/
```
Share this link with all parks and drivers!

---

## 📱 Features

| Feature | Description |
|---|---|
| **Dashboard** | Weekly stats, recent deliveries, pending orders, location status |
| **Log Delivery** | Record supplies delivered, odometer start/end (auto-calculates KM), attach receipt photos/PDFs |
| **Supply Orders** | Parks staff place orders directly — shows up instantly on driver's dashboard |
| **Inventory** | Track stock levels per item, adjust quantities, filter by low/out of stock |
| **Fuel Log** | Log every fuel stop with litres, cost, odometer, receipt number, attach receipt files |
| **Friday Report** | Auto-generated weekly report — all deliveries, fuel, orders, receipts — print or save as PDF |

---

## 📎 Attaching Receipts

- When logging a delivery or fuel stop, click the upload area to attach PDF or photo receipts
- File names are recorded in the system and listed in the Friday Report
- For the Friday office submission: print the Friday Report as PDF (Ctrl+P → Save as PDF), then attach the actual receipt files in an email or folder

---

## 💾 Data Storage

Data is stored in your **browser's local storage** — it persists between sessions on the same device and browser.

> **Important**: Data is per-device. For a shared system across multiple drivers, consider upgrading to a Google Sheets backend (ask for instructions).

---

## 🗂️ File Structure

```
index.html    ← The entire app (one file, no dependencies needed)
README.md     ← This file
```

---

## 📞 Questions?
Contact your system administrator or IT support.
