<h1>MoneyBug Support</h1>

<p>MoneyBug is a time-tracking and invoicing app for macOS.</p>

<p>This page is where to ask a question, report a problem or suggest a feature.</p>

<h2>Ask a Question</h2>
<p>Not sure how something works, or whether it's a bug? Ask in Discussions. Usage questions, compatibility concerns and general feedback are all welcome, and your question may help the next person.</p>
<p><a href="https://github.com/oddforms-design/MoneyBug/discussions">Open Discussions</a></p>

<h2>Report a Problem</h2>

<p>Bug reports go through GitHub, which keeps everything in one place and lets you see whether someone has already hit the same thing.</p>

<p><a href="https://github.com/oddforms-design/MoneyBug/issues">Browse existing issues</a> &nbsp;|&nbsp; <a href="https://github.com/oddforms-design/MoneyBug/issues/new?template=bug_report.md">Report a new bug</a></p>

<p>Helpful things to include:</p>
<ul>
  <li>Your macOS version and MoneyBug version (MoneyBug → About MoneyBug)</li>
  <li>What you did, what you expected, and what happened instead</li>
  <li>Where in the app it happened: a job, an invoice or estimate, the invoice designer, the menu bar, sync</li>
  <li>Screenshots, if relevant</li>
</ul>

<p>Issue reports are public. Invoices and job lists hold your clients' details, so please blur or crop out names, addresses, amounts and anything else private before posting a screenshot. Never attach a backup file.</p>

<p>If it's a security problem, please report it privately instead: see <a href="SECURITY.md">Security</a>.</p>

<h2>Request a Feature</h2>

<p>MoneyBug is kept deliberately small, so it stays quick to learn and easy to use. Every request is read, but not every one will make it into the app. <a href="FEATURE-REQUESTS.md">How feature requests work</a> explains why, and what makes a request most useful.</p>

<p><a href="https://github.com/oddforms-design/MoneyBug/issues/new?template=feature_request.md">Request a feature</a></p>

<h2>What's New</h2>
<p>Every version's changes are in the <a href="https://github.com/oddforms-design/MoneyBug/blob/main/CHANGELOG.md">changelog</a>.</p>

<h2>Email</h2>

<p>The fastest way to get help is through GitHub, using the links above. Accounts are free, and posting there helps me stay organized. If you'd rather not create an account, email <a href="mailto:support@oddforms.com">support@oddforms.com</a> and I'll get back to you as soon as I can.</p>

<h2>Common Questions</h2>

<h3>Where is my data kept?</h3>
<p>On your Mac, in MoneyBug's own library. MoneyBug has no account and no server of its own, and it doesn't collect or share anything about you or your clients. If you turn on Encrypted Sync with iCloud, your library is also kept in your own iCloud, encrypted first with keys held in your iCloud Keychain, so I can't read it.</p>

<h3>Can I use MoneyBug on more than one Mac?</h3>
<p>Yes. On each Mac, sign in to the same Apple Account and turn on Encrypted Sync with iCloud in MoneyBug → Settings → Sync. A library that has just started syncing can take a few minutes to appear on the other Mac. A timer belongs to the Mac it was started on, but you can stop it from any of them.</p>

<h3>How do I back up, or move to a new Mac?</h3>
<p>MoneyBug backs up your library automatically: once a day, after each update, and before you import a backup. You can see and manage these in Settings → Backups. To keep a copy somewhere of your choosing, use File → Export MoneyBug Backup…. On another Mac, choose File → Import MoneyBug Backup… and pick the file, or turn on Encrypted Sync with iCloud on both.</p>

<h3>Can I try MoneyBug before entering my own work?</h3>
<p>Yes. Choose Help → Explore the Sample Library… to open a made-up design studio's library, with clients, jobs, estimates and invoices to try things on. Your own library isn't touched, and the sample resets when you close it.</p>

<h3>How do I make the invoice look like mine?</h3>
<p>Open a job's invoice and choose Edit Template… to change its layout, fonts and colors. Your business details and logo come from Profile Settings.</p>

<h3>How do I send an invoice?</h3>
<p>Finalize the invoice, then use Share or Save PDF…, and send the PDF however you like. MoneyBug doesn't send email or take payments itself; mark an invoice paid when the money arrives.</p>

<h3>Can I bring my data from another app?</h3>
<p>MoneyBug can't open other apps' libraries, but File → Import Time from CSV… reads the time reports many apps export as CSV, and adds them to the profile you choose, or a new one. It's experimental, so check the preview it shows before importing.</p>

<h3>I forgot my backup password</h3>
<p>If you turned on Encrypt Local Backups, the Mac that made them remembers the key, so they open there without the password. If you also turned on Save Backup Password in iCloud Keychain, your other Macs can open them too. Anywhere else, an encrypted backup needs its password, and without it the backup can't be opened, by you or by me. Backups made while encryption was off are not encrypted.</p>

<h3>An invoice number isn't what I expected</h3>
<p>Each client has its own number format. In the client's settings, choose Customize… beside Next Invoice Number (or Edit Scheme… in an invoice's bar) to see the format and the next value of each counter: Client #, Profile # and Global #. You can change a counter's next value there. Typing a number into an invoice draft uses that number without moving any counter.</p>

<h3>How do I remove MoneyBug and its data?</h3>
<p>Moving MoneyBug to the Trash leaves your library on the Mac. To remove it, open MoneyBug → Settings → Security and choose Delete All MoneyBug Data on each Mac. If the Mac syncs, it also offers to delete your data from iCloud, which turns sync off on your other Macs. To take MoneyBug off your iCloud storage list too, go to System Settings → Apple Account → iCloud. Then move MoneyBug to the Trash. Backups you exported elsewhere aren't touched.</p>

<h3>What does MoneyBug need?</h3>
<p>A Mac with macOS 15.2 Sequoia or later. Sync needs an Apple Account signed in to iCloud.</p>

<h2>About</h2>

<p>MoneyBug is made by <a href="https://oddforms.com">Oddforms Design</a>, a one-person studio. It's a closed-source app for tracking time and sending invoices on the Mac.</p>
