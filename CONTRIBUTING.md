# 🤝 Katkıda Bulunma Rehberi

GymBuddy projesine katkıda bulunmak istediğiniz için teşekkürler! Bu rehber, projeye nasıl katkıda bulunabileceğinizi açıklar.

## 📋 İçindekiler

- [Nasıl Katkıda Bulunabilirim?](#nasıl-katkıda-bulunabilirim)
- [Geliştirme Ortamını Kurma](#geliştirme-ortamını-kurma)
- [Kod Standartları](#kod-standartları)
- [Commit Mesajları](#commit-mesajları)
- [Pull Request Süreci](#pull-request-süreci)
- [Raporlama](#raporlama)

## 🚀 Nasıl Katkıda Bulunabilirim?

### Yeni Başlayanlar İçin
- [Issues](https://github.com/furblood0/GymBuddy/issues) sayfasını inceleyin
- "good first issue" etiketli konuları arayın
- Dokümantasyonu iyileştirin

### Deneyimli Geliştiriciler İçin
- Yeni özellikler ekleyin
- Hata düzeltmeleri yapın
- Performans iyileştirmeleri
- Kod refactoring

## 🛠️ Geliştirme Ortamını Kurma

### Gereksinimler
1. **Clomosy IDE** veya uyumlu geliştirme ortamı
2. **Git** yüklü olmalı
3. **TrObject** dili desteği

### Kurulum Adımları
```bash
# Repository'yi fork edin
git clone https://github.com/YOUR_USERNAME/GymBuddy.git
cd GymBuddy

# Ana repository'yi upstream olarak ekleyin
git remote add upstream https://github.com/furblood0/GymBuddy.git
```

## 📝 Kod Standartları

### Genel Kurallar
- **Okunabilirlik**: Kodunuzun anlaşılır olmasına dikkat edin
- **Yorumlar**: Karmaşık kod bloklarına açıklayıcı yorumlar ekleyin
- **Tutarlılık**: Mevcut kod stilini takip edin

### TrObject/Clomosy Standartları
```trobject
// Değişken tanımlama
var
  FormName: TclForm;
  ComponentName: TclProComponent;

// Fonksiyon tanımlama
void FunctionName;
{
  // Kod buraya
}

// Hata yönetimi
try
  // Kod
except
  ShowMessage('Hata mesajı');
}
```

### Dosya Organizasyonu
- Her sayfa için ayrı `.tro` dosyası
- Açıklayıcı dosya isimleri
- Tutarlı dizin yapısı

## 💬 Commit Mesajları

### Format
```
<tip>: <kısa açıklama>

<detaylı açıklama (opsiyonel)>
```

### Commit Tipleri
- `feat`: Yeni özellik
- `fix`: Hata düzeltmesi
- `docs`: Dokümantasyon değişiklikleri
- `style`: Kod formatı değişiklikleri
- `refactor`: Kod refactoring
- `test`: Test ekleme veya düzenleme
- `chore`: Yapılandırma değişiklikleri

### Örnekler
```
feat: kullanıcı profil fotoğrafı yükleme özelliği eklendi

- Fotoğraf seçici entegrasyonu
- Base64 encoding desteği
- Profil sayfasında görüntüleme

fix: giriş sayfasında şifre görünürlük hatası düzeltildi

docs: README dosyasına kurulum talimatları eklendi
```

## 🔄 Pull Request Süreci

### 1. Branch Oluşturma
```bash
git checkout -b feature/yeni-ozellik
# veya
git checkout -b fix/hata-duzeltmesi
```

### 2. Değişiklikleri Yapma
- Kodunuzu yazın
- Test edin
- Commit'lerinizi yapın

### 3. Pull Request Oluşturma
1. GitHub'da Pull Request oluşturun
2. Template'i doldurun
3. Değişikliklerinizi açıklayın
4. Screenshot'lar ekleyin (gerekirse)

### 4. Code Review
- Review'ları dikkate alın
- Gerekli değişiklikleri yapın
- Test'leri geçtiğinden emin olun

## 🐛 Raporlama

### Bug Report Template
```markdown
**Hata Açıklaması**
Kısa ve net bir açıklama

**Tekrar Üretme Adımları**
1. '...' sayfasına gidin
2. '...' butonuna tıklayın
3. '...' hatası görünür

**Beklenen Davranış**
Ne olması gerektiği

**Screenshots**
Varsa ekran görüntüleri

**Ortam Bilgileri**
- Clomosy Versiyonu: [örn. 1.0.0]
- İşletim Sistemi: [örn. Windows 10]
- Tarayıcı: [eğer web uygulaması ise]
```

### Feature Request Template
```markdown
**Özellik Açıklaması**
Ne yapmak istediğiniz

**Kullanım Senaryosu**
Bu özelliğin nasıl kullanılacağı

**Alternatif Çözümler**
Varsa alternatif yaklaşımlar

**Ek Bilgiler**
Ekran görüntüleri, mockup'lar vb.
```

## 📞 İletişim

- **Email**: furkanfidan.2357@gmail.com
- **GitHub Issues**: [Issues sayfası](https://github.com/furblood0/GymBuddy/issues)
- **Discussions**: [Discussions sayfası](https://github.com/furblood0/GymBuddy/discussions)

## 🙏 Teşekkürler

Katkılarınız için teşekkürler! Her katkı projeyi daha iyi hale getiriyor.

---

**Not**: Bu rehber sürekli güncellenmektedir. Önerileriniz varsa lütfen paylaşın! 