---
description: "Feeprune is a Mac app that shows each listing's profit after its ad fee, for eBay sellers who run Promoted Listings."
---
# Feeprune

Feeprune is a Mac app that shows each listing's profit after its ad fee, for eBay sellers who run Promoted Listings.

From January 13, 2026, more eBay sales carry a General ad fee, and Seller Hub reports direct and halo sales as one number. One seller on the eBay Community called it a stealth fee increase. Others say they cannot tell which ad fees bought real sales. Feeprune reads one month of your Transaction report and names the listings where the ad does not pay.

## What it does
- Reads the Transaction report CSV from Seller Hub, by drop or Open window. Rows group by listing and calendar month.
- Shows each listing's units sold, sales, eBay fees, ad fee, cost per item and profit after ad.
- Keeps the cost you type for an item, and uses it again in every month with that item.
- Flags "Ads not paying": a listing whose ad fee took more than half of its profit before the ad fee.
- A bar above the table sums sales, eBay fees, ad fees, item costs and profit after ads for the month. Its last figure is the ad fees spent on flagged listings, with their count.
- Free: one month, with every feature above.
- Feeprune Pro, a one-time purchase of $4.99 in the US with no subscription, adds:
  - All imported months, picked from the month menu.
  - Max ad rate for each listing, next to its current rate. If the max falls under 2%, eBay's lowest General rate, the cell reads Remove ad.
  - Export Flagged: one CSV row per flagged listing, with Item ID, title, both rates, ad fee and profit after ad.
  - Import Costs: item costs from a CSV file keyed by Item ID or Custom label.

## Works with
- The eBay Seller Hub Transaction report, downloaded as a CSV file from Payments, then Reports.
- Cost files in CSV format with an "Item ID" or "Custom label" column and a "Cost" column.
- Exported CSV files open in Numbers, Excel and Google Sheets.

Feeprune is not made by or affiliated with eBay Inc.

## What it does not do
- It does not connect to eBay or any server. It reads only the files you pick or drop.
- Only the Transaction report imports. An Orders report or an advertising report shows an error and adds nothing.
- It does not set ad rates. You set them in Seller Hub.
- It reads one currency per report. Create one report per eBay site.
- Profit after ad is only as good as the costs you type. A listing with no cost counts it as zero.

## Compared with
- eBay Seller Hub advertising dashboard: free and built in. It cannot show which ad fees paid off.
- Sellerfuse: £19.99 a month. Its profit dashboard takes ad fees off each sale, with no Promoted Listings ROI per listing.
- ResaleOS: $24.99 a month. A crosslister and reseller suite with no per-listing ad fee analysis.
- Ecomli: $29 to $199 a month. It shows Promoted Listings cost for the whole store, not per listing.
- 3Dsellers eBay Ads: from $19 a month. It manages campaigns and bids in bulk. Its pages show no profit after ad fee per listing.
- Flippedit: free. It syncs through eBay's API and shows profit per item after fees, with no ad fee audit per listing.
- Slayva's Promoted Listings calculator: free, for one item at a time. It does not read your reports.
- Feeprune: free for one month, or $4.99 once for every month. It reads your Transaction report and judges the ad fee of each listing.

## Requirements
macOS 26 or later, on Apple silicon or Intel.

## Questions
**Can Feeprune show which promoted listings lose money to ad fees?**
Yes. Feeprune flags each listing whose ad fee took more than half of its profit before the ad fee, or that made no profit before it.

**Can Feeprune judge an ad fee without knowing which click led to the sale?**
Yes. eBay's reports do not say which click led to a sale. Feeprune judges each listing by what it kept after the ad fee eBay charged on it.

**Does Feeprune need my eBay password or API access?**
No. Feeprune reads the Transaction report CSV that you download from Seller Hub. It has no network access.

**Can Feeprune tell me what ad rate to set?**
Yes, with Pro. Feeprune shows the highest rate at which the ad fee stays within half of the profit before the ad fee.

**Does Feeprune handle multi-item orders and refunds?**
Yes. Feeprune counts each multi-item order and refund once per listing. Ad fee rows without an Item ID go to the order's items.

**Is Feeprune free?**
Yes, for one month at a time. Feeprune Pro is a one-time purchase of $4.99 in the US for every month and the Pro tools.

## Get it
Feeprune is coming to the Mac App Store. The download link goes here at launch.

[Support](https://mustafalpyilmaz.github.io/studio-legal/feeprune/support.html) · [Privacy Policy](https://mustafalpyilmaz.github.io/studio-legal/feeprune/privacy-policy.html)
