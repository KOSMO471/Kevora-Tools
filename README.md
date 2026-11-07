# ⬢ ToolHive

**ToolHive**, tamamen tarayıcıda çalışan (*client-side*), sunucu gerektirmeyen ve geliştiriciler, tasarımcılar ile dijital işlerle uğraşan herkes için tasarlanmış ücretsiz bir çevrim içi araç setidir.

👉 **Canlı Önizleme:** https://kosmo471.github.io/Kevora-Tools/

---

## ✨ Özellikler

### 🔳 Üreticiler
* **QR Kod Yapıcı:** Metin veya URL'lerden anlık QR kod üretimi ve PNG olarak indirme.
* **Barkod Yapıcı:** JsBarcode ile CODE128, EAN, UPC, CODE39 ve daha birçok formatta barkod üretimi.
* **UUID / GUID Oluşturucu:** Kriptografik olarak güvenli v4 UUID üretimi (özelleştirilebilir büyük/küçük harf, tire ve süslü parantez seçenekleriyle).

### 🧮 Hesaplama ve Matematik
* **Hesap Makinesi:** Standart işlemlerin yanı sıra trigonometrik fonksiyonlar (`sin`, `cos`, `tan`), logaritma, üs ve karekök desteği.
* **Yüzde Hesaplayıcı:** 4 farklı senaryoya göre anlık yüzde hesaplama.
* **Birim Dönüştürücü:** Uzunluk, ağırlık, sıcaklık, alan, hacim, hız, zaman ve veri birimleri arasında dönüşüm.

### 🔁 Dönüştürme Araçları
* **Base64 / URL Kodlayıcı & Çözücü:** UTF-8 destekli Base64 ve URL encoding işlemleri.
* **Renk Paleti / Kod Çevirici:** HEX, RGB ve HSL arasında anlık dönüşüm + ton paleti oluşturucu.
* **Dönüştürücü Sistemler:** Metinleri Binary, Oktal, Hexadecimal, Base32/58/64, Morse alfabesi, URL, HTML Entities, Unicode Escape ve Leet Speak formatlarına çevirme.

### 🔍 Analiz ve Şifreleme
* **JSON Biçimlendirici & Doğrulayıcı:** JSON verilerini biçimlendirme, küçültme ve hata denetimi.
* **Kontrast Kontrolcü:** WCAG 2.1 standartlarına göre erişilebilirlik kontrast oranı hesaplayıcı.
* **Kriptografi & Klasik Şifreler:** ROT13, Atbash, Vigenère, Bacon, Rail Fence, Sütunlu Yer Değiştirme, Playfair ve Affine şifreleme/çözme algoritmaları.

---

## 🛠️ Kullanılan Teknolojiler

Proje tamamen saf web teknolojileriyle geliştirilmiştir ve dışarıdan ağır bir backend bağımlılığı yoktur:
* **HTML5 & CSS3** (Modern Flexbox/Grid mimarisi, CSS değişkenleri)
* **Vanilla JavaScript (ES6+)**
* **QRCode.js** (QR kod üretimi için)
* **JsBarcode** (Barkod üretimi için)

---

## 🚀 Yerel Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak son derece basittir; herhangi bir sunucu kurmanıza gerek yoktur:

1. Bu depoyu klonlayın veya ZIP olarak indirin:
   ```bash
   git clone [https://github.com/KOSMO471/ToolHive.git](https://github.com/KOSMO471/ToolHive.git)
