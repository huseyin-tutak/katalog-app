# Mini Katalog Uygulaması

Bu proje, Mobil Uygulama Geliştirme (Android / iOS) Eğitimi kapsamında geliştirilen bir örnek katalog uygulamasıdır. Proje, Flutter'ın temel yapı taşlarını (Widget'lar, Navigasyon, JSON Modelleme, State Yönetimi) öğretmek amacıyla tasarlanmıştır.

## 🚀 Proje Özellikleri

*   **Klasörleme Yapısı:** `lib/screens`, `lib/models`, `lib/widgets`, `lib/data` şeklinde temiz mimari.
*   **JSON Simülasyonu:** `lib/data/product_data.dart` içerisinde bulunan mock JSON verisi `jsonDecode` ile ayrıştırılarak dinamik listeleme yapılmaktadır.
*   **Dinamik Listeleme:** `GridView.builder` kullanılarak ürünlerin grid formatında gösterimi.
*   **Navigasyon:** `Navigator.pushNamed` ile isimlendirilmiş rotalar üzerinden sayfa geçişi ve `Route Arguments` ile veri taşıma.
*   **Model Sınıfı:** `Product` modeli içinde `fromJson` ve `toJson` metodları ile veri modelleme.
*   **State Yönetimi:** `setState` kullanılarak sepet sayacı (Badge) simülasyonu.

## 🛠️ Kullanılan Teknolojiler

*   **SDK:** [Flutter >=3.0.0 <4.0.0](https://flutter.dev)
*   **Dil:** [Dart SDK](https://dart.dev)
*   **UI Paketi:** `material.dart` (Varsayılan)

## 🏗️ Nasıl Çalıştırılır?

Projeyi bilgisayarınızda yerel olarak çalıştırmak için şu adımları izleyin:

1.  **Flutter SDK**'nın siteminizde kurulu olduğundan emin olun.
2.  Proje ana dizinindeyken bağımlılıkları yükleyin:
    ```bash
    flutter pub get
    ```
3.  Uygulamayı bir emulator veya fiziksel cihazda başlatın:
    ```bash
    flutter run
    ```

