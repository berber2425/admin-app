# Berber Admin Panel

Platform yöneticilerinin kullandığı admin paneli uygulaması. Flutter ile geliştirilmiş web ve desktop uygulaması.

## Özellikler

- Platform yönetimi ve moderasyon
- Kullanıcı ve işletme yönetimi
- İçerik yönetimi
- Raporlama ve analiz
- Sistem ayarları ve yapılandırma

## Teknik Detaylar

### Kullanılan Teknolojiler

- Flutter
- GraphQL (berber2425/gql_client)
- State Management (berber2425/sign, berber2425/sign_flutter)
- Data Layer (berber2425/admin_data_layer)

### Geliştirme Ortamı Gereksinimleri

- Flutter SDK
- VS Code veya Android Studio
- Git

### Kurulum

1. Repository'yi klonlayın

```bash
git clone https://github.com/berber2425/admin_app.git
```

2. Bağımlılıkları yükleyin

```bash
flutter pub get
```

3. Uygulamayı çalıştırın

```bash
# Web için
flutter run -d chrome

# Desktop için
flutter run -d windows # veya macos, linux
```

## Proje Yapısı

```
lib/
  ├── core/           # Çekirdek fonksiyonlar ve utilities
  ├── data/           # Data layer entegrasyonu
  ├── features/       # Özellik bazlı modüller
  ├── shared/         # Paylaşılan widget'lar ve helper'lar
  └── main.dart       # Uygulama giriş noktası
```

## Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun
