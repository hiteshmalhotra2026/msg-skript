# 📩 Msg — Private Messaging System

> A clean, lightweight, and fully-featured private messaging system for Minecraft servers using Skript.

Developed by **HACK Studio | itzz_hitesh**

---

## ✨ Features

- 💬 `/msg` command for private messaging
- 🔄 `/reply` and `/r` to quickly reply to your latest conversation
- 🔕 `/msgtoggle` to enable or disable direct messages
- 👀 `/socialspy` for staff to monitor private conversations
- 🛡️ Staff bypass system (`msg.bypass`)
- 📌 Staff can message players even when DMs are disabled
- 🏷️ Social Spy displays a **[BYPASS]** tag for audit tracking
- 🎨 Fully configurable messages, colors, prefixes, and sounds
- ⚡ Lightweight and easy to configure

---

# 📦 Requirements

- **Minecraft Server**
- **Skript 2.6+**

---

# 📥 Installation

1. Download the Skript file.
2. Place it inside:

```
plugins/Skript/scripts/
```

3. Reload Skript:

```
/sk reload Msg
```

or

```
/sk reload all
```

---

# 📖 Commands

| Command | Description |
|----------|-------------|
| `/msg <player> <message>` | Send a private message |
| `/reply <message>` | Reply to your latest conversation |
| `/r <message>` | Shortcut for `/reply` |
| `/msgtoggle` | Enable or disable private messages |
| `/socialspy` | Toggle Social Spy |

---

# 🔑 Permissions

| Permission | Description |
|------------|-------------|
| `msg.use` | Allows use of `/msg`, `/reply`, and `/r` |
| `msg.admin` | Allows use of `/socialspy` |
| `msg.bypass` | Bypass disabled private messages |

---

# 🛠 Configuration

Everything is configurable directly inside the Skript file, including:

- Messages
- Prefixes
- Colors
- Sounds
- Social Spy format
- Bypass settings

No additional configuration files are required.

---

# 💡 How It Works

### Private Messages

Players can privately message each other using:

```
/msg Player Hello!
```

### Reply

Reply instantly without typing the player's name:

```
/reply Hi!
```

or

```
/r Hi!
```

### Message Toggle

Players can disable incoming private messages:

```
/msgtoggle
```

Staff members with `msg.bypass` can still message them.

### Social Spy

Staff can monitor private conversations:

```
/socialspy
```

Messages sent using bypass permissions are marked with:

```
[BYPASS]
```

making moderation easier.

---

# ✅ Permissions Example

```yaml
permissions:
  msg.use:
    default: true

  msg.admin:
    default: op

  msg.bypass:
    default: op
```

---

# 📸 Features Overview

- ✅ Clean private messaging
- ✅ Fast reply system
- ✅ DM toggle
- ✅ Staff bypass
- ✅ Social Spy
- ✅ Configurable messages
- ✅ Lightweight
- ✅ Skript 2.6+

---

# 🐛 Bug Reports

Found a bug?

Please open an issue on GitHub with:

- Server version
- Skript version
- Error logs (if any)
- Steps to reproduce

---

# 💬 Support

Need help or have suggestions?

Feel free to contact:

**HACK Studio | itzz_hitesh**

---

# 📜 License

This project is released under the **MIT License**.

Feel free to use, modify, and contribute while keeping proper credit.

---

## ⭐ Support the Project

If you enjoy using **Msg**, consider giving the repository a **⭐ Star** on GitHub. It helps support future updates and improvements.
```
