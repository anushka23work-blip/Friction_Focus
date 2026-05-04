# Friction_Focus
Friction Focus
Complete Product Guide  ·  Powered by Scroll Brakers

🌐 Web App
📱 PWA – Android Ready
🧩 Chrome Extension
🎮 Gamer Extension
🔐 Face Auth
🔥 Firebase Powered
📋 Table of Contents
1. Install as App (PWA)
2. Get & Install Extension
3. Home Page
4. Parental Gate / Login
5. Dashboard Overview
6. Site Analytics
7. Face Registration & Unlock
8. Browser Controls
9. Procrastination Punisher
10. Generate Report📱
Install as App on Android
Add Friction Focus to your home screen — works like a native app, no Play Store needed

📱 Friction Focus is a Progressive Web App (PWA). Open it in Chrome on Android and install it directly to your home screen. It launches full screen with no browser bar — exactly like a native app.

🌐Step 1: Open Chrome on Android and go to the app URL

🟣Step 2: Tap the Install banner that appears at the bottom 

🏠Step 3: Icon appears on home screen — tap to open full screen

📲 How to Install — Step by Step

Follow these steps on your Android phone
1. Open Chrome on your Android phone — must be Chrome, not Samsung Browser or Firefox

2. Go to: https://avataar-alert01.web.app

3. Wait for the page to fully load — a purple banner will appear at the bottom saying "Install Friction Focus"

4. Tap Install on the banner — done!

★
If no banner appears — tap the ⋮ three-dot menu (top right of Chrome) → tap "Add to Home screen" → tap Add

🖥️
Full Screen Launch
Opens without Chrome's URL bar — feels exactly like a native mobile app.

📶
Offline Support
Service Worker caches the app so it loads instantly even on slow connections.

🔄
Auto Updates
When the app is updated on Firebase, the PWA updates automatically in the background.

📲
Share the Link
Send the web.app URL to anyone — they can install it on their Android the same way.

✅ Once installed, the Friction Focus icon appears on your Android home screen and in the app switcher — tap it anytime to manage your child's screen time remotely.
🧩
Get & Install the Extensions
Download from Google Drive and load into Chrome in 4 steps

🗂️ Both extensions are stored in the Avtaar_Alert Google Drive folder. Download them, extract the zip, and load into Chrome using Developer Mode — no Chrome Web Store needed.

📥 Step 1 — Download from Google Drive
Click the button below to open the shared folder
Open Avtaar_Alert on Google Drive

1. Click the button above — Google Drive opens in your browser

2. You will see two folders — Friction Focus Extension and Procrastination Punisher

3. Right-click the folder you want → click Download — it downloads as a .zip file

4. Go to your Downloads folder — right-click the .zip → click Extract All → click Extract

5. You now have an extracted folder — keep this path handy, you will need it in the next step

🔧 Step 2 — Load into Chrome as Unpacked Extension
Do this on the child's PC where you want the extension to run
1. Open Google Chrome on the PC

2. In the address bar, type exactly and press Enter:

chrome://extensions

3. In the top-right corner of the Extensions page, toggle Developer mode ON — the toggle turns blue

4. Click the Load unpacked button that appears on the left

5. A file picker opens — navigate to your extracted folder and select the extension folder (the one that contains a file named manifest.json inside)

6. Click Select Folder — the extension appears in the list with its icon

7. Pin it to the toolbar — click the puzzle piece 🧩 icon in Chrome toolbar → click the pin 📌 next to the extension

✅ The extension icon now appears in the Chrome toolbar. Click it to open the popup and sign in with the same Firebase account used on the dashboard.
🎮 To install the Procrastination Punisher extension — repeat the exact same steps above but download and select the Procrastination Punisher folder from Drive instead. Both extensions can be installed at the same time.
Friction Focus Extension Popup
🧩 Friction Focus Extension — Digital Control timer popup showing time remaining and lock status
⏳
Countdown Timer
Shows time remaining. When it hits zero, browser locks automatically.

🔒
Lock Status
Shows LOCKED in red. Child cannot unlock from the extension — only the dashboard can unlock.

📡
Firebase Connected
Listens to Firebase in real time. Parent sends a command → extension reacts within seconds.

🚫
Dashboard Only Unlock
"Locked – Use dashboard to unlock" — children cannot bypass parent controls.

🏠
Home Page
The landing page — first thing users see

Friction Focus Home Page
🏠 Friction Focus landing page — Make Distraction Difficult. Make Focus Natural.
🎯
Hero Section
Bold headline with live stats — 12K+ sites tracked, 98% friction rate, 2.4× focus boost.

🧭
Navigation
Home, Parent Gate, Dashboard, About, and a prominent Get Extension button in the navbar.

🔑
Parent Login
Direct access button to the Parental Gate for parents to manage restrictions.

📊
View Dashboard
Jump straight into the live dashboard to view screen time and usage data.

🔐
Parental Gate
Secure parent-only login to access the control panel

Parental Gate Login
🔐 Parental Gate — Sign In or Create Account with email + 6-digit PIN
👨‍👩‍👧
Parent / Guardian Role
Role is locked to Parent/Guardian — children cannot access this gate.

📧
Email + PIN Login
Sign in with your email and a 6-digit PIN. Quick and secure.

🆕
Create Account
New users can create an account directly from this screen.

🔁
Forgot PIN
Reset your PIN via email if you forget it.

1
Click Parent Gate in the navbar or Parent Login on the home page

2
Click Sign In if you have an account, or Create Account if new

3
Enter your email address and 6-digit PIN

4
Click Access Control Panel — you are taken straight to the dashboard

📊
Dashboard Overview
The main control panel — live stats and full browser control in one place

Dashboard Overview
📊 Friction Focus Tracker Dashboard — live stats, controls, and site analytics
⏱️
Total Time Online
Live screen time counter with daily limit progress bar.

🌐
Most Visited Site
Shows the top visited site of the day with share of total traffic.

🔒
Browser Status
Real-time lock/unlock status with engagement percentage.

⚠️
Friction Events
Total blocks triggered today with override rate percentage.

Dashboard action buttons:

🔒 Lock
⏰ Reset
🔓 Unlock
📸 Register Face
🔐 Unlock with Face
📥 Get Extension
📄 Generate Report
🚪 Logout
📈
Site Usage Analytics
Live tracking of every website visited — updates in real time

Site Usage Analytics
📈 Site Usage Analytics — live table with visit counts, timestamps, and tracked status
🟢
Live Updates
Table updates in real-time as the child browses — powered by Firebase Realtime Database.

🔢
Visit Count
Each site shows how many times it was visited today with a numbered badge.

🕐
Last Visited
Exact timestamp of the last visit to each website.

✅
Tracked Status
Every site is marked Tracked so parents know what is being monitored.

🤖
Face Registration & Unlock
AI-powered facial recognition — only the registered parent can unlock

🤖 Uses face-api.js — AI runs entirely in the browser. No face data is sent to any external server. The face descriptor is saved securely in Firebase under your account only.
📸
Register Face
Click Register Face → allow camera → look at camera → face saved to Firebase in 3 seconds.

🔐
Unlock with Face
Click Unlock with Face → look at camera → if matched, browser unlocks. Wrong person = access denied.

✅
Face Ready Badge
Green "Face ready" badge on dashboard confirms face is registered and AI is loaded.

🔒
Secure by Design
Strict match threshold — only the registered parent's face unlocks. No PIN bypass possible.

1
Click Register Face on the dashboard

2
Allow camera access when browser asks

3
Look directly at the camera and click the capture button

4
Face saved to Firebase — dashboard shows ✅ Face ready

5
To unlock the browser — click Unlock with Face → look at camera → browser unlocks automatically

🎮
Browser Controls
Remote lock, unlock and reset — commands sent via Firebase to the extension instantly

🔒
Lock
Immediately locks the browser. Extension shows a locked screen and blocks all navigation.

🔓
Unlock
Sends unlock command via Firebase. Extension receives it and resumes normal browsing.

⏰
Reset Timer
Resets the daily screen time counter. Useful for giving extra time or starting fresh.

🔐
Face Unlock
Parent verifies their face — on match, unlock command is sent to extension automatically.

✅ All commands go through Firebase Realtime Database — the extension responds within 1–2 seconds even if the dashboard is open on a phone and the browser is on a separate PC.
💀
Procrastination Punisher
The gamer extension — set a doom timer, face the consequences

Procrastination Punisher
💀 Procrastination Punisher — doom timer with 4 punishment modes
⏱️
Doom Timer
Set hours, minutes, seconds. When time is up — punishment activates automatically.

🐱
Cat Video
Fullscreen cat takeover — screen is taken over by a cat video.

🌀
Invert Colors
The entire screen colors are inverted making browsing uncomfortable.

🧱
Infinite Wall
An infinite brick wall blocks all content — kills the endless scroll.

🌫️
Gradual Blur
Screen slowly fades to nothing — content becomes increasingly blurry over time.

🔥
No Tracking
Runs independently — no Firebase, no dashboard. Pure self-enforced focus.

💀 This extension is self-contained and does not connect to Firebase or the dashboard. It is a standalone focus tool for gamers and students who want to self-enforce focus sessions.
📄
Generate Report
Export a PDF of daily usage and send it via email

📊
Full Usage Report
Includes total screen time, most visited sites, friction events, and browser status.

📥
PDF Download
Generated as a PDF and downloaded automatically to your device.

📧
Email via Mailto
Email client opens with a pre-filled message — attach the PDF and send to co-parents or teachers.

🔐
Parent Only
Only available after parent login — children cannot access or delete reports.

1
Log in through Parental Gate and open the Dashboard

2
Click the 📄 Generate Report button

3
PDF is generated and downloaded automatically

4
Email client opens pre-filled — attach the PDF and send

Friction Focus
Powered by Scroll Brakers  ·  © 2026 All rights reserved
https://avataar-alert01.web.app


