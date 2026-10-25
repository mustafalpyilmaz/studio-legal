---
description: "Feeprune is a Mac app that shows each listing's profit after its ad fee, for eBay sellers who run Promoted Listings."
---
# Feeprune

Feeprune is a Mac app that shows each listing's profit after its ad fee, for eBay sellers who run Promoted Listings.

Since January 2026, eBay charges General ad fees on more sales, and Seller Hub no longer splits direct and halo sales. One seller on the eBay Community called it a stealth fee increase. Others say they cannot tell which ad fees bought real sales. Feeprune reads one month of your Transaction report and names the listings where the ad does not pay.

## What it does
- Reads the Transaction report CSV from Seller Hub, by drop or Open window. Rows group by listing and calendar month.
- Shows each listing's units sold, sales, eBay fees, ad fee, cost per item and profit after ad.
- Keeps the cost you type for an item, and uses it again in every month with that item.
- Flags "Ads not paying": a listing whose ad fee took more than half of its profit before the ad fee.
- Totals the month: sales, eBay fees, ad fees, item costs, profit after ads and the ad fees spent where ads don't pay.
- Free: one month, with every feature above.
- Feeprune Pro, a one-time purchase of $4.99 in the US, adds:
  - All imported months, picked from the month menu.
  - Max ad rate for each listing, next to its current rate. Below eBay's lowest rate of 2%, it says Remove ad.
  - Export Flagged: the flagged listings as a CSV file with their rates, ad fee and profit after ad.
  - Import Costs: item costs from a CSV file keyed by Item ID or Custom label.

## Works with
- The eBay Seller Hub Transaction report, downloaded as a CSV file from Payments, then Reports.
- Cost files in CSV format with an "Item ID" or "Custom label" column and a "Cost" column.
- Exported CSV files open in Numbers, Excel and Google Sheets.

Feeprune is not made by or affiliated with eBay Inc.

## What it does not do
- It does not connect to eBay or any server. It reads only the files you pick or drop.
- It does not read the Orders report or the advertising reports.
- It does not set ad rates. You set them in Seller Hub.
- It reads one currency per report. Create one report per eBay site.
- Profit after ad is only as good as the costs you type. A listing with no cost counts it as zero.

## Requirements
macOS 26 or later, on Apple silicon or Intel.

## Questions
**Can Feeprune show which promoted listings lose money to ad fees?**
Yes. Feeprune flags each listing whose ad fee took more than half of its profit before the ad fee, or that made no profit before it.

**Does Feeprune prove which sales came from an ad click?**
No. eBay's reports do not say which click led to a sale. Feeprune shows what each listing kept after the ad fee eBay charged on it.

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
