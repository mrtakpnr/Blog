# ASP.NET CORE MVC BLOG WEBPROJEM

ASP.NET tabanlı kişisel blog sitem, sağlam bir katmanlı yapı üzerine inşa edildi ve bağımlılıkları mümkün olduğunca minimize etmeye odaklandı. Ziyaretçiler, blog yazılarına yorum yapabilir ve aldıkları cevaplarla etkileşimde bulunabilirler. Ancak, tüm yorumlar önce admin panelinden geçer ve içerikleri kontrol edilip onaylandıktan sonra yayınlanır. Onaylanan yorumlar, ilgili blog yazılarının altında görülebilir.

Yöneticiler, admin panelinden mevcut blog girişlerini düzenleyebilir ve durumlarını değiştirebilirler. Bu, içeriğin güncel ve yönetilebilir kalmasını sağlamak adına önemli bir özelliktir. Hem yeni blog girişleri eklemek hem de mevcutları güncellemek oldukça kolaydır.

Veritabanı olarak MS-SQL kullanılarak, blog yazıları ve yorumlar güvenli ve düzenli bir şekilde depolanır. Bu, veri yönetimi açısından güçlü bir temel sağlar.

## Kullanılan Teknolojiler

- Katmanlı Mimari / Onion Pattern
- Asp.Net Core 7
- Ajax
- N Tier Architecture (Entity Layer, Service Layer, 
- DataAccess Layer, UI Layer)
- Identity Authorization
- Entity Framework Core
- MS Sql
- Generic Repository
- Unit Of Work
- LINQ
- JavaScript
- Bootstrap
## Bilgisayarınızda çalıştırmak için appsetting.js dosyasına bu kodu eklemeniz gerekir.

```javascript
{
  "ConnectionStrings": {
    "ConnStr": "Bu kısmı kendinize göre ayarlamanız gereklidir"
  },
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  "AllowedHosts": "*"
}
```

  
