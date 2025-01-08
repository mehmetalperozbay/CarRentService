# CarRentService

CarRentService, araç kiralama süreçlerini yönetmek ve kullanıcı doğrulamalarını gerçekleştirmek için geliştirilmiş bir uygulamadır. Proje, kullanıcıların araç kiralama işlemlerini basitleştirirken yöneticiler için de bir admin paneli sunmaktadır. 

Proje Proje Ödevi Olarak Yapılmıştır. 2024 - 2025 Eğitim Öğretim Yılı.

## Özellikler

- **Admin Paneli:**
  - Kullanıcıları Spectre Console ile Görme.
  - Kiralanan Arabaları Görme.
  - Kullanıcı Ekleme/Silme/Sorgulama.
  - Destek Talepleri.
  - Kiralama geçmişi görüntüleme.
- **Kullanıcı Yönetimi:**
  - T.C. Kimlik No (TCKN) doğrulama sistemi.
  - Kullanıcı kayıt ve giriş işlemleri.
- **Araç Kiralama:**
  - Kullanıcıların araç kiralayıp iade işlemlerini gerçekleştirebilmesi.
- **API Entegrasyonu:**
  - TCKN doğrulama işlemleri için dış bir API kullanımı [NVI API](https://www.nvi.gov.tr/).

## Kullanılan Teknolojiler

### Backend
- **C# (ASP.NET Core)**: Backend geliştirme için.
- **HttpClient**: TCKN API'sine istek gönderme ve yanıt alma işlemleri.
- **MySQL**: Veritabanı yönetimi.

  
### Kullanılan NuGet Paketleri
- **[MySql.Data (v9.1.0)](https://www.nuget.org/packages/MySql.Data/):** MySQL veritabanı ile bağlantı.
- **[Newtonsoft.Json (v13.0.3)](https://www.nuget.org/packages/Newtonsoft.Json/):** JSON verilerini işlemek için.
- **[Spectre.Console (v0.49.1)](https://www.nuget.org/packages/Spectre.Console/):** Konsol tabanlı zengin kullanıcı arayüzü oluşturmak için.

### API
- **TCKN Doğrulama API'si:** Kullanıcıların T.C. Kimlik Numaralarını doğrulamak için bir dış API kullanıldı [NVI API](https://www.nvi.gov.tr/).

## Gereksinimler

Projeyi çalıştırmak için aşağıdaki yazılımlara ihtiyacınız var:

- [.NET SDK (5.0 veya üzeri)](https://dotnet.microsoft.com/download)
- [MySQL Server](https://www.mysql.com/)

### Projeyi Klonlama

[Adım 1](./images/git1.png)
[Adım 2](./images/git1.png)

Veya

```bash
git clone https://github.com/mehmetalperozbay/CarRentService.git
cd CarRentService
