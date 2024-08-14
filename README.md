# Angular DataGrid Projesi

Bu proje, Angular framework'ü kullanarak veri ızgarası (DataGrid) oluşturmak ve yönetmek için geliştirilmiş basit bir uygulamadır. Proje, hem istemci (client) hem de sunucu (server) tarafı bileşenlerini içerir.

## Proje Yapısı

### AngularDataGridClient
Bu bölüm, Angular ile geliştirilmiş istemci tarafı uygulamasını içerir. Bu uygulama, `ag-grid-angular` kütüphanesi kullanılarak veri ızgarası bileşenlerini oluşturur ve yönetir.

### AngularDataGridServer
Bu bölüm, ASP.NET Core kullanılarak geliştirilmiş sunucu tarafı API'yi içerir. Sunucu tarafı, Entity Framework Core ile veritabanı işlemlerini yönetir ve istemci uygulaması için gerekli API servislerini sağlar.

#### Kullanılan Kütüphaneler:
- **Microsoft.EntityFrameworkCore**: Veritabanı işlemleri için.
- **Swashbuckle.AspNetCore**: Swagger entegrasyonu için.
- **Bogus**: Test verisi oluşturmak için.
- **Microsoft.AspNetCore.OData**: OData sorguları için.

