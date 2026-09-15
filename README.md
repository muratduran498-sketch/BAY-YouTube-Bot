# BAY Bot Dağıtım Paketi - Hızlı Referans

## 🚀 Müşteride Kurulum (Adım Adım)

### 1. Paketleri Yükle (İlk Kez)
```
Kurulum.bat dosyasına çift tıkla → Enter → Bitene kadar bekle
```
(Python'un kurulu olduğundan emin ol: https://www.python.org/downloads/)

### 2. Uygulamayı Başlat
```
Uygulamayi_Baslat.bat dosyasına çift tıkla
```


### 3. Lisans Anahtarını Yapıştır
Kilit ekranında satıcıdan aldığın uzun metni yapıştır.

### 4. Aktifleştir
"✅ Aktifleştir" butonuna bas → ✅ Çalışır!

---

## 📞 Lisans Almak İçin
Lisans anahtarı için satıcıyla iletişime geçin.
Satıcı maili: sromuratduran@gmail.com
---

**Sürüm:** 1.0.0 | **GitHub:** muratduran498-sketch/BAY-YouTube-Bot

## 📁 Klasör Yapısı

```
BayYtBot/
├── Kurulum.bat .................. (Paket yükleme, ilk kez çalıştır)
├── Uygulamayi_Baslat.bat ........ (Her açılış için)
├── KULLANIM_REHBERI.md .......... (Detaylı rehber)
├── SATIŞ_VE_DAĞITIM.md .......... (Satıcı rehberi — müşteriye gitmez)
├── requirements.txt ............. (Python paketleri)
├── version.json ................. (Sürüm bilgisi — otomatik güncelleme)
│
├── gui_app.py ................... (Arayüz motor)
├── main.py ...................... (Video üretim motor)
├── license_manager.py ........... (Lisans doğrulama)
├── updater.py ................... (Otomatik güncelleme)
│
└── [diğer Python modülleri...]
    ├── config.py, accounts.py, api_settings.py
    ├── topic_researcher.py, script_writer.py
    ├── image_generator.py, tts_generator.py
    ├── video_assembler.py, youtube_uploader.py
    └── ...
```

---

## 🔑 Satıcı İşlemleri (Sende Kalır)

### Her Sürümde
1. `updater.py`: `APP_VERSION = "X.Y.Z"` yükselt
2. `BayYtBot` zip'le
3. GitHub releases'a yükle
4. `version.json` güncelle ve GitHub'a push'la

### Her Müşteri İçin
1. `Lisans_Uret.bat` çalıştır
2. Anahtar kopyala
3. ZIP + Anahtar gönder

---

## 🛠️ Dosyalar (Müşteriye ASLA Gönderme)

❌ `kod üretim ytbot/` klasörü
❌ `private_key.pem` (gizli)
❌ `license_generator.py`
❌ Eski sürüm zipleri

---

## 🔄 Güncelleme Akışı (Otomatik)

1. Müşteri uygulamayı açar
2. 5 saniye sonra GitHub'ı kontrol eder
3. Yeni sürüm varsa bildirim gelir
4. Müşteri "Güncelle" derse:
   - ZIP indirilir
   - Eski sürüm yedeklenir
   - Yeni sürüm kurulur
   - Lisans korunur ✅
   - Uygulama kapanır
5. Müşteri yeniden açar → çalışır

---

**Sürüm:** 1.0.0 | **Tarih:** 2026-09-15 | **GitHub:** muratduran498-sketch/BAY-YouTube-Bot
