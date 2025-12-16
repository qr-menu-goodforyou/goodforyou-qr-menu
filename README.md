# ☕ GOOD FOR YOU COFFEE SHOP - QR Dijital Menü

Bu depo, Good For You Coffee Shop için hazırlanan responsive (mobil uyumlu) QR kod dijital menü projesini barındırmaktadır. Proje, statik HTML, CSS ve resim dosyalarından oluşmakta olup, Netlify üzerinden sürekli dağıtım (Continuous Deployment) ile yayındadır.

---

## 🔗 CANLI BAĞLANTI (QR Kod Adresi)
https://qr-menu-goodforyou.vercel.app/menu.html

---

## 🚀 ÖZELLİKLER

* **Responsive Tasarım:** Tüm mobil cihazlarda (iOS/Android) sorunsuz ve hızlı görüntülenme.
* **Yapışkan Navigasyon:** Kategoriler arası geçiş için ekranın üstüne yapışan, kaydırılabilir menü sekmeleri.
* **Temiz Görünüm:** Koyu renk tema, okunaklı fontlar ve estetik ürün/fiyat hizalaması.
* **Statik ve Hızlı:** Dinamik bir altyapıya ihtiyaç duymadan hızlı yükleme.

---

## 🛠️ YÖNETİM VE GÜNCELLEME REHBERİ

Menüde bir fiyat, ürün veya açıklama değiştirmek istediğinizde izlemeniz gereken adımlar aşağıdadır:

### 1. Dosya Düzenleme

* **Menü İçeriği:** Ürün adları, açıklamaları ve fiyatları **`menu.html`** (veya `index.html`) dosyası içindeki ilgili `<span>` ve `<p>` etiketlerinde bulunur.
* **Tasarım/Stil:** Genel tasarım, mobil uyumluluk ve renk düzenleri **`style.css`** dosyasında bulunur.

### 2. GitHub Üzerinden Dağıtım (Deploy)

Değişiklikleri kaydettikten sonra, projenizin bulunduğu klasörde Terminal/Komut İstemi üzerinden aşağıdaki 3 komutu sırayla kullanmalısınız:

1.  **Değişiklikleri takibe alma:**
    ```bash
    git add . 
    ```
2.  **Değişiklikleri kaydetme (Commit):**
    ```bash
    git commit -m "Aciklayici bir mesaj yazin (Orn: 'Kahve fiyatlari guncellendi')"
    ```
3.  **Netlify'ın görebileceği şekilde GitHub'a yükleme (Push):**
    ```bash
    git push origin main
    ```
    *(Not: `main` dalı yerine `master` kullanıyorsanız, onu belirtin.)*

**Sonuç:** `git push` işlemi tamamlandığında, Netlify otomatik olarak yeni menünüzü mevcut web adresinde yayınlar. **QR kodunu yeniden bastırmaya gerek yoktur.**

---

## 📂 DEPO YAPISI

* `index.html`: (Menü veya Hoş Geldiniz Sayfası)
* `style.css`: Ana stil dosyası.
* `menu_arkaplan.jpg`: Arka plan görseli.
* `good_for_you_logo...png`: İkon ve logo dosyaları.
* `README.md`: Bu dosya.
