# React Native Todo Uygulaması

**Öğrenci Adı:** Yağız Berkutay Ayhan  
**Öğrenci Numarası:** 220404001

## Proje Hakkında

Bu proje, React Native kullanılarak geliştirilmiş bir yapılacaklar listesi (Todo List) uygulamasıdır. Kullanıcılar görev ekleyebilir, listeleyebilir ve silebilir.

## Özellikler

- ✅ Yeni görev ekleme
- ✅ Görevleri listeleme
- ✅ Görevleri silme (tıklayarak)
- ✅ Boş görev kontrolü
- ✅ Klavye yönetimi (otomatik kapanma)
- ✅ Responsive tasarım
- ✅ iOS ve Android desteği

## Kullanılan Teknolojiler

- React Native
- React Hooks (useState)
- React Native Components:
  - FlatList
  - TextInput
  - Pressable
  - KeyboardAvoidingView
  - SafeAreaView

## Kurulum

### Gereksinimler

- Node.js (v14 veya üzeri)
- npm veya yarn
- React Native CLI
- Android Studio (Android için)
- Xcode (iOS için - sadece macOS)

### Adımlar

1. **Projeyi klonlayın:**
```bash
git clone https://github.com/KULLANICI_ADIN/TodoApp.git
cd TodoApp
```

2. **Bağımlılıkları yükleyin:**
```bash
npm install
# veya
yarn install
```

3. **iOS için (sadece macOS):**
```bash
cd ios
pod install
cd ..
```

## Uygulamayı Çalıştırma

### Android için:

1. Android emulator'ünü başlatın veya fiziksel cihazınızı bağlayın
2. Terminalde şu komutu çalıştırın:
```bash
npm run android
# veya
npx react-native run-android
```

### iOS için (sadece macOS):

1. iOS simulator'ünü başlatın veya fiziksel cihazınızı bağlayın
2. Terminalde şu komutu çalıştırın:
```bash
npm run ios
# veya
npx react-native run-ios
```

## Proje Yapısı
```
TodoApp/
├── components/
│   └── TodoItem.js          # Tek görev bileşeni
├── App.js                    # Ana uygulama bileşeni
├── package.json              # Proje bağımlılıkları
└── README.md                 # Bu dosya
```

## Kullanım

1. Uygulamayı açın
2. Üst kısımdaki metin kutusuna görevinizi yazın
3. **"Ekle"** butonuna tıklayın
4. Göreviniz listeye eklenecektir
5. Bir görevi silmek için üzerine tıklayın

## Önemli Notlar

- Boş görev eklenemez
- Görev eklendikten sonra klavye otomatik kapanır
- Her görevin benzersiz bir ID'si vardır
- Liste boşsa "Henüz görev yok. Bir tane ekle!" mesajı görünür

## Geliştirme Aşamaları

### Commit 1: Proje Başlangıcı
- İlk kurulum
- Temel UI yapısı

### Commit 2: State Yönetimi
- useState hook'u eklendi
- TextInput kontrolü eklendi
- Görev ekleme fonksiyonu

### Commit 3: Liste Görünümü
- FlatList implementasyonu
- TodoItem bileşeni
- Dinamik liste render

### Commit 4: Silme Özelliği
- Pressable ile interaktif öğeler
- deleteTaskHandler fonksiyonu
- Görsel geri bildirim

### Commit 5: Klavye Yönetimi
- KeyboardAvoidingView eklendi
- Keyboard.dismiss() implementasyonu
- Platform-specific davranışlar

## Ekran Görüntüleri

*(Buraya uygulamanızın ekran görüntülerini ekleyebilirsiniz)*

## Lisans

Bu proje eğitim amaçlı geliştirilmiştir.

## İletişim

- **Öğrenci:** Yağız Berkutay Ayhan
- **Numara:** 220404001
- **GitHub:** [github.com/KULLANICI_ADIN](https://github.com/KULLANICI_ADIN)

---

**Son Güncelleme:** Kasım 2025
