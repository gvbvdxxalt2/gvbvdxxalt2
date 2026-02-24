## 🔨😾 Scratch Ban: The Incident Report

### 🚩 Why I was Banned
* **Gvbvdxx Chat:** Used `innerHTML` instead of `textContent`. Users exploited this via **XSS** to inject scripts. My client-side IP ban system was too weak to stop them.
* **The API Bot:** Created a Node.js bot for anonymous commenting. Because I didn't filter the input strictly enough, it was used to bypass Scratch's community filters.

### 💾 The Great Rescue
Before the Scratch Team deleted my main account, I ran a **custom Node.js scraping script**. I successfully backed up every shared project across my main and all alt accounts.
* **[View the rescued projects here!](./projects/README.md)**

### 🛡️ Hard-Learned Lessons
1. **Never post unmoderated cloud chats.** It's a ban-magnet.
2. **API Tools are a trap.** If users can post through your bot, *you* are responsible for what they say.
3. **Keep it Raw:** If you want to build something 13+ or technically "raw," host it on GitHub or Render. Keep your Scratch profile "clean" or lose your work.

---
[**⬅️ Back to profile**](./README.md)
