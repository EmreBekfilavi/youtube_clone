# React Project

Bu proje **React** kullanılarak geliştirilmiştir ve yoğun şekilde **JavaScript (ES6+)** içermektedir. Amaç; modern frontend pratiklerini kullanarak ölçeklenebilir, okunabilir ve kolay geliştirilebilir bir yapı sunmaktır.

## 🚀 Proje Özeti

* React (Hooks & Functional Components)
* Modern JavaScript (ES6+)
* Component bazlı mimari
* Modüler ve okunabilir kod yapısı
* Geliştirme ve test odaklı kurulum

Bu README dosyası, projeyi **local ortamınızda sorunsuz şekilde çalıştırabilmeniz** için gerekli tüm adımları açıklamaktadır.

---

## 📦 Gereksinimler

Projeyi çalıştırmadan önce sisteminizde aşağıdaki araçların kurulu olduğundan emin olun:

* **Node.js** (önerilen: LTS sürüm)
* **npm** veya **yarn**
* Git

Node.js sürümünüzü kontrol etmek için:

```bash
node -v
npm -v
```

---

## 🔧 Kurulum

### 1. Repoyu Klonlayın

```bash
git clone https://github.com/EmreBekfilavi/youtube_clone
```

```bash
cd youtube_clone
```

### 2. Bağımlılıkları Yükleyin

```bash
npm install
```

veya

```bash
yarn install
```

---

## ▶️ Projeyi Çalıştırma

Local development ortamında projeyi ayağa kaldırmak için:

```bash
npm start
```

veya

```bash
yarn start
```

Uygulama varsayılan olarak aşağıdaki adreste çalışacaktır:

```
http://localhost:3000
```

Tarayıcı otomatik açılmazsa, adresi manuel olarak ziyaret edebilirsiniz.

---

## 🗂️ Proje Yapısı (Özet)

```text
src/
 ├─ components/      # Tekrar kullanılabilir React componentleri
 ├─ services/        # API ve dış servis işlemleri
 ├─ utils/            # Yardımcı fonksiyonlar
 ├─ assets/           # Statik dosyalar
 ├─ App.js            # Ana uygulama bileşeni
 └─ index.js          # Uygulama giriş noktası
```

---

## 🌱 Ortam Değişkenleri

Eğer projede environment variable kullanılıyorsa, root dizininde bir `.env` dosyası oluşturmanız gerekebilir:

```env
REACT_APP_API_URL=your_api_url_here
```

> **Not:** `REACT_APP_` ile başlayan değişkenler React tarafından erişilebilir.

---

## 🛠️ Build Alma

Production build oluşturmak için:

```bash
npm run build
```

Bu işlem sonucunda `build/` klasörü oluşur ve deploy için hazır hale gelir.

---

## 🧪 Testler (Varsa)

```bash
npm test
```

---

## 📌 Notlar

* Proje **local development** için optimize edilmiştir.
* Kod yapısı genişletilmeye uygundur.
* React best practice’leri göz önünde bulundurulmuştur.

---

## 🤝 Katkıda Bulunma

Pull request’ler her zaman açıktır. Büyük değişiklikler için lütfen önce bir issue açınız.

---

## 📄 Lisans

Bu proje kişisel/öğrenme amaçlı geliştirilmiştir. Lisans bilgisi eklemek isterseniz burayı güncelleyebilirsiniz.

---

✨ Her türlü geri bildirim ve katkı için teşekkürler!
