# 🏋️‍♂️ GymBuddy - Antrenman Partneri Bulma Uygulaması

GymBuddy, kullanıcıların seviyelerine göre antrenman partneri bulmalarını sağlayan modern bir mobil uygulamadır. Clomosy ve TrObject teknolojileri kullanılarak geliştirilmiştir.

## 📱 Özellikler

### 🔐 Kullanıcı Yönetimi
- **Kayıt ve Giriş**: Güvenli kullanıcı kaydı ve giriş sistemi
- **Profil Yönetimi**: Detaylı profil oluşturma ve düzenleme
- **Fotoğraf Yükleme**: Profil fotoğrafı ve antrenman anıları paylaşımı

### 👥 Partner Bulma
- **Akıllı Eşleştirme**: Seviye, lokasyon ve tercihlere göre partner bulma
- **Filtreleme**: Gelişmiş arama ve filtreleme seçenekleri
- **Galeri**: Kullanıcıların fotoğraf paylaşım platformu

### 🎯 Kullanıcı Deneyimi
- **Modern Arayüz**: Kullanıcı dostu ve modern tasarım
- **Responsive**: Farklı ekran boyutlarına uyumlu
- **Hızlı Performans**: Optimize edilmiş veritabanı sorguları

## 🛠️ Teknolojiler

- **Geliştirme Dili**: Clomosy ve TrObject
- **Arayüz**: TclUnit kütüphanesi
- **Veritabanı**: SQLite
- **Veri İşleme**: Base64 encoding/decoding
- **Platform**: Cross-platform mobil uygulama

## 📋 Gereksinimler

### Sistem Gereksinimleri
- Clomosy geliştirme ortamı
- TrObject dili desteği
- SQLite veritabanı desteği

### Kurulum Gereksinimleri
- Clomosy IDE veya uyumlu geliştirme ortamı
- TclUnit kütüphanesi
- SQLite veritabanı sürücüsü

## 🚀 Kurulum

### 1. Projeyi İndirin
```bash
git clone https://github.com/furblood0/GymBuddy.git
cd GymBuddy
```

### 2. Geliştirme Ortamını Hazırlayın
- Clomosy IDE'yi açın
- Proje dosyalarını IDE'ye yükleyin
- Gerekli kütüphanelerin yüklü olduğundan emin olun

### 3. Veritabanını Başlatın
- Uygulamayı ilk kez çalıştırdığınızda veritabanı otomatik olarak oluşturulacaktır
- `GYMBUDDY2.db3` dosyası otomatik olarak oluşturulur

### 4. Uygulamayı Çalıştırın
- `MainCode.tro` dosyasını ana giriş noktası olarak kullanın
- Uygulamayı derleyin ve çalıştırın

## 📁 Proje Yapısı

```
GymBuddy/
├── MainCode.tro          # Ana uygulama giriş noktası
├── RegisterUnit.tro      # Kayıt sayfası
├── AnasayfaUnit.tro      # Ana sayfa
├── FindBuddyUnit.tro     # Partner bulma sayfası
├── MyProfileUnit.tro     # Profil yönetimi
├── GalleryUnit.tro       # Galeri sayfası
├── README.md             # Proje dokümantasyonu
└── .gitignore           # Git ignore dosyası
```

## 🎮 Kullanım

### İlk Kullanım
1. **Kayıt Olun**: Uygulamayı açtığınızda "Kayıt Ol" butonuna tıklayın
2. **Profil Oluşturun**: Kişisel bilgilerinizi ve fotoğrafınızı ekleyin
3. **Giriş Yapın**: Oluşturduğunuz hesap bilgileriyle giriş yapın

### Partner Bulma
1. **Ana Sayfa**: Giriş yaptıktan sonra ana sayfaya yönlendirilirsiniz
2. **Partner Ara**: "Partner Bul" sekmesine gidin
3. **Filtreleme**: Seviye, lokasyon gibi kriterlere göre arama yapın
4. **İletişim**: Uygun partneri bulduğunuzda iletişime geçin

### Galeri
1. **Fotoğraf Yükleme**: Galeri sayfasından fotoğraf yükleyin
2. **Paylaşım**: Antrenman anılarınızı paylaşın
3. **Görüntüleme**: Diğer kullanıcıların fotoğraflarını inceleyin

## 🔧 Geliştirme

### Kod Yapısı
- **Modüler Tasarım**: Her sayfa ayrı bir unit dosyasında
- **Veritabanı Katmanı**: SQLite ile veri yönetimi
- **UI Bileşenleri**: TclUnit ile modern arayüz

### Veritabanı Şeması
```sql
CREATE TABLE Users (
    userID INTEGER PRIMARY KEY AUTOINCREMENT,
    USERNAME TEXT UNIQUE,
    NAME TEXT,
    SURNAME TEXT,
    AGE INTEGER,
    WEIGHT REAL,
    HEIGHT REAL,
    PHONE TEXT,
    PASSWORD TEXT,
    CITY TEXT,
    GENDER TEXT,
    PROFILEPHOTO TEXT
);
```

## 🤝 Katkıda Bulunma

1. Bu repository'yi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/yeni-ozellik`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakın.

## 📞 İletişim

Herhangi bir sorunuz, öneriniz veya geri bildiriminiz varsa:

- **Email**: furkanfidan.2357@gmail.com
- **GitHub**: [@furblood0](https://github.com/furblood0)

## 🙏 Teşekkürler

Bu projeyi geliştirirken kullanılan teknolojiler ve topluluk desteği için teşekkürler.

---

⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!
