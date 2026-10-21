# 🚀 Sᴏᴄɪᴀʟ Mᴇᴅɪᴀ Dᴏᴡɴʟᴏᴀᴅᴇʀ API 📥

**« ⚡ Fᴀsᴛ • Lɪɢʜᴛᴡᴇɪɢʜᴛ • Pᴏᴡᴇʀғᴜʟ • Vᴇʀᴄᴇʟ Rᴇᴀᴅʏ »**

A ᴘᴏᴡᴇʀғᴜʟ ᴀɴᴅ fᴀsᴛ Fʟᴀsᴋ-ʙᴀsᴇᴅ Sᴏᴄɪᴀʟ Mᴇᴅɪᴀ Dᴏᴡɴʟᴏᴀᴅᴇʀ API tᴏ eхᴛʀᴀᴄᴛ dɪʀeᴄᴛ mᴇᴅɪᴀ lɪɴᴋs fʀᴏᴍ vᴀʀɪᴏᴜs sᴏᴄɪᴀʟ mᴇᴅɪᴀ pʟᴀᴛfᴏʀᴍs. 🚀

!
━━━━━━━━━━━━━━━━━━━━━━━━

## ✨ Fᴇᴀᴛᴜʀᴇs

- 📸 **Iɴsᴛᴀɢʀᴀᴍ** — Rᴇeʟs • Pᴏsᴛs • Sᴛᴏʀɪés • Hɪɢʜʟɪɢʜᴛs • Pʀᴏfɪʟés
- 👥 **Fᴀᴄeʙᴏᴏᴋ** — HD • SD Vɪdᴇᴏ Lɪɴᴋs
- 👻 **Sɴᴀpᴄʜᴀᴛ** — Dɪʀeᴄᴛ Vɪdᴇᴏ • Iᴍᴀɢe
- 📌 **Pɪɴᴛeʀésᴛ** — Vɪdᴇᴏ • Hɪɢʜ-Résᴏʟᴜᴛɪᴏɴ Pʜᴏᴛᴏ
- ▶️ **YᴏᴜTᴜʙe** — Vɪdᴇᴏ Dᴏẃɴʟᴏᴀᴅ
- 🎵 **TɪᴋTᴏᴋ** — Nᴏ Wᴀᴛeʀᴍᴀʀᴋ • HD Vɪdᴇᴏ
- ⚡ **Fᴀsᴛ & Lɪɢʜᴛᴡéɪɢʜᴛ**
- ☁️ **Véʀcéʟ Réᴀdý**
- 🔗 **Sɪᴍpʟé REST API**

━━━━━━━━━━━━━━━━━━━━━━━━

## 📡 Aᴘɪ Éɴdᴘᴏɪɴᴛs

### 🏠 1. Rᴏᴏᴛ / Héᴀlᴛʜ Chéćk

> Géᴛ ᴀll ᴀvᴀɪlᴀbʟe éɴdpᴏɪɴᴛs ᴀɴd Dévélᴏpə́r Ínfᴏ́rᴍáᴛíᴏ́n.

```http
GET /


### 📘 2. Fᴀᴄᴇʙᴏᴏᴋ

```http
GET /facebook?video=URL
```

### 📸 3. Iɴsᴛᴀɢʀᴀᴍ

```http
GET /Instagram?video=URL
```

### 📌 4. Pɪɴᴛᴇʀᴇsᴛ

```http
GET /Pinterest?video=URL
GET /youtube?video=URL
```

### 👻 5. Sɴᴀᴘᴄʜᴀᴛ

```http
GET /snap?video=URL
```
🎵 6. Tiktok

GET /tiktok?video=URL


━━━━━━━━━━━━━━━━━━━━━━━━

## 📦 Rᴇsᴘᴏɴsᴇ Exᴀᴍᴘʟᴇ

{
  "Developer": "t.me/Hasan99809",
  "Endpoints": {
    "Facebook": "/facebook?video=URL",
    "Instagram": "/Instagram?video=URL",
    "Pinterest": "/Pinterest?video=URL",
    "Snapchat": "/snap?video=URL",
    "YouTube": "/youtube?video=URL",
    "TikTok": "/tiktok?video=URL"
  },
  "Main Channel": "@Hasan99809",
  "Owner": "@Hasan99809"
}


━━━━━━━━━━━━━━━━━━━━━━━━

## 📋 Eɴᴅᴘᴏɪɴᴛ Sᴜᴍᴍᴀʀʏ

| Endpoint | Method | Parameter | Description |
|----------|--------|-----------|-------------|
| `/` | `GET` | — | Health check & endpoint list |
| `/facebook` | `GET`, `POST` | `video` | Facebook video downloader |
| `/Instagram` | `GET`, `POST` | `video` | Instagram Reels / Post / Story / Profile |
| `/snap` | `GET`, `POST` | `video` | Snapchat video & image |
| `/Pinterest` | `GET`, `POST` | `video` | Pinterest video & photo |
| `/youtube` | `GET`, `POST` | `video` | YouTube video downloader |
| `/tiktok` | `GET`, `POST` | `video` | TikTok No-Watermark video downloader

━━━━━━━━━━━━━━━━━━━━━━━━

## 💻 Rᴜɴɴɪɴɢ Lᴏᴄᴀʟʟʏ

**1️⃣ Clone or download this project folder.**

**2️⃣ Install dependencies:**

```bash
pip install -r requirements.txt
# YouTube support uses yt-dlp
```

**3️⃣ Run the Flask server:**

```bash
python api.py
```

**4️⃣ Access the API locally:**

```
http://127.0.0.1:5150/
```

━━━━━━━━━━━━━━━━━━━━━━━━

## ☁️ Dᴇᴘʟᴏʏᴍᴇɴᴛ

- 🚀 **Vᴇʀᴄᴇʟ Rᴇᴀᴅʏ**
- ⚙️ **Fʟᴀsᴋ + Pʏᴛʜᴏɴ**
- 🔗 **REST API Sᴜᴘᴘᴏʀᴛ**

### 🔧 Option A — Vercel CLI

```bash
npm install -g vercel
vercel
```

### 🐙 Option B — GitHub + Vercel Dashboard

1. Upload this project to **GitHub**
2. Import on the [Vercel Dashboard](https://vercel.com/dashboard)
3. Click **Deploy** 🚀

━━━━━━━━━━━━━━━━━━━━━━━━

## ⚠️ Iᴍᴘᴏʀᴛᴀɴᴛ Nᴏᴛᴇs

- 📌 All endpoints accept the URL via the **`video`** parameter.
- 📌 Use **query string** or **form-data / x-www-form-urlencoded** for POST requests. JSON body is **not** supported.
- 📌 Flask routes are **case-sensitive** — `/Instagram` and `/instagram` are treated differently.

━━━━━━━━━━━━━━━━━━━━━━━━

## 👨‍💻 Dᴇᴠᴇʟᴏᴘᴇʀ Iɴғᴏ
👤 Nᴀᴍᴇ : HASAN
⚡ Bʀᴀɴᴅ : COPY 
💻 Rᴏʟᴇ : Fᴜʟʟ Sᴛᴀᴄᴋ Dᴇᴠᴇʟᴏᴘᴇʀ
🚀 Pʀᴏᴊᴇᴄᴛ : Sᴏᴄɪᴀʟ Mᴇᴅɪᴀ Dᴏᴡɴʟᴏᴀᴅᴇʀ Aᴘɪ
📡 Sᴜᴘᴘᴏʀᴛ : @Hasan99809

━━━━━━━━━━━━━━━━━━━━━━━━

## ⚡ HASAN Sᴏᴄɪᴀʟ Mᴇᴅɪᴀ Dᴏᴡɴʟᴏᴀᴅᴇʀ

**« 🔥 Fᴀsᴛ • Sᴍᴏᴏᴛʜ • Sɪᴍᴘʟᴇ • Pᴏᴡᴇʀғᴜʟ 🚀 »**

━━━━━━━━━━━━━━━━━━━━━━━━
🙂🙂 ##  padhai hogya to channel per jao https://t.me/Hasan99809
