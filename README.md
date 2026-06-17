
<table>
<tr>
<td width="320">

<img src="images/spark.png" width="300">

</td>

<td valign="top">

# Spark Logger
### Every Event. Every Detail. Every Time.
A powerful, highly configurable Discord logging bot that captures and organizes server events with precision.

</td>
</tr>
</table>

---

## 📌 Overview

**Spark Logger** is a Discord bot built in Python that provides comprehensive server event logging with a flexible, multi-tier channel configuration system. Whether you want all logs in one place or deeply organized category- and event-level channels, Spark Logger adapts to your server's needs.

- **85+ events** captured across 8 major Discord activity categories
- **3-tier logging setup** — Default, Category, or Event-wise channels
- **Webhooks** — Push logs into channels through webhook integration
- **Per-event control** — disable any event you don't want logged
- **Built for scale** — runs on Amazon EC2 with managed PostgreSQL

---

## ✨ Features

### 🔧 Flexible Log Channel Configuration

Spark Logger's advanced logging system gives admins granular control over where logs appear:

| Mode | Description |
|------|-------------|
| **Default Channel** | All events across all categories logged into a single channel |
| **Category Channels** | Events grouped by category, each in its own dedicated channel |
| **Event-wise Channels** | Each individual event gets its own dedicated channel |

You can mix and match — set a default, override specific categories, or go all the way down to per-event channels.

---

### 📂 Log Categories & Events

Spark Logger captures events across **8 categories**:

---

#### 📢 Channel
> Channel and thread lifecycle, webhooks, and followed channels.

`Channel Create` `Channel Update` `Channel Delete` `Channel Permission`
`Thread Create` `Thread Update` `Thread Delete`
`Webhook Create` `Webhook Update` `Webhook Delete`
`Channel Follow` `Followed Channel Update` `Channel Unfollow`

---

#### 👥 Member
> Member joins, leaves, updates, bot additions, and role changes.

`Member Join` `Member Leave` `Member Update`
`Bot Add` `Bot Remove`
`Role Add` `Role Remove`

---

#### 💬 Message
> Message edits, deletions, reactions, pins, and polls.

`Message Delete` `Message Bulk Delete` `Message Edit` `Attachment Remove`
`Reaction Add` `Reaction Remove` `Reaction Emoji Clear` `Reaction All Clear`
`Message Pin` `Message Unpin`
`Poll Create` `Poll Delete` `Poll End` `Poll Vote Add` `Poll Vote Remove`

---

#### 🔨 Moderation
> Bans, kicks, timeouts, pruning, and AutoMod.

`Kick` `Ban` `Unban` `Timeout` `Timeout Remove` `Prune`
`Automod Create` `Automod Update` `Automod Delete` `Automod Action`

---

#### 🏠 Server
> Guild updates, emojis, stickers, soundboard, events, invites, and boosts.

`Server Update`
`Emoji Create` `Emoji Update` `Emoji Delete`
`Sticker Create` `Sticker Update` `Sticker Delete`
`Soundboard Create` `Soundboard Update` `Soundboard Delete`
`Event Create` `Event Update` `Event Delete` `Event Start` `Event End`
`Invite Create` `Invite Delete`
`Server Boost`

---

#### 🎭 Role
> Role creation, updates, deletions, and permission changes.

`Role Create` `Role Update` `Role Delete` `Role Permission`

---

#### 🔊 Voice
> Voice activity, streams, video, stage channels, and speaker invites.

`Voice Join` `Voice Leave` `Voice Switch` `Voice Move` `Voice Disconnect`
`Voice Mute` `Voice Unmute` `Voice Deafen` `Voice Undeafen`
`Stream Start` `Stream End`
`Video Start` `Video End`
`Stage Start` `Stage Update` `Stage End`
`Stage Speaker Invite` `Stage New Invite`

---

#### 🤖 Bot
> Bot-specific updates and configuration changes.

`Bot Updates` `Config Update`

---

### 🚫 Event Disabling

Don't want to log a specific event? Admins can disable any individual event from being logged — keeping your log channels clean and relevant.

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Python |
| Database | PostgreSQL (Amazon RDS Managed) |
| Hosting | Amazon EC2 |
| Language Support | English (more coming soon) |

---

## 🌐 Current Limitations

- 🇬🇧 English only — multilingual support coming in a future update
- 📤 Sends logs only — no interactive dashboard yet
- No channel/role/member exclusion filters (coming soon)

---

## 🔮 Roadmap

Spark Logger is actively being developed. Upcoming features include:

- [ ] **Exclusion Filters** — Exclude specific channels, roles, or members from being logged
- [ ] **Message Statistics** — Server-wide, channel-wise, and member-wise message analytics
- [ ] **Multi-language Support** — Localized log messages in multiple languages
- [ ] **More event types** — Continued expansion of the event map
- [ ] **Log search & export** — Query and export historical logs

---

## 📬 Support

For support, join our [Discord Server](https://discord.gg/7tUZuZbk7R)  
Spark Logger [Web Page](https://sparklogger.github.io/webpage/)

---

## ✉️ Invite

Invite Spark Logger by clicking here → <img src="images/spark.png" 
     alt="Spark" 
     style="width:20px; height:20px; vertical-align:middle; margin:0 2px;"> [Spark Logger](https://discord.com/oauth2/authorize?client_id=1461191281987551283)

---

## 💰 Donate

Support development by donating here → <img src="images/paypal.png"
     alt="Spark" 
     style="width:16px; height:16px; vertical-align:middle; margin:0 2px;"> [PayPal](https://www.paypal.com/paypalme/LogeshWaran777)

---

*Made with <img src="images/py.png" 
     alt="Spark" 
     style="width:16px; height:16px; vertical-align:middle; margin:0 2px;"> by the Spark Logger team*
