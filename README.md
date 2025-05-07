# 🏝️ Tatil Seyahat Sitesi

Bu proje, ASP.NET MVC kullanılarak geliştirilmiş kapsamlı bir tatil ve seyahat rezervasyon platformudur. Kullanıcıların tatil destinasyonlarını keşfetmelerine, seyahat planları oluşturmalarına ve rezervasyon yapmalarına olanak tanır.

![Tatil Seyahat Sitesi](https://img.shields.io/badge/ASP.NET%20MVC-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

## 📋 Proje Özellikleri

### 🌟 Kullanıcı Tarafı
- Tatil destinasyonlarını listeleme ve detaylarını görüntüleme
- Gelişmiş filtreleme ve arama fonksiyonları
- Kullanıcı hesabı oluşturma ve yönetme
- Rezervasyon yapma ve ödeme işlemleri
- Yorumlar ve puanlamalar
- Seyahat blog içerikleri
- İletişim formu

### ⚙️ Admin Paneli
- Destinasyon yönetimi (ekleme, düzenleme, silme)
- Rezervasyon takibi ve yönetimi
- Kullanıcı yorumlarını onaylama/reddetme
- Blog yazıları yönetimi
- İstatistik ve raporlama

## 🛠️ Kullanılan Teknolojiler

- **Backend**: ASP.NET MVC 5
- **Programlama Dili**: C#
- **Veritabanı**: SQL Server
- **ORM**: Entity Framework (Code First yaklaşımı)
- **Frontend**: HTML5, CSS3, JavaScript, jQuery
- **Tasarım**: Bootstrap 4
- **Kimlik Doğrulama**: ASP.NET Identity
- **Araçlar**: Visual Studio 2022

## 📦 Veritabanı Yapısı

Proje, Code First yaklaşımı kullanılarak aşağıdaki ana tablolarla yapılandırılmıştır:

- **Destinations**: Tatil yerlerinin bilgileri
- **Reservations**: Kullanıcı rezervasyonları
- **Comments**: Kullanıcı yorumları
- **Blogs**: Blog yazıları
- **Users**: Kullanıcı bilgileri
- **ContactMessages**: İletişim formundan gelen mesajlar

## 🚀 Kurulum

1. Projeyi klonlayın:
   ```
   git clone https://github.com/yusufbalcidev/Tatil-Seyahat-Sitesi-.git
   ```

2. Visual Studio'da projeyi açın.

3. `Web.config` dosyasında veritabanı bağlantı dizesini kendi ortamınıza göre ayarlayın:
   ```xml
   <connectionStrings>
     <add name="TatilSeyahatContext" connectionString="Data Source=YOURSERVER;Initial Catalog=TatilSeyahatDB;Integrated Security=True;" providerName="System.Data.SqlClient" />
   </connectionStrings>
   ```

4. Package Manager Console'da migrations'ı etkinleştirin ve veritabanını oluşturun:
   ```
   Enable-Migrations
   Update-Database
   ```

5. Projeyi derleyin ve çalıştırın.


## 🔄 Proje Mimarisi

- **Model**: Veritabanı tablolarını temsil eden sınıflar
- **View**: Kullanıcı arayüzünü oluşturan Razor görünümleri
- **Controller**: İş mantığını yöneten denetleyiciler
- **Repository**: Veritabanı işlemlerini soyutlayan repository pattern
- **ViewModel**: Görünüm için özelleştirilmiş veri modelleri

## 🔮 Gelecek Planları

- Çoklu dil desteği
- Mobil uygulaması
- Gerçek zamanlı bildirim sistemi
- Sosyal medya entegrasyonu
- Google Maps entegrasyonu

## 👨‍💻 Geliştirici

Bu proje [Yusuf Balci](https://github.com/yusufbalcidev) tarafından geliştirilmiştir.


⭐ Bu projeyi beğendiyseniz, yıldız vermeyi unutmayın! ⭐
