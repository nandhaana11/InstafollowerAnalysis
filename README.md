# InstaTrack 🚀

**Instagram Follower & Unfollower Analyzer** — A clean, fast, 100% private client-side web tool to categorize your Instagram relationships:

- 🚫 **Unfollowed**: Users in your **Following** list but not in your **Followers** list (accounts you follow that do not follow you back).
- 💙 **Fans**: Users in your **Followers** list but not in your **Following** list (accounts that follow you, but you don't follow back).
- 🤝 **Mutual**: Users present in **both** lists (accounts you and each other follow mutually).
- 📋 **All Accounts**: Combined unique list of every account discovered.

---

## 🔒 100% Private & Local
- Runs completely in your browser via local JavaScript.
- **Zero data is uploaded** to any server. Your Instagram credentials, export files, and lists never leave your device.
- Supports both **HTML** (`followers_1.html`, `following.html`) and **JSON** (`followers_1.json`, `following.json`) formats exported from Instagram / Meta Accounts Centre.

---

## 📖 How to Use

### 1. Download your data from Instagram:
1. Go to **Instagram Settings** &rarr; **Accounts Centre** &rarr; **Your Information and Permissions**.
2. Click **Export your information** / **Download your information**.
3. Select **Some of your information** &rarr; check **Followers and Following**.
4. Select Format: **HTML** (or **JSON**) and Date Range: **All time**.
5. Once Instagram emails you the download link, download and unzip the folder.
6. Open `connections/followers_and_following/`. You will find:
   - `followers_1.html` (or `followers.html` / `followers_1.json`)
   - `following.html` (or `following.json`)

### 2. Run InstaTrack:
- Simply open [`index.html`](index.html) directly in any web browser (Chrome, Edge, Firefox, Safari).
- Or run a quick local server:
  ```bash
  python -m http.server 8080
  ```
  Then open [http://localhost:8080](http://localhost:8080).

### 3. Analyze:
1. Upload or drag & drop your **Followers** file.
2. Upload or drag & drop your **Following** file.
3. Click **Analyse Now**.
4. Switch between **Unfollowed**, **Fans**, and **Mutual** using the interactive tabs or stat cards!
5. Search any handle instantly with live filtering, copy individual handles, copy the whole list, or export to `.txt`.

---

## ✨ Features
- 🚫 **Unfollowers View**: See who unfollowed you or doesn't follow back.
- 💙 **Fans View**: See who loves your content without you following back.
- 🤝 **Mutual View**: See all your mutual connections.
- 📋 **One-Click Copy & Export**: Copy individual handles or the full list, or download as a text file.
- ↗️ **Direct Link**: Click to open any profile directly on Instagram (`instagram.com/username`).
- 🔍 **Live Search**: Instant filtering by username in real time.
- 🎨 **Modern Dark UI**: Smooth animations, responsive design, and intuitive metrics.
