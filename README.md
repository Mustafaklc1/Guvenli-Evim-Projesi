# 🌍 Güvenli Evim - Deprem Farkındalık Simülasyonu

"Güvenli Evim", 10-12 yaş grubu çocuklara afet bilincini dijital ortamda "yaparak ve yaşayarak" (Game-Based Learning) aşılamayı hedefleyen 3 boyutlu bir eğitim simülasyonudur. Unity 6 oyun motoru ile geliştirilmiş olup, travma duyarlı (kan veya korkutucu sesler içermeyen) ve hata dostu bir pedagojik altyapıya sahiptir.

---

## 🎮 Oyun Ekranları ve Akış

Simülasyon, "İskele Yöntemi" (Scaffolding) baz alınarak aşama aşama inşa edilmiş 4 ana bölümden oluşmaktadır:

### 🏠 1. Başla Ekranı (Ana Menü)
Oyuncunun ismini girerek maceraya adım attığı giriş ekranıdır. Bu ekranda 4 temel menü bulunur:
* **Başla:** Simülasyonu doğrudan başlatır.
* **Bilgilendirme:** Projenin amacını, hedef kitlesini, "Öz-Belirleme (SDT)" ve "Akış Teorisi (Flow)" gibi pedagojik ve kuramsal altyapılarını detaylıca açıklar.
* **Ayarlar:** Oyun içi "Gündüz / Gece Modu" seçiminin yapıldığı ve tüm klavye/kamera kontrollerinin oyuncuya gösterildiği alandır.
* **Çıkış:** Oyunu kapatır.

### 🎒 2. Oyun Ekranı (Afet Öncesi - Çanta Hazırlama)
Sevimli rehber robotumuzun karşılamasıyla başlayan bu bölümde, deprem öncesi hazırlıklar işlenir. 
* **Görev:** Kısıtlı bir süre içinde, evdeki eşyalar arasından doğru olanları seçerek (fener vb.) 6 eşyalı deprem çantasını eksiksiz tamamlamak.
* **Dinamik Zorluk:** Görev esnasında elektriklerin kesilmesi gibi durumlar yaşanır; oyuncu karanlıkta yolunu bulmak için çantasına fener eklemek zorundadır.

### ⚠️ 3. Oyun 1 Ekranı (Afet Anı ve Tahliye)
Simülasyonun en kritik aşamasıdır. Deprem alarmı çaldığında oyuncunun doğru reaksiyonları göstermesi beklenir:
* **Çök-Kapan-Tutun:** Sarsıntı başladığında oyuncu, sağlam bir eşyanın (masa gibi) yanına giderek güvenli pozisyon almalıdır.
* **Tahliye Yolu:** Sarsıntı bittikten sonra ekranda beliren mavi ve yeşil yönlendirme çizgilerini takip ederek güvenli alana tahliye işlemi gerçekleştirilir. (Asansör kullanımı gibi ölümcül hatalara izin verilmez, oyuncu doğru rotaya yönlendirilir).

### 🏁 4. Bitiş Ekranı (Değerlendirme)
"Güvenli Bölgeye Ulaştınız!" mesajıyla oyuncuyu karşılayan sonuç ekranıdır. 
* Oyuncunun çanta hazırlama puanı, geçen süre ve genel başarı puanı listelenir.
* *“Deprem anında paniğe kapılmamak ve doğru tahliye rotasını izlemek hayat kurtarır.”* mesajıyla eğitim tamamlanır. Oyuncu buradan Ana Menüye dönebilir veya tekrar oynayabilir.

---

## ⌨️ Oyun Kontrolleri

Oyun kontrolleri FPS (Birinci Şahıs) kamerasına uygun olarak tasarlanmıştır:
* **[W, A, S, D]:** Karakteri Yönlendir
* **[Fare (Mouse)]:** Etrafa Bak / Kamerayı Çevir
* **[TAB Tuşu]:** Yapılacaklar (Görev) Listesini Aç / Kapat
* **[C Tuşu]:** Çök - Kapan - Tutun (Deprem Anı Koruması)
* **[E Tuşu]:** Etkileşim (Çantayı Aç / 112'yi Ara vb.)
* **[F Tuşu]:** Nesneyi Çantaya Ekle
* **[Y Tuşu]:** Çanta Tamamlandığında Sonraki Bölüme Geç

---

## 🚀 Nasıl Oynanır?

1. Sayfanın sağ tarafındaki **Releases** bölümünden oyunun son sürümünü `.zip` formatında bilgisayarınıza indirin.
2. İndirdiğiniz dosyayı sağ tıklayıp "Klasöre Çıkart" seçeneği ile açın.
3. Klasörün içindeki `.exe` (Güvenli Evim) dosyasına çift tıklayarak simülasyonu başlatın.

---

## 📺 Oynanış Videosu
Simülasyonun mekaniklerini, sahneler arası geçişleri ve oyun içi detayları uygulamalı olarak görmek için aşağıdaki bağlantıdan tanıtım/oynanış videomuzu izleyebilirsiniz:

▶️ **[Oynanış Videosunu İzlemek İçin Tıklayın](BURAYA_YOUTUBE_LINKINI_YAPISTIR)**
