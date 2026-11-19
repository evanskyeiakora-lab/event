THE BEST COUPLE · EFFECT'26 — DOMINIC & HELENA

PACKAGE FILES
- index.html: Main wedding website, now with a live countdown timer.
- thank-you.html: Separate digital thank-you page.

COUNTDOWN TIMER
- Counts down to Saturday, 28 November 2026, at 9:30 AM Ghana time (UTC).
- Updates every second with days, hours, minutes, and seconds.
- On the event day/time, displays a celebration message. After the event, displays a thank-you message.

HOW TO TEST LOCALLY
1. Extract this ZIP.
2. Open index.html in a browser or use VS Code Live Server.
3. Confirm the countdown appears and the seconds change every second.
4. Optional completion test: In index.html, temporarily replace the weddingDate line with:
   const weddingDate = Date.now() + 10000;
   Save and refresh; after about 10 seconds, the celebration message should appear.
5. Restore the original date line after testing.

UPDATE YOUR GITHUB PAGES SITE
1. Copy both index.html and thank-you.html into your D:\events repository folder.
2. In PowerShell, run:
   git add index.html thank-you.html
   git commit -m "Add live wedding countdown timer"
   git push
3. Allow GitHub Pages a few minutes to publish.

NOTE: The event time currently shown in the hero section is 9:30 AM. The countdown is aligned to that time (Ghana is UTC).
