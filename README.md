# Online Store Project

## Struktur Proyek
Proyek ini dibangun menggunakan microservices dengan teknologi .NET, Docker, RabbitMQ, dan API Gateway.

## Cara Menjalankan Proyek
1. Pastikan Docker sudah terinstal.
2. Jalankan `docker-compose up` untuk menjalankan seluruh layanan secara bersamaan.
3. Akses API Gateway pada `localhost:5000`.

cd services/OrderService
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools

cd ../CustomerService
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools

cd ../InventoryService
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools

cd ../PaymentService
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools