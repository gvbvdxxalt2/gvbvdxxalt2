[Back to profile](./README.md)

### 🔨😾 The "Incident Report": How I got banned from Scratch

#### 💬 The Gvbvdxx Chat Era (The First Bans)
When I was first learning **Socket.io** and **Glitch.com**, I built "Gvbvdxx Chat." It was a simple relay server: whatever you sent, the server echoed to everyone. Naturally, I shared it on Scratch to get an audience.

**The Technical Failures:**
* **XSS Vulnerability:** I was using `innerHTML` instead of `textContent`. Users quickly figured out they could inject scripts and HTML to break the site or redirect people.
* **Security Flaws:** My "IP Ban" system was entirely client-side. It just told the browser, "Hey, please don't let this guy talk," which was trivial to bypass.
* **Moderation:** I thought I was moderating, but "User123" proved that a manual ban-hammer can't keep up with someone dedicated to breaking the rules.

Because I kept sharing the link after being warned, the Scratch Team eventually handed out a permanent ban.

#### 🤖 The Anonymous Commenter (The Final Ban)
Later, I experimented with the **Scratch API** using Node.js. I built a bot that allowed users to post comments anonymously. 

**The Result:**
Since I wasn't strictly filtering what people sent through the bot, it became a tool for people to bypass Scratch's filters. The bot and my account were banned simultaneously. 

**The Exit Strategy:**
After a few attempts at new accounts, I realized the bridge was burnt. I asked the Scratch Team to delete my main account, but not before I ran a **custom Node.js backup script** I wrote to scrape and save every single shared project across my main and **all my alt accounts**. 

> [!TIP]
> These projects were succesfully restored:
> **[Click here to view the rescued projects!](./projects/README.md)**

 [Back to profile](./README.md)
