# Guide: How to Build a Youth Hockey Player Stats Dashboard Using Google Sheets and GitHub Pages

This guide walks parents or coaches through setting up a modern, mobile-friendly webpage to track a youth hockey player’s statistics. It requires minimal coding knowledge and uses free tools: Google Sheets and GitHub Pages.

---

## ✅ What You’ll Create
A live webpage that displays:
- A player card with name, team, position, and headshot
- A Spring 2025 game log pulled from Google Sheets
- Career stats also pulled from Google Sheets

---

## ⚡️ What You’ll Need
- A **Google account**
- A **GitHub account** ([signup link](https://github.com/join))
- A **headshot** image of the player (optional)
- A **team logo** (optional)

---

## 📝 Step 1: Set Up the Google Sheet
1. Open [this template](https://docs.google.com/spreadsheets/d/1lMEexk9CWTM6A0C_XCyoN_QbKkV2rYhzcr31wA7G62c/copy)
2. Click **“Make a copy”**
3. Fill in the `Game Log` tab with per-game data (date, goals, assists, etc.)
4. Fill in the `Career Stats` tab with season totals
5. Click **Share → Anyone with the link → Viewer**
6. Copy the **Spreadsheet URL** — you’ll need the ID later (the long string in the URL)

---

## 🔧 Step 2: Create Your Webpage
1. Create a new folder on your computer called `player-dashboard`
2. Inside it, create a new file named `index.html`
3. Copy and paste the HTML template provided (see below)
4. Replace `sheetID` in the script section with your Google Sheet’s ID
5. Optional: Add a player headshot by uploading `headshot.jpg` in the same folder and updating the `background-image` URL in the HTML

---

## 💾 Step 3: Upload to GitHub Pages
1. Log into [GitHub](https://github.com) and click **New Repository**
2. Name it something like `player-dashboard`
3. Click **Add file → Upload files**
4. Upload `index.html` (and `headshot.jpg` if using)
5. Click **Commit changes**
6. Go to **Settings → Pages**
7. Under **Source**, select `main` and folder `/root`
8. Click **Save**
9. After a few seconds, GitHub will give you a live URL:

   Example: `https://yourusername.github.io/player-dashboard/`

---

## 📅 Updating Stats
Any time you update the Google Sheet, the dashboard will reflect changes automatically. No need to re-upload anything.

---

## 🎓 Customize Further
- Change colors, fonts, or layout using the CSS styles in the `<style>` section
- Add charts or new tabs (e.g., Tournament stats)
- Use a custom domain (requires more setup)

---

## 🚀 You’re Done!
You now have a shareable, live hockey stats dashboard for your player. Great for family, teammates, or college coaches to view.

Need help? Reach out to a tech-savvy friend — or copy and adapt from someone who already set it up!

