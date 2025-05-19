# 🎓 Study Color - Çocuklar İçin Eğitici Oyun Uygulaması 🎓

Study Color, kullanıcıların vücut parçalarını, renkleri ve sayıları eğlenceli ve etkileşimli oyunlar aracılığıyla öğrenmelerini sağlayan modern bir Android uygulamasıdır. Jetpack Compose ile geliştirilen bu uygulama, sezgisel ve duyarlı bir kullanıcı arayüzü sunarak her yaştan kullanıcı için öğrenme deneyimini keyifli hale getirir. Uygulama, farklı ekran boyutlarına ve yönlendirmelere uyum sağlayan dinamik bir tasarıma sahiptir ve sesli geri bildirimlerle öğrenmeyi destekler.

## Kullanılan Teknolojiler ve Kütüphaneler

### Temel Teknolojiler

- **Jetpack Compose**: Android'in modern UI geliştirme kiti, tüm ekranlar ve bileşenler için kullanıldı.
- **Kotlin**: Uygulamanın ana programlama dili, güvenli ve kısa bir söz dizimi sunar.
- **Android ViewModel**: UI ile ilgili verileri yaşam döngüsüne uygun şekilde yönetmek için.
- **Kotlin Coroutines**: Ses çalma ve UI güncellemeleri gibi asenkron işlemler için.
- **MediaPlayer**: Talimat ve geri bildirim seslerini oynatmak için kullanılan Android API'si.

- ## Proje Ekran Görüntüleri

Aşağıda projenin bazı ekran görüntülerini bulabilirsiniz:

<img src="https://github.com/user-attachments/assets/57713eb8-66d8-4e11-a098-280f47b92efb" width="200">
<img src="https://github.com/user-attachments/assets/510d76d4-1961-420f-9bf6-547a36fa2052" width="200">
<img src="https://github.com/user-attachments/assets/8222343e-ecad-4798-b755-02aaea474fc4" width="200">
<img src="https://github.com/user-attachments/assets/47a13119-6428-49ea-a14a-ef0908622fc7" width="200">
<img src="https://github.com/user-attachments/assets/70fcbc40-38bf-4239-8cc8-cb5fb20484a0" width="200">

## Demo
Study Color uygulamasının temel özelliklerini ve kullanımını gösteren demo videosuna aşağıdaki bağlantıdan ulaşabilirsiniz:
🎬 [**Study Color Tanıtım Videosu**](https://drive.google.com/file/d/19m6Uo1T2U3Olh3LktHleD36JMGLqbvSs/view?usp=sharing)
Video içeriği:
- Vücut Parçaları Oyunu
- Renkler Oyunu
- Sayılar Oyunu
- Duyarlı tasarım örnekleri
  

### UI ve Kullanıcı Deneyimi

- **Material Design 3**: Modern ve şık bir arayüz için kullanılan tasarım bileşenleri.
- **androidx.compose.material3**: Butonlar, metin stilleri ve dinamik temalar için.
- **Custom Typography**: Özel yazı tipi (chewyRegularFamily) ile eğlenceli ve okunabilir metinler.
- **Responsive Layouts**: Ekran boyutuna ve yönlendirmeye göre dinamik boyutlandırma (LocalConfiguration).
- **Android Resources**:
  - **R.drawable**: Vücut parçaları, renkler ve sayılar için görseller.
  - **R.raw**: Sesli talimatlar ve geri bildirim sesleri.

### Oyun Mekanikleri

- **State Management**: mutableStateOf ile reaktif durum yönetimi.
- **Randomization**: kotlin.random.Random ile oyun öğelerinin rastgele sıralanması.
- **LaunchedEffect**: Oyun başlatma ve durum güncellemeleri için kullanılan Compose API'si.

## Uygulama Özellikleri

- **Splash Screen**: Uygulama açılışında kullanıcıyı karşılayan modern ve görsel bir karşılama ekranı.
- **Vücut Parçaları Oyunu**:
  - 2x2 ızgara düzeninde vücut parçalarını (ör. "Ağız", "Kulak") seçme oyunu.
  - Sesli talimatlar ve doğru/yanlış cevaplar için geri bildirim.
  - Portre ve manzara moduna uyumlu dinamik düzen.
- **Renkler Oyunu**:
  - Kullanıcıların renkleri tanımasını sağlayan etkileşimli bir oyun.
  - Canlı renk paletleri ve sesli geri bildirimlerle desteklenir.
- **Sayılar Oyunu**:
  - Sayıları öğrenmek için ızgara tabanlı bir seçim oyunu.
  - Sorular (ör. "Hangi sayı 5?") ve sesli talimatlarla desteklenir.
- **Duyarlı Tasarım**: Telefonlar, tabletler ve katlanabilir cihazlar için optimize edilmiş arayüz.
- **Ses Entegrasyonu**: Her oyun için talimat ve geri bildirim sesleri, öğrenme deneyimini zenginleştirir.




