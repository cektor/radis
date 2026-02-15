# 📻 Radyo Amatörü Dijital ID Sorgulama
### R.A.D.I.S.

**[English](README.md) | [Türkçe](#türkçe)**

<div align="center">

<img src="radioid.png" alt="Uygulama Logosu" width="150"/>

![Versiyon](https://img.shields.io/badge/versiyon-1.0.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Android-green.svg)
![Lisans](https://img.shields.io/badge/lisans-MIT-orange.svg)
![API](https://img.shields.io/badge/API-24%2B-brightgreen.svg)

**Radyo Amatörleri için DMR, NXDN, Röle ID ve APRS Verilerini Sorgulama Aracı**

**🆓 %100 Ücretsiz & Reklamsız Sonsuza Kadar**

[İndir](#indir) • [Özellikler](#özellikler) • [Ekran Görüntüleri](#ekran-görüntüleri) • [Gizlilik](#gizlilik) • [Destek](#destek)

</div>

---

## 🌟 Neden Bu Uygulamayı Seçmelisiniz?

Dijital ID'leri ve APRS verilerini **hızlı, güvenilir ve gizlilik odaklı** bir şekilde sorgulamak isteyen bir radyo amatörü müsünüz? Doğru yerdesiniz! Uygulamamız, ham radio topluluğu için özel olarak tasarlanmış ve sizin için en önemli özellikleri içeriyor.

### ✨ Temel Özellikler

- 🚀 **Yıldırım Hızı** - DMR, NXDN ve Röle ID'lerini saniyeler içinde sorgulayın
- 📡 **APRS Entegrasyonu** - QTH Locator hesaplamalı gerçek zamanlı APRS istasyon takibi
- 🔒 **Gizlilik Öncelikli** - Veri toplama yok, izleme yok, reklam yok
- 📴 **Çevrimdışı Mod** - İnternet olmadan son aramalarınıza erişin
- 🌙 **Karanlık Tema** - Gece operasyonları için güzel karanlık öncelikli tasarım
- 🆓 **%100 Ücretsiz** - Abonelik yok, uygulama içi satın alma yok

---

## 🎯 Özellikler

### 📊 Dijital ID Arama

Birden fazla ağda radyo amatörü bilgilerini sorgulayın:

#### DMR ID Arama
- Çağrı işareti veya DMR ID ile arama
- Operatör adı, şehir, ülke görüntüleme
- Son konuşma grubu aktivitesini gösterme
- Tek dokunuşla ID'yi panoya kopyalama

#### NXDN ID Arama
- Tam NXDN veritabanı erişimi
- Anında çağrı işareti arama
- Detaylı operatör bilgileri

#### Röle Veritabanı
- ID veya çağrı işareti ile röle arama
- Frekans, offset ve tonları görüntüleme
- Sorumlu operatörleri bulma
- Konum bilgileri (şehir, ülke)

### 🗺️ APRS Özellikleri

Gelişmiş APRS istasyon takibi:

- **Gerçek Zamanlı Konum** - En son istasyon koordinatları
- **QTH Locator** - Otomatik Maidenhead grid hesaplama
- **APRS PassCode** - Herhangi bir çağrı işareti için passcode üretme
- **Harita Entegrasyonu** - İstasyon konumunu APRS.fi'de açma
- **SSID Desteği** - -N, -1, -2, vb. otomatik algılama
- **İstasyon Bilgisi** - Yorum, sembol ve son görülme verileri

### 🔄 Akıllı Özellikler

#### Çevrimdışı Mod
- DMR/NXDN/Röle sorguları için **24 saatlik önbellek**
- APRS verileri için **1 saatlik önbellek** (daha dinamik)
- Çevrimiçi olduğunda otomatik senkronizasyon
- Görsel çevrimdışı göstergesi

#### Paylaşım & Dışa Aktarma
- **Sonuçları Paylaş** - WhatsApp, Telegram, SMS, E-posta ile gönder
- **QR Kod Oluşturma** - Herhangi bir sonuç için QR kod oluştur
- **UTF-8 Desteği** - Mükemmel Türkçe karakter desteği
- **Panoya Kopyala** - ID'ler ve passcode'lar için hızlı kopyalama

#### Kullanıcı Deneyimi
- **Büyük Harf Girişi** - Otomatik çağrı işareti formatlama
- **Boş Alan Doğrulama** - Yardımcı hata mesajları
- **Hızlı Navigasyon** - Alt sekme navigasyonu
- **Temiz Arayüz** - Minimal, dikkat dağıtmayan tasarım

---

## 📱 Ekran Görüntüleri

### Ana Ekranlar

| ID Arama | APRS Sorgu | Sonuçlar |
|----------|------------|----------|
| ![ID Arama](screenshots/id_search.png) | ![APRS](screenshots/aprs.png) | ![Sonuçlar](screenshots/results.png) |

### Özellikler

| Çevrimdışı Mod | QR Kod | Paylaş |
|----------------|--------|--------|
| ![Çevrimdışı](screenshots/offline.png) | ![QR](screenshots/qr.png) | ![Paylaş](screenshots/share.png) |

---

## 🚀 Başlangıç

### Gereksinimler

- Android 7.0 (API 24) veya üzeri
- İnternet bağlantısı (sorgular için)
- ~10 MB depolama alanı

### Kurulum

#### Seçenek 1: Google Play Store (Önerilen)
```
Yakında!
```

#### Seçenek 2: Doğrudan APK İndirme
1. [Releases](https://github.com/yourusername/radio-amateur-id-query/releases) sayfasından en son APK'yı indirin
2. Android ayarlarında "Bilinmeyen Kaynaklardan Yükleme"yi etkinleştirin
3. APK'yı yükleyin
4. Açın ve sorgulamaya başlayın!

#### Seçenek 3: Kaynaktan Derleme
```bash
# Depoyu klonlayın
git clone https://github.com/yourusername/radio-amateur-id-query.git

# Android Studio'da açın
cd radio-amateur-id-query

# Derleyin ve çalıştırın
./gradlew assembleDebug
```

---

## 🔧 Teknik Detaylar

### Kullanılan Teknolojiler

- **Kotlin** - Modern Android geliştirme
- **Jetpack Compose** - Bildirimsel UI framework
- **Retrofit** - Tip güvenli HTTP istemcisi
- **Coroutines** - Asenkron programlama
- **ViewModel** - Yaşam döngüsü farkında veri yönetimi
- **SharedPreferences** - Yerel veri önbellekleme
- **ZXing** - QR kod oluşturma

### Mimari

- **MVVM Pattern** - Temiz endişe ayrımı
- **Repository Pattern** - Veri soyutlama katmanı
- **Offline-First** - Önbellek öncelikli strateji
- **Material Design** - Modern UI/UX prensipleri

### Veri Kaynakları

#### RadioID.net API
- **Amaç:** DMR, NXDN ve Röle veritabanı
- **Kapsam:** Dünya çapında radyo amatörü veritabanı
- **Güncelleme Sıklığı:** Gerçek zamanlı
- **Veri Türü:** Halka açık bilgi

#### APRS.fi API
- **Amaç:** APRS istasyon takibi
- **Kapsam:** Küresel APRS-IS ağı
- **Güncelleme Sıklığı:** Gerçek zamanlı
- **API Anahtarı:** Salt okunur genel erişim

---

## 🔒 Gizlilik & Güvenlik

### Taahhüdümüz

- ✅ **Veri Toplama Yok** - Hiçbir kullanıcı verisi toplamıyoruz
- ✅ **İzleme Yok** - Analitik veya izleme hizmeti yok
- ✅ **Reklam Yok** - Tamamen reklamsız deneyim, sonsuza kadar
- ✅ **Hesap Yok** - Kayıt gerekmiyor
- ✅ **%100 Ücretsiz** - Abonelik yok, uygulama içi satın alma yok, gizli maliyet yok
- ✅ **Sadece Yerel Depolama** - Veriler cihazınızda önbelleğe alınır
- ✅ **Sadece HTTPS** - Güvenli API iletişimi
- ✅ **Açık Kaynak** - Şeffaf kod tabanı

### İzinler

Uygulama sadece **İKİ** izin gerektirir:

- **İNTERNET** - RadioID.net ve APRS.fi API'lerini sorgulamak için
- **ACCESS_NETWORK_STATE** - Ağ bağlantısını algılamak ve çevrimiçi/çevrimdışı durumu göstermek için

**Başka izin gerekmiyor!** Konum, kamera, kişiler veya depolama erişimi yok.

### Veri İşleme

- **Arama Sorguları:** Doğrudan üçüncü taraf API'lere gönderilir (RadioID.net, APRS.fi)
- **Önbellek Depolama:** Cihazınızda yerel olarak saklanır (Android OS tarafından şifrelenir)
- **Önbellek Süresi:** 24 saat (ID'ler) / 1 saat (APRS)
- **Kullanıcı Kontrolü:** Uygulamayı kaldırarak önbelleği temizleyin

Tam [Gizlilik Politikamızı](privacy_policy.md) okuyun

### Yasal Bildirim & Veri Kaynakları

**Önemli Bilgi:**

Bu uygulamada görüntülenen tüm kullanıcı ve radyo amatörü bilgileri, halka açık veritabanlarından yasal olarak alınmaktadır:

- **RadioID.net** - Halka açık DMR, NXDN ve Röle veritabanı
- **APRS.fi** - Halka açık APRS ağ verileri

Bu uygulama yalnızca bir sorgulama arayüzü olarak çalışır ve sunucularımızda hiçbir kullanıcı verisi SAKLAMAZ, TOPLAMAZ veya MUHAFAZA ETMEZ. Tüm bilgiler:

- ✅ Resmi radyo amatörü veritabanları üzerinden halka açıktır
- ✅ Üçüncü taraf API'lerden gerçek zamanlı olarak alınır
- ✅ Yalnızca cihazınızda geçici olarak önbelleğe alınır
- ✅ Radyo amatörlüğü yönetmelikleri kapsamında yasal olarak erişilebilirdir

**Veri Silme Talepleri:**

Bilgilerinizi kaldırmak veya değiştirmek isterseniz:
- DMR/NXDN/Röle verileri için doğrudan **RadioID.net** ile iletişime geçin
- APRS verileri için doğrudan **APRS.fi** ile iletişime geçin
- Hiçbir veri saklamadığımız için silme taleplerini işleme alamayız

**Kullanım Koşulları:**

Bu uygulamayı kullanarak, aşağıdakileri kabul etmiş sayılırsınız:
1. Tüm veriler halka açık radyo amatörü veritabanlarından alınmaktadır
2. Uygulama, harici sunucularda kişisel veri saklamaz
3. Veri silme talepleri orijinal veri kaynaklarına yönlendirilmelidir
4. Uygulama, radyo amatörlüğü yönetmeliklerine ve veri koruma yasalarına uygundur

---

## 🌍 Desteklenen Diller

- 🇬🇧 İngilizce (English)
- 🇹🇷 Türkçe

---

## 📖 Nasıl Kullanılır

### Dijital ID Arama

1. Uygulamayı açın (ID Arama ekranında başlar)
2. Bir çağrı işareti (örn. `TB1TFO`) veya ID numarası (örn. `2861059`) girin
3. "Sorgula" butonuna dokunun
4. DMR, NXDN ve Röle veritabanları için sonuçları görüntüleyin
5. Herhangi bir ID'nin yanındaki kopyala simgesine dokunarak kopyalayın

### APRS Verisi Sorgulama

1. "APRS Sorgula" sekmesine gidin
2. Bir çağrı işareti girin (örn. `TB1TFO`)
3. "APRS Sorgula" butonuna dokunun
4. İstasyon konumu, QTH Locator ve APRS PassCode'u görüntüleyin
5. APRS.fi'de açmak için "Haritada Görüntüle"ye dokunun

### Sonuçları Paylaşma

1. Sonuçları aldıktan sonra kartın altına kaydırın
2. Herhangi bir uygulama ile paylaşmak için "Paylaş"a dokunun
3. Veya QR kod oluşturmak için "QR Kod"a dokunun
4. Radyo amatörü arkadaşlarınızla paylaşın!

### Çevrimdışı Erişim

1. Çevrimiçiyken herhangi bir çağrı işareti veya ID sorgulayın
2. Sonuçlar otomatik olarak önbelleğe alınır
3. Çevrimdışıyken aynı çağrı işaretini arayın
4. Çevrimdışı göstergesi ile önbelleğe alınmış sonuçları görün
5. Tekrar çevrimiçi olduğunuzda veriler otomatik olarak yenilenir

---

## 🤝 Katkıda Bulunma

Radyo amatörü topluluğundan katkıları memnuniyetle karşılıyoruz!

### Nasıl Katkıda Bulunulur

1. Depoyu fork edin
2. Bir özellik dalı oluşturun (`git checkout -b feature/HarikaOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Harika özellik eklendi'`)
4. Dalı push edin (`git push origin feature/HarikaOzellik`)
5. Bir Pull Request açın

### Geliştirme Kurulumu

```bash
# Ön Gereksinimler
- Android Studio Arctic Fox veya üzeri
- JDK 11 veya üzeri
- Android SDK 35

# Klonlama ve kurulum
git clone https://github.com/yourusername/radio-amateur-id-query.git
cd radio-amateur-id-query

# Android Studio'da açın ve Gradle'ı senkronize edin
```

### Kodlama Kuralları

- Kotlin kodlama kurallarını takip edin
- UI için Jetpack Compose kullanın
- Anlamlı commit mesajları yazın
- Karmaşık mantık için yorumlar ekleyin
- Birden fazla Android sürümünde test edin

---

## 🐛 Hata Raporları & Özellik İstekleri

Bir hata buldunuz veya özellik fikriniz mi var? Sizden haber almak isteriz!

### Hata Bildirme

Lütfen şunları ekleyin:
- Android sürümü
- Cihaz modeli
- Yeniden üretme adımları
- Beklenen ve gerçek davranış
- Ekran görüntüleri (varsa)

### Özellik İstekleri

Bize söyleyin:
- Hangi özelliği istediğinizi
- Neden yararlı olacağını
- Nasıl çalışması gerektiğini

[Bir Issue Açın](https://github.com/yourusername/radio-amateur-id-query/issues)

---

## 📞 Destek

### Yardım Alın

- 📧 **E-posta:** info@algyazilim.com
- 🌐 **Web Sitesi:** https://algyazilim.com
- 💬 **Issues:** [GitHub Issues](https://github.com/yourusername/radio-amateur-id-query/issues)

### SSS

**S: Bu uygulama ücretsiz mi?**  
C: Evet! Reklam veya uygulama içi satın alma olmadan %100 ücretsiz.

**S: Hesap oluşturmam gerekiyor mu?**  
C: Hayır! Uygulama herhangi bir kayıt olmadan çalışır.

**S: Çevrimdışı çalışır mı?**  
C: Evet! Son aramalar çevrimdışı erişim için önbelleğe alınır.

**S: Hangi veritabanlarını arar?**  
C: RadioID.net (DMR, NXDN, Röleler) ve APRS.fi (APRS istasyonları).

**S: Verilerim güvende mi?**  
C: Kesinlikle! Hiçbir kullanıcı verisi toplamıyoruz. Her şey cihazınızda yerel olarak saklanır.

**S: Türkiye dışında kullanabilir miyim?**  
C: Evet! Tüm radyo amatörleri için dünya çapında çalışır.

---

## 👨💻 Geliştirici

**ALG Yazılım & Elektronik Inc.**

- **Geliştirici:** Fatih ÖNDER (TB1TFO - CekToR)
- **E-posta:** info@algyazilim.com
- **Web Sitesi:** https://algyazilim.com

---

## 📄 Lisans

Bu proje MIT Lisansı altında lisanslanmıştır - detaylar için [LICENSE](LICENSE) dosyasına bakın.

---

## 🙏 Teşekkürler

- **RadioID.net** - DMR/NXDN/Röle veritabanı API'sini sağladığı için
- **APRS.fi** - Mükemmel APRS takip hizmeti için
- **Radyo Amatörü Topluluğu** - Geri bildirim ve destek için
- **Açık Kaynak Katkıda Bulunanlar** - Bu projeyi daha iyi hale getirdiği için

---

## 🌟 Yıldız Geçmişi

Bu uygulamayı yararlı buluyorsanız, lütfen yıldız vermeyi düşünün! ⭐

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/radio-amateur-id-query&type=Date)](https://star-history.com/#yourusername/radio-amateur-id-query&Date)

---

## 📊 İstatistikler

![GitHub yıldızları](https://img.shields.io/github/stars/yourusername/radio-amateur-id-query?style=social)
![GitHub fork'ları](https://img.shields.io/github/forks/yourusername/radio-amateur-id-query?style=social)
![GitHub izleyicileri](https://img.shields.io/github/watchers/yourusername/radio-amateur-id-query?style=social)

---

<div align="center">

**Radyo Amatörü Topluluğu için ❤️ ile yapıldı**

**73!** 📻

[⬆ Başa Dön](#-radyo-amatörü-dijital-id-sorgulama)

</div>
