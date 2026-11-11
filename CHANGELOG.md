# MoneyBug Changelog

What changed in each version of MoneyBug, newest first. Issue numbers link to this repository's [issues](https://github.com/oddforms-design/MoneyBug/issues).

## 1.0.1 (TestFlight)

- A new look, rebranded to fit in with Liquid Glass:
  - A new app icon.
  - An accent color in Settings → General: Blue, Mint, Brown or Graphite, each with its own shade in dark mode.
  - Client colors refreshed to match. A color you picked yourself stays as it is.
  - Liquid Glass on the controls that float over your documents and lists, and on macOS 27, on the sidebar's buttons and Dashboard tile.
- Quantities for line items: fixed costs, expenses and credits take a quantity and a unit price, with optional Qty and Rate columns in the Invoice Designer ([#8](https://github.com/oddforms-design/MoneyBug/issues/8)).
- "Updating Your Library", with a count, the first time an update syncs, instead of a sync that seemed stuck ([#2](https://github.com/oddforms-design/MoneyBug/issues/2)).
- Time worked on the Dashboard and client pages counts your time as rounded, matching the task rows.
- Revise Invoice and Revise Estimate in the ⋯ menu, and Discard Revision names the revision it discards.
- Un-finalize right from a finalized invoice's fields, beside starting a revision.
- Balance Due in the job's header once a payment is recorded.
- A deposit's line on the balance invoice is named with the date it was paid, and can be edited in the job.
- After a crash or force quit with a timer running, MoneyBug asks what to do with the time instead of deciding for you.
- Purchase MoneyBug… and Restore Purchase stay in the menus until you've bought MoneyBug.
- Clearer wording about what's encrypted in iCloud.
- Fixes:
  - A short pinwheel at launch: automatic backups now run in the background.
  - The away question after the Mac slept could show the wrong times.
  - A purchase could show as the free version after a restart.
  - A draft invoice could keep its old look after a design change.
  - In the Invoice Designer, a second details box didn't follow the first one's switches.
  - Settings could open with empty tabs after MoneyBug was locked.
  - Three-letter client initials wrapped onto two lines.
  - The Sample Library could show an open job with a negative balance.
  - Two rare sync cases: an item moved into a section deleted on another Mac, and updating again after going back to an older version.

## 1.0

The first version, released November 11, 2026: time tracking and invoicing, made for the Mac.

- A timer on every task, from the job or the menu bar, with the rounding you choose and a question when you come back from being away.
- Fixed costs, expenses, mileage and discounts beside your time, grouped into sections.
- Estimates and invoices from the same job, with deposits, payments, revisions and numbering for each client.
- The Invoice Designer: your own layout, fonts, colors and logo, or one of the built-in designs.
- A Dashboard of the time you've worked, what's not yet invoiced and what's waiting for payment, and a page for every client.
- Profiles, each with its own details and invoice numbers.
- Sync between your Macs through your own iCloud, your library's contents encrypted before they're sent.
- Automatic backups, encrypted if you like, plus Export as CSV and Import Time from CSV.
- An app lock with Touch ID or your Mac's password.
- A Sample Library to try everything on before entering your own work.
- Free for your first three jobs. One purchase unlocks the rest, on every Mac you own and with Family Sharing, with no subscription.
