# Robinson Finances app

Installable home-screen app for the Robinson Finances dashboard (a Google Apps Script web app).
This site holds only the app shell: an icon, a manifest and a frame that opens the dashboard.
No financial data is stored here; signing in happens inside the dashboard.

Open https://jrobin1216-lab.github.io/robinsonbudget/ on your phone, then:
- Android (Chrome): menu ⋮ → Install app
- iPhone (Safari): Share → Add to Home Screen

Face ID lock (installed app only): after installing, the app offers to lock itself with Face ID or a fingerprint.
It asks when the app opens and after it has been in the background for 5 minutes. The passkey stays on the phone
and is used only for this lock. "Use my password instead" signs the dashboard out, so the password is still needed.
