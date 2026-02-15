---

# 🐍 Snake Royale — Multiplayer Discord Snake

Play **real-time multiplayer Snake inside Discord** — no installation required.

Just download the `.exe`, run it, add your bot token, and play.

---

## 🎮 Features

* 🧑‍🤝‍🧑 Multiplayer Snake in one Discord message
* 🎮 Reaction-based controls
* ⌨️ WASD keyboard movement
* 🍎 Live food spawning
* 🏆 Automatic ranking with medals
* ⚙️ Customizable board size
* 📦 Standalone Windows executable

---

## 🚀 How To Use

### 1️⃣ Download

Download:

```
snake.exe
```

---

### 2️⃣ First Launch

Double-click `snake.exe`.

If `creds.txt` does not exist, the program will:

* Create `creds.txt`
* Show this inside:

```
token:"Your Token"
Width:20
Height:12
```

The bot will then close.

---

### 3️⃣ Configure Bot

Open `creds.txt` and replace:

```
token:"Your Token"
```

with your actual Discord bot token.

Example:

```
token:"YOUR_REAL_BOT_TOKEN"
Width:25
Height:15
```

Save the file.

---

### 4️⃣ Run Again

Double-click `snake.exe` again.

A CMD window will open showing bot logs.

If everything is correct, your bot will come online ✅

---

## 🎯 How To Play

Use slash command:

```
/snake
```

### Lobby (10 seconds)

Click ✅ to join.

### Controls

You can move using reactions:

⬅️ ➡️ ⬆️ ⬇️

Or using chat:

* W → Up
* A → Left
* S → Down
* D → Right

You can queue multiple moves:

```
wwaassdd
```

---

## 🏆 Game Rules

* Eat 🍎 to grow
* Hit wall = eliminated
* Hit any snake = eliminated
* Last snake alive wins
* Final ranking shows 🥇🥈🥉

---

## ⚙️ Config File Settings

| Setting | Description            |
| ------- | ---------------------- |
| token   | Your Discord bot token |
| Width   | Game board width       |
| Height  | Game board height      |

---

## 🔐 Required Discord Settings

In Discord Developer Portal:

* Enable **Message Content Intent**
* Enable **Server Members Intent** (if needed)

---

## 🖥 Platform

* Windows 10 / 11
* No Python required
* No installation required

---

## 🛡 Security Note

Never share your bot token with anyone.

If leaked, regenerate it immediately in the Discord Developer Portal.

---

## ⭐ Support

If you enjoy this project, consider starring the repository!

---

If you'd like, I can now create:

* 🔥 A super flashy animated GitHub profile-style README
* 🧱 A minimal clean professional README
* 🎮 A gamer-themed neon README
* 🏢 A polished open-source portfolio version

Just tell me the vibe you want 😎
