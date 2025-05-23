# Gerçek Zamanlı Anlık Mesajlaşma Uygulaması
Bu proje, ASP.NET Core ve SignalR teknolojileri kullanılarak geliştirilmiş, kullanıcıların birbirleriyle gerçek zamanlı olarak mesajlaşabildiği basit bir anlık mesajlaşma uygulamasıdır. Lütfen appsetting dosyanızda kendi server isminizi eklemeyi unutmayın.
---
## Projenin Amacı
Bu projenin amacı, istemciler arasında gerçek zamanlı iletişim kurulmasını sağlayan bir sistem tasarlamaktır. Kullanıcılar bir arayüz üzerinden giriş yaparak, listedeki diğer kullanıcıları seçip onlarla anlık olarak mesajlaşabilmektedir.
---
## Kullanılan Teknolojiler ve Kütüphaneler
- ASP.NET Core MVC – Web uygulamasının temel çatısını oluşturur.
- SignalR – Gerçek zamanlı veri iletimi ve istemciler arası iletişimi sağlar.
- Entity Framework Core – Veritabanı işlemleri ve ORM (Object-Relational Mapping) için kullanılır.
- Microsoft SQL Server – Verilerin kalıcı olarak saklandığı veritabanı sistemi.
- Bootstrap (isteğe bağlı) – Basit ve duyarlı kullanıcı arayüzü oluşturmak için (kullanıldıysa).
- Visual Studio / .NET CLI – Geliştirme ortamı ve proje yönetimi.
---
## Özellikler
- Kullanıcılar giriş yapmadan doğrudan kullanıcı adıyla mesajlaşabilir.
- Gerçek zamanlı mesaj gönderme ve alma (SignalR ile).
- Kullanıcı seçimi ve birebir mesajlaşma desteği.
- Mesajların veritabanında kalıcı olarak saklanması.
- Veritabanı olarak Entity Framework ile SQL Server kullanımı.
---
## Kullanılan Kütüphaneler
- Microsoft.AspNetCore.SignalR
- Microsoft.AspNetCore.SignalR.Client
- Microsoft.EntityFrameworkCore
- Microsoft.EntityFrameworkCore.SqlServer
- Microsoft.EntityFrameworkCore.Tools
- Microsoft.AspNetCore.Mvc
- Microsoft.Extensions.DependencyInjection
- Microsoft.AspNetCore.Http
- Microsoft.AspNetCore.Routing
- System.ComponentModel.DataAnnotations
- Microsoft.AspNetCore.StaticFiles
- Microsoft.AspNetCore.Hosting
- Microsoft.Extensions.Hosting
- Microsoft.NET.Sdk.Web
---
