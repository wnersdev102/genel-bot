<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=5865F2&height=200&section=header&text=Aşırı%20Gelişmiş%20Bot&fontSize=40&fontColor=ffffff&animation=fadeIn" width="100%"/>

# 🤖 Aşırı Gelişmiş Slash Altyapı

**wnersdev102 tarafından geliştirilen, 80+ komutlu tam donanımlı Discord bot altyapısı**

[![Discord](https://img.shields.io/discord/wnerscode?label=Discord%20Sunucu&logo=discord&logoColor=white&color=5865F2&style=for-the-badge)](https://discord.gg/wnerscode)
[![YouTube](https://img.shields.io/badge/YouTube-wnersdev-red?logo=youtube&style=for-the-badge)](https://www.youtube.com/@wnersdev)
[![Node.js](https://img.shields.io/badge/Node.js-18%2B-brightgreen?logo=node.js&style=for-the-badge)](https://nodejs.org)
[![License](https://img.shields.io/badge/Lisans-MIT-blue?style=for-the-badge)](LICENSE)

</div>

---

## 📋 İçindekiler

- [Hakkında](#-hakkında)
- [Gereksinimler](#-gereksinimler)
- [Kurulum](#-kurulum)
- [Özellikler](#-özellikler)
- [Komutlar](#-komutlar)
- [Yapılandırma](#-yapılandırma)
- [Destek](#-destek)

---

## 💡 Hakkında

Bu altyapı, Discord sunucunuzu **sıfırdan tam donanımlı** bir hale getirmek için tasarlanmıştır. Giriş/çıkış mesajlarından çekiliş sistemine, moderasyon araçlarından seviye sistemine kadar ihtiyacınız olan her şey tek bir pakette sunulmaktadır.

> ⚡ Hızlı kurulum, kolay yapılandırma, güçlü altyapı.

---

## 🛠️ Gereksinimler

Botu çalıştırabilmek için aşağıdakilerin kurulu olması gerekmektedir:

| Gereksinim | Minimum Sürüm | İndirme |
|------------|---------------|---------|
| Node.js | v18.0.0+ | [nodejs.org](https://nodejs.org) |
| npm | v8.0.0+ | Node.js ile gelir |
| Discord Bot Token | — | [Discord Developer Portal](https://discord.com/developers/applications) |

---

## 📦 Kurulum

### 1️⃣ Repoyu klonlayın
```bash
git clone https://github.com/wnersdev102/asiri-gelismis-genel-bot.git
cd asiri-gelismis-genel-bot
```

### 2️⃣ `ayarlar.json` dosyasını doldurun

[`ayarlar.json`](https://github.com/wnersdev102/asiri-gelismis-genel-bot/blob/main/ayarlar.json) dosyasını açın ve tüm alanları eksiksiz doldurun:
```json
{
  "token": "BOT_TOKEN_BURAYA",
  "prefix": "!",
  "clientId": "BOT_CLIENT_ID",
  "guildId": "SUNUCU_ID"
}
```

> ⚠️ **Uyarı:** Token bilginizi asla kimseyle paylaşmayın ve `.gitignore` dosyasına eklemeyi unutmayın!

### 3️⃣ Bağımlılıkları yükleyin
```bash
npm i
```

### 4️⃣ Botu başlatın
```bash
node wnersdev.js
```

✅ Konsolda `Bot aktif!` mesajını gördüyseniz kurulum tamamdır.

---

## ✨ Özellikler

### 🔔 Giriş / Çıkış Sistemi
Sunucuya yeni katılan veya ayrılan üyeler için özelleştirilebilir hoş geldin ve veda mesajları. Belirli bir kanala gönderilir, embed mesaj desteği mevcuttur.

### 🎭 Otomatik Rol Sistemi
Yeni üyeler sunucuya katıldığında otomatik olarak belirlenen roller atanır. Birden fazla rol tanımlanabilir.

### 🏷️ Otomatik Tag Sistemi
Üyelerin kullanıcı adlarına otomatik olarak sunucu etiketi (tag) ekler. Sunucu kimliğini ön plana çıkarmak için idealdir.

### 💬 Otomatik Cevap Sistemi
Belirli anahtar kelimelere karşılık botun otomatik yanıt vermesini sağlar. SSS kanallarında büyük kolaylık sunar.

### 📨 Davet Sistemi
Kim kaç kişiyi davet etti takip edilebilir. Davet sıralaması ve istatistikleri görüntülenebilir.

### 🛡️ Koruma Sistemleri
Anti-spam, anti-raid, kelime filtresi ve link engelleme gibi güvenlik önlemleri. Sunucunuzu kötü niyetli kullanıcılardan korur.

### 🎮 Eğlence Sistemi
Üyelerin eğlenceli zaman geçirebileceği çeşitli komutlar: trivia, zar, yazı-tura ve daha fazlası.

### ⭐ Seviye Sistemi
Mesaj attıkça XP kazanma, seviye atlama ve liderlik tablosu. Aktif üyeler ödüllendirilebilir.

### 🎫 Destek Sistemi
Ticket (destek talebi) oluşturma sistemi. Üyeler sorunlarını özel kanallar aracılığıyla iletebilir.

### 🎁 Çekiliş Sistemi
Kolayca çekiliş başlatın, süreyi ve kazanan sayısını belirleyin. Kazananlar otomatik seçilir.

### 👤 Kullanıcı Sistemleri
Profil kartı, avatar görüntüleme, bilgi sorgulama gibi kullanıcıya özel komutlar.

### 🔘 Buton Rol Sistemi
Üyeler mesajlardaki butonlara tıklayarak kendilerine rol alabilir veya verebilir. Modern ve kullanıcı dostu arayüz.

### 🟢 Durum Rol Sistemi
Kullanıcının Discord durumuna (çevrimiçi, meşgul, rahatsız etme) göre otomatik rol ataması.

### 📢 Bildirim Sistemleri
YouTube, Twitch veya özel olaylar için otomatik bildirim gönderme sistemi.

---

## ⚙️ Yapılandırma

Tüm ayarlar `ayarlar.json` dosyasından yönetilir. Detaylı açıklamalar için dosyanın içindeki yorumları inceleyebilirsiniz.

| Alan | Açıklama |
|------|----------|
| `token` | Discord bot tokenınız |
| `prefix` | Komut öneki (varsayılan: `!`) |
| `clientId` | Botunuzun uygulama ID'si |
| `guildId` | Slash komutlarının test edileceği sunucu ID'si |
| `welcomeChannel` | Hoş geldin mesajlarının gönderileceği kanal |
| `logChannel` | Moderasyon loglarının tutulacağı kanal |

---

## 🆘 Destek

Bir sorunla karşılaştıysanız:

1. Önce [`ayarlar.json`](https://github.com/wnersdev102/asiri-gelismis-genel-bot/blob/main/ayarlar.json) dosyasını doğru doldurduğunuzdan emin olun
2. Node.js sürümünüzün **v18+** olduğunu kontrol edin
3. Hâlâ sorun yaşıyorsanız **[Discord sunucumuza](https://discord.gg/wnerscode)** katılın

---

## 📺 YouTube

Kurulum rehberleri, yeni özellik tanıtımları ve güncellemeler için kanalımıza göz atın:

**👉 [youtube.com/@wnersdev](https://www.youtube.com/@wnersdev)**

---

<div align="center">

**wnersdev102 tarafından ❤️ ile geliştirildi**

<img src="https://capsule-render.vercel.app/api?type=waving&color=5865F2&height=100&section=footer" width="100%"/>

</div>
