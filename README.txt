MY TIME CLOCK

A private, local-first time clock web app for iPhone.

FEATURES
- Clock in / clock out and track unpaid breaks
- Add and edit past shifts
- Hourly wage and configurable weekly overtime estimate
- Weekly and pay-period hours and estimated gross pay
- CSV timesheet export and full JSON backup/restore
- Offline support after the first load when hosted over HTTPS

IMPORTANT SETUP
This is a static web app. To install it as an iPhone Home Screen app, host these files on an HTTPS static host (for example, a free GitHub Pages site or Netlify static site), open that URL in Safari, tap Share, then Add to Home Screen.

The app stores records in Safari's local browser storage on that device. It does not sync between devices. Export a JSON backup regularly. Do not clear Safari website data unless you have a backup.

OVERTIME
The app estimates overtime after the configured hours per calendar workweek (Monday-Sunday). It is a personal estimate, not a payroll/legal compliance system. Check your applicable rules and pay stub.

FILES
- index.html: app
- manifest.webmanifest: install metadata
- sw.js: offline cache
- icon.svg: app icon
