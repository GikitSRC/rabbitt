# 🐰 rabbitt
An AI. But not just any AI - an "agent" that can do tasks on your behalf. Fun weekend side project I made 😄 <br>
You can use your R1 to send Discord messages and control Rabbitt - [here](https://github.com/GikitSRC/rabbitt_integration). If you like this project, leave it a ⭐!

---

# 🛠️ How does it work?
```
+-------------------------------+
|  User inputs website &        |
|  instructions to do on        |
|  website                      |
+-------------+-----------------+
              |
              v
+-------------+-----------------+
| Axios retrieves website's     |
| HTML                          |
+-------------+-----------------+
              |
              v
+-------------+-----------------+
| Sends website's HTML to       |
| first Gemini AI               |
+-------------+-----------------+
              |
              v
+-------------+-----------------+
| First Gemini AI makes         |
| description of all IDs and    |
| attributes                    |
+-------------+-----------------+
              |
              v
+-------------+-----------------+
| Sends attributes and IDs to   |
| second Gemini AI              |
+-------------+-----------------+
              |
              v
+-------------+-----------------+
| Second Gemini AI makes        |
| playwright script along with  |
| user's instructions           |
+-------------+-----------------+
              |
              v
+-------------+-----------------+
| child_process executes        |
| playwright script             |
+-------------+-----------------+

```
In reality, it really just uses Gemini 1.5 Pro to make a Playwright script
---

# 🚀 How to set it up?
Easy peasy lemon squeezy! Just copy and paste these commands into your terminal, or run install.bat:

```bash
git clone https://github.com/GikitSRC/rabbitt
cd rabbitt
npm init -y
npm install
npx playwright install
node server.js
```
After that, open up the .env files and put 2 API keys in. You can get them for free at [AI Studio](https://aistudio.google.com). <br>
Go to [this website](https://localhost:3000) on any web browser connected to the same WiFi to see the results! 😎

# 🎥 Video Demos
[Sending Prompt to ChatGPT](https://i.e-z.host/c2e9iqos.mp4) (silly AI) <br>
[Logging in to Discord](https://i.e-z.host/boarys0m.mp4) (... fake passw ofc + no captcha support) <br>
[ThriveOS](https://i.e-z.host/dy0vm9p8.mp4) (ITS MY WEBSITE!!!!)
<br>
<br>
By the way... you can control all of this + sending message on Discord with your R1. <br>
More information [here](https://github.com/GikitSRC/rabbitt_integration)

# 🌐 [ThriveOS](https://thriveos.pages.dev/)
Advertisement for custom a web based operating system I didn't finish yet :) 
