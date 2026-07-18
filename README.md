# 🦈 Sharka - 2D Sualtı Macera Oyunu

Sharka, derin okyanusta hazineleri toplamak ve düşmanları yenmek için mücadele eden cesur bir köpekbalığını (Sharka) kontrol ettiğiniz, sürükleyici ve eğlenceli bir 2D sualtı macera oyunudur!

### 🌐 Canlı Önizleme
Uygulamanın sunucu üzerinde aktif olarak çalışan canlı sürümüne aşağıdaki adresten ulaşabilirsiniz:
👉 **[https://sharka.halil.tech](https://sharka.halil.tech)**

---

## Oynanış

Tehlikeli sularda ilerleyin, çeşitli deniz yaratıklarıyla savaşın ve derinliklerin en güçlü canavarı (Boss) ile yüzleşin.

### Kontroller 🎮

*   **Yön Tuşları (Sağ/Sol)** veya **A/D**: Sağa ve sola yüzme
*   **SPACE (Boşluk)** veya **Yukarı Yön Tuşu**: Yukarı doğru zıplama/yüzme
*   **X**: Baloncuk fırlatma (Mermi)
*   **Y**: Kuyruk vurma saldırısı (Yakın Dövüş)

### Amaç 🎯

*   Sualtı dünyasındaki engelleri aşarak ilerleyin.
*   Puan kazanmak için altınları toplayın (Toplam 20 adet).
*   Zehirli baloncukları aktifleştirmek için zehir şişelerini toplayın.
*   Baloncuk fırlatarak ve kuyruk vurarak düşmanları alt edin.
*   Bölüm sonu canavarını (Boss) yenerek zafere ulaşın!

---

## Kurulum ve Çalıştırma 🚀

### Gereksinimler
*   Modern bir web tarayıcısı.
*   Yerel çalıştırma için bilgisayarınızda **Docker** ve **Docker Compose** kurulu olmalıdır.

### Yerel Çalıştırma (Docker)
1.  Bu klasörde terminali açın.
2.  Aşağıdaki komutu çalıştırarak uygulamayı başlatın:
    ```bash
    docker compose up -d
    ```
3.  Tarayıcınızdan şu adrese gidin:
    👉 **[http://localhost:8081](http://localhost:8081)**

---

## Teknolojiler 🛠️

*   **HTML5 Canvas**: Donanım ivmeli 2D çizim ve render işlemleri.
*   **Vanilla JavaScript (ES6+)**: Herhangi bir kütüphane veya framework kullanmadan tamamen saf JavaScript OOP mimarisi.
*   **GSAP**: Pürüzsüz animasyonlar ve geçiş efektleri için kullanılan animasyon kütüphanesi.
*   **Nginx (Docker)**: Uygulamanın sunulması için kullanılan hafif web sunucusu.