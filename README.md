# 📱 Product Rating Mobile App

Bu proje, kullanıcıların ürünleri listeleyip puanlayabildiği ve Firebase altyapısı ile çalışan bir Android uygulamasıdır. Kotlin dili kullanılarak geliştirilmiştir.

---

## 🚀 Proje Hakkında

Product Rating uygulaması aşağıdaki özellikleri içermektedir:

- Kullanıcı kayıt & giriş işlemleri  
- Firebase Authentication (Email/Password, Telefon, Google)  
- Ürün ekleme  
- Ürün listeleme  
- Ürün puanlama  
- Firebase Realtime Database entegrasyonu  
- RecyclerView ile dinamik listeleme  

---

## 🛠️ Kullanılan Teknolojiler

- Kotlin  
- Android SDK  
- Firebase Authentication  
- Firebase Realtime Database  
- RecyclerView  
- ViewBinding  
- Gradle  

---

## 📂 Proje Yapısı

```
ProductRating/
│
├── app/
│   ├── src/main/java/com/example/productrating/
│   │   ├── MainActivity.kt
│   │   ├── LoginActivity.kt
│   │   ├── RegisterActivity.kt
│   │   ├── FirebaseManager.kt
│   │   ├── Product.kt
│   │   ├── ProductAdapter.kt
│   │   ├── ProductFragment.kt
│   │   └── ...
│   │
│   ├── res/
│   └── AndroidManifest.xml
│
├── build.gradle
└── settings.gradle
```

---

## 🔐 Kimlik Doğrulama Özellikleri

- Email & Şifre ile giriş  
- Google ile giriş  
- Telefon numarası ile OTP doğrulama  
- Yeni kullanıcı kaydı  

---

## 📦 Ürün İşlemleri

- Yeni ürün ekleme  
- Ürünleri listeleme  
- Firebase üzerinden veri çekme  
- Ürünlere puan verme  
- Gerçek zamanlı veri güncelleme  

---

## 🔥 Firebase Kurulumu

1. Firebase Console üzerinden yeni proje oluşturun.  
2. Android uygulaması ekleyin.  
3. `google-services.json` dosyasını indirip `app/` klasörüne ekleyin.  
4. Firebase Authentication ve Realtime Database servislerini aktif edin.  
5. Gradle senkronizasyonunu yapın.  

---

## ▶️ Projeyi Çalıştırma

1. Projeyi Android Studio ile açın.  
2. Gradle senkronizasyonunu bekleyin.  
3. Emulator veya fiziksel cihaz seçin.  
4. Run butonuna basarak uygulamayı başlatın.  

---

## 📌 Gereksinimler

- Android Studio (Güncel sürüm)  
- Minimum SDK: 21+  
- İnternet bağlantısı (Firebase için)  

---
