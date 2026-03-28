# Fleet P&L Tracker

A simple, offline-capable P&L tracker for your delivery fleet business.

## Features
- Monthly P&L sheets (one per month)
- Revenue, fixed costs, variable costs breakdown
- Per duty analysis (vehicle / bus / hired)
- Break-even calculation
- Summary view across all months
- **All data saved in your browser (localStorage) — no server needed**

## How to run locally (one click)

Just open `index.html` in any browser. That's it.

## How to host on GitHub Pages (free, runs forever)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it: `fleet-pl-tracker`
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload the file
1. Click **uploading an existing file**
2. Drag and drop `index.html`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select `main` branch
3. Click **Save**

### Step 5 — Access your app
Your app will be live at:
```
https://YOUR-USERNAME.github.io/fleet-pl-tracker/
```

GitHub will show the link in the Pages settings. It takes ~1 minute to go live.

---

## Data storage

All data is saved in your **browser's localStorage** on the device you use.

- Data persists across sessions on the same browser/device
- Data does NOT sync across devices automatically
- To backup: open browser console → type `localStorage.getItem('fleet_pl_v2')` → copy the output → save it somewhere safe

## Fixed costs (hardcoded)

| Item | Amount |
|------|--------|
| Driver salary | ₹18,000 |
| Your salary | ₹18,000 |
| EMI | ₹12,000 |
| Office + utilities | ₹6,900 |
| Police | ₹1,500 |
| Misc + bribe | ₹2,000 |
| Tyre | ₹2,000 |
| Insurance | ₹1,700 |
| Maintenance + repair | ₹10,000 |
| **Total** | **₹72,100** |

To change fixed costs, open `index.html` in a text editor and update the `FIXED_COSTS` array at the top of the `<script>` section.
