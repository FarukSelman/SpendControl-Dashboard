# 💳 SpendControl Dashboard (Expense Tracking Dashboard)

SpendControl Dashboard, kullanıcıların gelir ve giderlerini kolayca takip edebilmeleri, bütçe durumlarını analiz edebilmeleri ve harcama alışkanlıklarını görselleştirebilmeleri için geliştirilen **Vanilla JavaScript** tabanlı tek sayfa (SPA) bir web uygulamasıdır. Projede herhangi bir frontend framework veya harici grafik kütüphanesi kullanılmamış, tüm işlevler HTML, CSS ve JavaScript ile geliştirilmiştir.

---

# 🛠️ Öne Çıkan Özellikler

## 📊 Gelir ve Gider Yönetimi

- Gelir ve gider kayıtları oluşturma
- Harcamaları kategori bazında takip etme
- Toplam gelir, toplam gider ve kalan bütçeyi hesaplama

---

## 💾 Local Storage Desteği

Uygulama verileri tarayıcının **Local Storage API** kullanılarak saklanmaktadır.

- Sayfa yenilendiğinde veriler korunur.
- Tarayıcı kapatılıp tekrar açıldığında kayıtlar kaybolmaz.
- Harici veritabanına ihtiyaç duyulmaz.

---

## 📈 Canvas API ile Dinamik Grafik

Harici grafik kütüphaneleri kullanılmadan tamamen **HTML5 Canvas API** ile dinamik sütun grafikleri oluşturulmuştur.

Grafik;

- Harcama kategorilerini,
- Harcama miktarlarını,
- Görsel karşılaştırmaları

gerçek zamanlı olarak göstermektedir.

---

## 🔍 Dinamik Filtreleme

Kullanıcılar kayıtlarını;

- Kategoriye göre
- Arama kelimesine göre

anlık olarak filtreleyebilir.

Filtreleme işlemleri JavaScript ile dinamik DOM güncellemesi kullanılarak gerçekleştirilmektedir.

---

## ⚠️ Akıllı Bütçe Takibi

Belirlenen bütçe limiti aşıldığında sistem otomatik olarak kullanıcıyı uyarır.

- Dinamik CSS sınıfları uygulanır.
- Bütçe durumu görsel olarak vurgulanır.

---

# 🏗️ Proje Yapısı

```text
SpendControl-Dashboard/
│
├── index.html          # HTML, CSS ve JavaScript kodları
└── README.md           # Proje dokümantasyonu
```

---

# 🚀 Kullanılan Teknolojiler

## Frontend

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)

## Kullanılan Web API'leri

- Local Storage API
- Canvas 2D API

## Arayüz

- Flexbox
- CSS Grid
- Responsive Layout

---

# 🔧 Kurulum

## 1. Repoyu Klonlayın

```bash
git clone https://github.com/FarukSelman/SpendControl-Dashboard.git
```

## 2. Proje Klasörüne Girin

```bash
cd SpendControl-Dashboard
```

## 3. Uygulamayı Çalıştırın

Herhangi bir kurulum gerektirmez.

Aşağıdaki yöntemlerden biri kullanılabilir:

- `index.html` dosyasını doğrudan çift tıklayarak açın.
- VS Code **Live Server** eklentisi ile çalıştırın.
- Herhangi bir modern web tarayıcısında açın.

---

# 📈 Uygulama Akışı

1. Gelir veya gider kaydı oluşturulur.
2. Kategori seçilir.
3. Kayıt Local Storage'a kaydedilir.
4. Toplam bütçe otomatik hesaplanır.
5. Canvas grafiği güncellenir.
6. Filtreleme ve arama işlemleri gerçek zamanlı uygulanır.
7. Bütçe limiti aşılırsa kullanıcı uyarılır.

---

# 💡 Projenin Amacı

Bu çalışma;

- Vanilla JavaScript ile uygulama geliştirmek,
- Local Storage kullanımını öğrenmek,
- DOM manipülasyonu becerilerini geliştirmek,
- HTML5 Canvas API ile grafik oluşturmak,
- Dinamik kullanıcı arayüzleri geliştirmek,
- Frontend geliştirme pratiği kazanmak

amacıyla hazırlanmıştır.

---

# 👨‍💻 Geliştirici

**Faruk Selman**

GitHub: https://github.com/FarukSelman
