# 🌙 LunaDev Discord Bot

<div align="center">

![LunaDev Bot](https://img.shields.io/badge/Discord-Bot-7289da?style=for-the-badge&logo=discord&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-18+-green?style=for-the-badge&logo=node.js)
![License](https://img.shields.io/badge/License-ISC-yellow?style=for-the-badge)

**Advanced Discord Bot with Tickets, Giveaways, Moderation & More**

[🇹🇷 Türkçe](#tr-türkçe) | [🇺🇸 English](#en-english)

</div>

---

## 🇹🇷 Türkçe

### 📖 Açıklama

LunaDev, Discord sunucunuz için gelişmiş özellikler sunan kapsamlı bir bottur. Modern tasarım, güvenlik ve kullanıcı deneyimi odaklı olarak geliştirilmiştir.

### ✨ Özellikler

#### 🎫 **Gelişmiş Ticket Sistemi**
- **Kategorili Ticket Oluşturma** - Genel, Teknik, Faturalandırma, Şikayet
- **Buton Tabanlı Yönetim** - Kullanıcı ekleme/çıkarma, kapatma, üstlenme
- **Otomatik Arşivleme** - Kapatılan ticketlar arşiv kategorisine taşınır
- **Yeniden Açma** - Arşivlenmiş ticketlar tek butonla geri alınabilir
- **Transkript Sistemi** - Tüm konuşmalar otomatik kayıt edilir

#### 🎉 **Çekiliş Sistemi**
- **Canvas Tabanlı Tasarım** - Siyah-mavi elegant tema
- **Lokalize Süre Girişi** - Gün/Saat/Dakika ayrı ayrı
- **Canlı Güncelleme** - Katılımcı sayısı otomatik güncellenir
- **Çifte Katılım Koruması** - Aynı kişi 2 kez katılamaz
- **Otomatik Sonlandırma** - Belirtilen sürede otomatik biter

#### 👋 **Hoşgeldin Sistemi**
- **Canvas Hoşgeldin Kartları** - Kişiselleştirilmiş tasarım
- **Otomatik Rol Verme** - Yeni üyelere otomatik rol
- **Dil Algılama** - Discord locale'e göre otomatik dil
- **Üye Sayısı Takibi** - "Sen X. üyesin" mesajı

#### 🛡️ **Moderasyon Araçları**
- **`/sil`** - Toplu mesaj silme (1-100 arası)
- **`/kitle`** - Kanal yazma kilitleme
- **`/kilitaç`** - Kanal kilit açma
- **`/kisibilgi`** - Detaylı kullanıcı bilgileri (Canvas ile)

#### ⭐ **Geri Bildirim Sistemi**
- **Yıldızlı Değerlendirme** - 1-5 yıldız sistemi
- **Rol Tabanlı Erişim** - Sadece Customer rolü kullanabilir
- **Canvas Feedback Kartları** - Güzel görsel tasarım

#### 📢 **Duyuru Sistemi**
- **Toplu DM Gönderimi** - Tüm üyelere özel mesaj
- **Modal Tabanlı** - Başlık, mesaj, görsel desteği
- **İstatistik Takibi** - Başarılı/başarısız gönderim sayısı

#### 🌐 **Çoklu Dil Desteği**
- **Türkçe & İngilizce** - Tam lokalizasyon
- **Kullanıcı Tercihi** - `/language` komutu ile değiştirilebilir
- **Otomatik Algılama** - Discord locale'e göre

#### 🎨 **Canvas Entegrasyonu**
- **Hoşgeldin Kartları** - Kişiselleştirilmiş tasarım
- **Çekiliş Kartları** - Elegant siyah-mavi tema
- **Kullanıcı Bilgi Kartları** - Detaylı profil gösterimi
- **Yardım Menüsü** - Kategorili Canvas tasarımı

#### 💳 **Ödeme Sistemi**
- **`/ödeme`** - Tüm ödeme yöntemlerini göster
- **Güvenlik Uyarıları** - Dolandırıcılık koruması
- **Çoklu Platform** - Papara, İninal, Banka, PayPal, Kripto

### 🚀 Kurulum

#### 1. Gereksinimler
```bash
Node.js 18+
npm veya yarn
Discord Application (Bot Token)
```

#### 2. Projeyi İndirin
```bash
git clone https://github.com/your-username/lunadev-discord-bot.git
cd lunadev-discord-bot
```

#### 3. Bağımlılıkları Yükleyin
```bash
npm install
```

#### 4. Konfigürasyon
`.env` dosyası oluşturun:
```env
# Bot Bilgileri
BOT_TOKEN=your_bot_token_here
CLIENT_ID=your_client_id_here
GUILD_ID=your_guild_id_here

# Rol ID'leri
AUTO_ROLE_ID=your_auto_role_id
ADMIN_ROLE_ID=your_admin_role_id
MOD_ROLE_ID=your_mod_role_id
CUSTOMER_ROLE_ID=your_customer_role_id

# Kanal ID'leri
WELCOME_CHANNEL_ID=your_welcome_channel_id
TICKET_CATEGORY_ID=your_ticket_category_id
ARCHIVE_CATEGORY_ID=your_archive_category_id
TRANSCRIPT_CHANNEL_ID=your_transcript_channel_id
FEEDBACK_CHANNEL_ID=your_feedback_channel_id
LOG_CHANNEL_ID=your_log_channel_id

# Ödeme Bilgileri (İsteğe bağlı)
PAPARA_NUMBER=your_papara_number
ININAL_NUMBER=your_ininal_number
ZIRAAT_IBAN=your_bank_iban
PAYPAL_EMAIL=your_paypal_email
CRYPTO_WALLET=your_crypto_wallet
```

#### 5. Komutları Deploy Edin
```bash
npm run deploy
```

#### 6. Botu Başlatın
```bash
npm start          # Auto-restart ile
npm run start-direct  # Direkt başlatma
```

### 📋 Komutlar

#### 👥 **Kullanıcı Komutları**
- **`/help`** - Yardım menüsü (Canvas ile)
- **`/language`** - Dil değiştirme
- **`/ödeme`** - Ödeme yöntemleri
- **`/feedback`** - Geri bildirim bırakma (Customer rolü gerekli)

#### 🛡️ **Moderasyon Komutları**
- **`/sil [sayı] [kullanıcı]`** - Mesaj silme
- **`/kitle [kanal] [sebep]`** - Kanal kilitleme
- **`/kilitaç [kanal] [sebep]`** - Kanal kilit açma
- **`/kisibilgi [kullanıcı]`** - Kullanıcı bilgileri

#### 🎉 **Eğlence Komutları**
- **`/giveaway create`** - Çekiliş oluşturma

#### ⚙️ **Sistem Komutları**
- **`/ticket setup`** - Ticket sistemi kurma
- **`/announce`** - Toplu DM duyuru

### 🔧 Teknik Özellikler

#### 🏗️ **Mimari**
- **Discord.js v14** - En güncel Discord API
- **SQLite3** - Hafif ve hızlı veritabanı
- **Canvas** - Dinamik görsel oluşturma
- **Modüler Yapı** - Kolay bakım ve geliştirme

#### 🔒 **Güvenlik**
- **Environment Variables** - Güvenli konfigürasyon
- **Rol Tabanlı Erişim** - Yetki kontrolleri
- **Rate Limiting** - Spam koruması
- **Input Validation** - Güvenli veri girişi

#### 📊 **Logging**
- **Moderasyon Logları** - Tüm işlemler kayıt edilir
- **Kullanıcı Logları** - Üye aktiviteleri takibi
- **Hata Yönetimi** - Kapsamlı error handling
- **Auto-Restart** - Otomatik yeniden başlatma

### 👨‍💻 Geliştirici

**Coast** (leancoast)
- Discord: leancoast
- GitHub: [Your GitHub Profile]

### 📄 Lisans

Bu proje ISC lisansı altında lisanslanmıştır.

---

## 🇺🇸 English

### 📖 Description

LunaDev is a comprehensive Discord bot offering advanced features for your Discord server. Developed with a focus on modern design, security, and user experience.

### ✨ Features

#### 🎫 **Advanced Ticket System**
- **Categorized Ticket Creation** - General, Technical, Billing, Report
- **Button-Based Management** - Add/remove users, close, claim
- **Automatic Archiving** - Closed tickets moved to archive category
- **Reopen Functionality** - Archived tickets can be restored with one button
- **Transcript System** - All conversations automatically recorded

#### 🎉 **Giveaway System**
- **Canvas-Based Design** - Elegant black-blue theme
- **Localized Time Input** - Separate Day/Hour/Minute inputs
- **Live Updates** - Participant count updates automatically
- **Duplicate Entry Protection** - Same person can't enter twice
- **Automatic Ending** - Ends automatically at specified time

#### 👋 **Welcome System**
- **Canvas Welcome Cards** - Personalized design
- **Auto Role Assignment** - Automatic role for new members
- **Language Detection** - Automatic language based on Discord locale
- **Member Count Tracking** - "You are member #X" message

#### 🛡️ **Moderation Tools**
- **`/sil`** - Bulk message deletion (1-100 range)
- **`/kitle`** - Channel write lock
- **`/kilitaç`** - Channel unlock
- **`/kisibilgi`** - Detailed user information (with Canvas)

#### ⭐ **Feedback System**
- **Star Rating** - 1-5 star system
- **Role-Based Access** - Only Customer role can use
- **Canvas Feedback Cards** - Beautiful visual design

#### 📢 **Announcement System**
- **Bulk DM Sending** - Private message to all members
- **Modal-Based** - Title, message, image support
- **Statistics Tracking** - Success/failure count

#### 🌐 **Multi-Language Support**
- **Turkish & English** - Full localization
- **User Preference** - Changeable with `/language` command
- **Auto Detection** - Based on Discord locale

#### 🎨 **Canvas Integration**
- **Welcome Cards** - Personalized design
- **Giveaway Cards** - Elegant black-blue theme
- **User Info Cards** - Detailed profile display
- **Help Menu** - Categorized Canvas design

#### 💳 **Payment System**
- **`/ödeme`** - Show all payment methods
- **Security Warnings** - Fraud protection
- **Multi-Platform** - Papara, İninal, Bank, PayPal, Crypto

### 🚀 Installation

#### 1. Requirements
```bash
Node.js 18+
npm or yarn
Discord Application (Bot Token)
```

#### 2. Clone Project
```bash
git clone https://github.com/your-username/lunadev-discord-bot.git
cd lunadev-discord-bot
```

#### 3. Install Dependencies
```bash
npm install
```

#### 4. Configuration
Create `.env` file:
```env
# Bot Credentials
BOT_TOKEN=your_bot_token_here
CLIENT_ID=your_client_id_here
GUILD_ID=your_guild_id_here

# Role IDs
AUTO_ROLE_ID=your_auto_role_id
ADMIN_ROLE_ID=your_admin_role_id
MOD_ROLE_ID=your_mod_role_id
CUSTOMER_ROLE_ID=your_customer_role_id

# Channel IDs
WELCOME_CHANNEL_ID=your_welcome_channel_id
TICKET_CATEGORY_ID=your_ticket_category_id
ARCHIVE_CATEGORY_ID=your_archive_category_id
TRANSCRIPT_CHANNEL_ID=your_transcript_channel_id
FEEDBACK_CHANNEL_ID=your_feedback_channel_id
LOG_CHANNEL_ID=your_log_channel_id

# Payment Information (Optional)
PAPARA_NUMBER=your_papara_number
ININAL_NUMBER=your_ininal_number
ZIRAAT_IBAN=your_bank_iban
PAYPAL_EMAIL=your_paypal_email
CRYPTO_WALLET=your_crypto_wallet
```

#### 5. Deploy Commands
```bash
npm run deploy
```

#### 6. Start Bot
```bash
npm start              # With auto-restart
npm run start-direct   # Direct start
```

### 📋 Commands

#### 👥 **User Commands**
- **`/help`** - Help menu (with Canvas)
- **`/language`** - Change language
- **`/ödeme`** - Payment methods
- **`/feedback`** - Leave feedback (Customer role required)

#### 🛡️ **Moderation Commands**
- **`/sil [count] [user]`** - Delete messages
- **`/kitle [channel] [reason]`** - Lock channel
- **`/kilitaç [channel] [reason]`** - Unlock channel
- **`/kisibilgi [user]`** - User information

#### 🎉 **Fun Commands**
- **`/giveaway create`** - Create giveaway

#### ⚙️ **System Commands**
- **`/ticket setup`** - Setup ticket system
- **`/announce`** - Bulk DM announcement

### 🔧 Technical Features

#### 🏗️ **Architecture**
- **Discord.js v14** - Latest Discord API
- **SQLite3** - Lightweight and fast database
- **Canvas** - Dynamic image generation
- **Modular Structure** - Easy maintenance and development

#### 🔒 **Security**
- **Environment Variables** - Secure configuration
- **Role-Based Access** - Permission controls
- **Rate Limiting** - Spam protection
- **Input Validation** - Safe data input

#### 📊 **Logging**
- **Moderation Logs** - All actions recorded
- **User Logs** - Member activity tracking
- **Error Handling** - Comprehensive error management
- **Auto-Restart** - Automatic restart on crash

### 🛠️ Setup Guide

#### Discord Bot Setup
1. Go to [Discord Developer Portal](https://discord.com/developers/applications)
2. Create new application
3. Go to "Bot" section
4. Create bot and copy token
5. Enable all Privileged Gateway Intents
6. Go to "OAuth2" → "URL Generator"
7. Select "bot" and "applications.commands"
8. Select required permissions
9. Invite bot to your server

#### Server Setup
1. Create required channels and categories
2. Create required roles
3. Copy IDs to `.env` file
4. Run `npm run setup` for guided setup
5. Deploy commands with `npm run deploy`
6. Start bot with `npm start`

### 📊 Database Schema

#### Tables
- **`user_settings`** - User language preferences
- **`tickets`** - Ticket information and status
- **`feedback`** - User feedback and ratings
- **`giveaways`** - Giveaway data and participants
- **`server_settings`** - Server-specific configurations

### 🎨 Canvas Features

#### Welcome Cards
- **Grid Background** - Elegant pattern
- **Blue Gradient Text** - Modern typography
- **User Avatar** - Circular with glow effect
- **Member Count** - Dynamic member tracking
- **Localized Content** - Language-specific text

#### Giveaway Cards
- **Black-Blue Theme** - Professional design
- **Info Cards** - Participants, Time, Host
- **Real-time Updates** - Live participant count
- **Clean Typography** - No emoji clutter

### 🔄 Auto-Restart System

The bot includes a process manager (`start.js`) that automatically restarts the bot if it crashes:

- **Max Restarts**: 10 attempts
- **Restart Delay**: 5 seconds
- **Graceful Shutdown**: Ctrl+C handling
- **Stability Reset**: Counter resets after 5 minutes

### 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

### 📞 Support

For support or questions:
- **Discord**: leancoast
- **GitHub Issues**: [Create an issue](https://github.com/your-username/lunadev-discord-bot/issues)

### 👨‍💻 Developer

**Coast** (leancoast)
- Discord: leancoast
- GitHub: [Your GitHub Profile]

### 🙏 Acknowledgments

- Discord.js community for the excellent library
- Canvas contributors for image generation capabilities
- SQLite team for the reliable database engine

### 📄 License

This project is licensed under the ISC License.

---

<div align="center">

**Made with ❤️ by Coast**

[![Discord](https://img.shields.io/badge/Discord-leancoast-7289da?style=flat&logo=discord&logoColor=white)](https://discord.com)
[![GitHub](https://img.shields.io/badge/GitHub-Coast-black?style=flat&logo=github&logoColor=white)](https://github.com/your-username)

</div>
