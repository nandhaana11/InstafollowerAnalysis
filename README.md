# InstaTrack 🚀

**Instagram Follower & Unfollower Analyzer** — A clean, private, client-side web tool to discover:
- 👻 **Not Following Back**: Accounts you follow that don't follow you back.
- ✅ **Mutuals**: Accounts that follow each other.
- 💙 **Fans Only**: Accounts that follow you, but you don't follow back.
- 📋 **All**: All unique accounts combined.

---

## 🔒 100% Private & Local
- Runs completely in your browser.
- **Zero data is uploaded** to any server. Your Instagram credentials or files never leave your computer.

---

## 📖 How to Use

### 1. Download your data from Instagram:
1. Go to **Instagram Settings** &rarr; **Accounts Centre** &rarr; **Your Information and Permissions**.
2. Click **Export your information** / **Download your information**.
3. Select **Some of your information** &rarr; check **Followers and Following**.
4. Select Format: **HTML** and Date Range: **All time**.
5. Once Instagram emails you the download link, download and unzip the folder.
6. Open `connections/followers_and_following/`. You will find:
   - `followers_1.html` (or `followers.html`)
   - `following.html`

### 2. Run InstaTrack:
- Simply open [`index.html`](index.html) directly in any web browser (Chrome, Edge, Firefox, Safari).
- Or run a quick local server:
  ```bash
  python -m http.server 8080
  ```
  Then open `http://localhost:8080`.

### 3. Analyze:
1. Drag & drop or select your **Followers** file.
2. Drag & drop or select your **Following** file.
3. Click **Analyse Now**.
4. Use the tabs to browse categories, search usernames, and click the **copy** icon or **Copy All**!

---

## ✨ Features
- 📋 **One-Click Copy**: Copy any single username or copy all usernames in a tab.
- ↗️ **Direct Link**: Click to open any profile directly on Instagram.
- 🔍 **Live Search**: Filter accounts instantly by username.
- 🎨 **Modern Dark UI**: Smooth gradients, responsive layout, and intuitive statistics.
