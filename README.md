# 🎙️ Kamoliddin Ashurov — Speaker & Tech Innovator


💬 **Bog'lanish:** Telegram: [@ilevel_kamoliddin](https://t.me/ilevel_kamoliddin)


---

## 🎙️ RubaiSTT — O'zbekcha Ovozli Yozuv Ilovasi

### Nima bu?

**RubaiSTT Dictation** — macOS uchun o'zbek tilidagi nutqni matnga aylantiruvchi ilova.  
Istalgan ilovada (Telegram, brauzer, hujjat, xabar) **⌃⌥D** tugmasi bosilganda — gapiring, matn avtomatik yoziladi.

### ✨ Xususiyatlari

| Xususiyat | Tavsif |
|-----------|--------|
| 🌐 Tizim bo'ylab | Istalgan ilovada ishlaydi |
| 🇺🇿 O'zbek tiliga maxsus | `rubaiSTT v2 medium` modeli, lotin alifbosi |
| ⚡ Metal tezlashtirish | Apple Silicon GPU'da tez ishlaydi |
| 🔌 To'liq oflayn | Internet kerak emas |
| 🪶 Yengil | 3 daqiqa ishlatilmasa RAM'dan bo'shaydi |

### 🤖 Qaysi AI ishlatiladi?

- **Model:** [`rubaiSTT v2 medium`](https://huggingface.co/islomov/rubaistt_v2_medium) — Sardor Islomov tomonidan yaratilgan
- **Arxitektura:** OpenAI Whisper asosida, faqat o'zbek tili uchun maxsus o'qitilgan
- **Engine:** [whisper.cpp](https://github.com/ggml-org/whisper.cpp) + Apple Metal
- **Narx:** Bepul, hech qanday API to'lovi yo'q

### 📋 Talablar

- macOS 13+ (Apple Silicon — M1/M2/M3/M4/M5)
- [Homebrew](https://brew.sh)
- ~1 GB disk maydoni

### 🚀 O'rnatish

```bash
git clone https://github.com/MuhammadMirrr/uzbek-dictation.git
cd uzbek-dictation
./setup.sh
```

### 🎯 Ishlatish

1. Istalgan joyda kursorni yozish maydoniga qo'ying
2. **⌃⌥D** bosing → 🔴 gapiring → **⌃⌥D** yana bosing
3. Matn o'sha joyga avtomatik yoziladi

### ⚙️ Oxirgi sozlama

```
System Settings → Privacy & Security → Accessibility
→ "RubaiSTT Dictation" ni qo'shing va yoqing ✅
```

---

## 🙏 Minnatdorchilik

- [rubaiSTT](https://huggingface.co/islomov/rubaistt_v2_medium) — Sardor Islomov (o'zbek STT modeli)
- [whisper.cpp](https://github.com/ggml-org/whisper.cpp) — Georgi Gerganov
- [uzbek-dictation](https://github.com/kamolbeek/speaker) — Kamoliddin Ashurov (kamolbeek)

---

*© 2026 Kamoliddin Ashurov — Barcha huquqlar himoyalangan*
