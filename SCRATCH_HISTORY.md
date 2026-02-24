## 🔨😾 Scratch Ban: The Incident Report

### 🚩 Why I was Banned
* **Gvbvdxx Chat:** Used `innerHTML` instead of `textContent`. Users exploited this via **XSS** to inject scripts. My client-side IP ban system was too weak to stop them.
* **The API Bot & The Mute Cycle:** I created a Node.js bot using the Scratch API that allowed users to post comments anonymously. I ran the bot on a separate, dedicated alt account. 
* **The "Iframe of Doom":** I actually knew the bot was a massive risk. I even hardcoded a "banned iframe" into the bot's site so people could read *why* it was banned when the time inevitably came. I shrugged it off at the time, but the Scratch Team definitely didn't.
* **The Trace & Final Strike:** The *bot account* got stuck in a loop of getting muted, serving the time, getting the automated *"Welcome back to Scratch!"* message, and getting muted again based on what users posted. Eventually, the Scratch Team tracked the bot back to my main account (likely via IP or email). They permanently banned both the bot and my main account.

### 🚪 The Exit Strategy: Why I Didn't Go Anonymous
After the ban, I tried making new, anonymous accounts to keep coding. But because I have years of experience with Scratch, I knew I was going to keep making high-quality, popular projects. 

I quickly realized something weird: **if this "fake" persona got famous, I would end up being jealous of *myself*.** Pretending to be someone else and hiding my identity made me feel like I was living as two different people, and I hated lying about who I was just to stay on the platform. Instead of keeping up the act, I decided to take a clean break and **actually asked the Scratch Team to delete my main account.**

### 💾 The Great Rescue

Before I sent that final deletion request, I ran a **custom Node.js scraping script** I wrote to back up every single shared project across my main and all my alt accounts. 
* **[View the rescued projects here!](./projects/README.md)**

### 🛡️ Hard-Learned Lessons
1. **Never post unmoderated cloud chats.** It's a ban-magnet.
2. **Alt Accounts Aren't Shields.** If you build an API bot or a rule-breaking tool on a burner account, the Scratch Team *will* trace it back to your main.
3. **API Bots are a Liability.** Even if you aren't the one typing the messages, if your bot posts it, *you* take the fall. 
4. **Don't Taunt the Filter:** Building a "why I got banned" screen before you even get banned is funny, but it proves you knew you were breaking the rules!
5. **Authenticity Matters:** Living a double life on burner accounts is exhausting. If you want to build raw/13+ projects, just move to GitHub or Render where you can take real credit for your work.

---
[**⬅️ Back to profile**](./README.md)
