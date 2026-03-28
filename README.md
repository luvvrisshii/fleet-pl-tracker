# Fleet P&L Tracker

A simple, offline-capable P&L tracker for your delivery fleet business.

## Features
- Monthly P&L sheets (one per month)
- Revenue, fixed costs, variable costs breakdown
- Per duty analysis (vehicle / bus / hired)
- Break-even calculation
- Summary view across all months
- **All data saved in your browser (localStorage) — no server needed**


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
