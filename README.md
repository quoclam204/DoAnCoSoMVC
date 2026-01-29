# 🛒 Dalat Specialty E-commerce Website

An ASP.NET Core MVC e-commerce platform for selling Dalat specialties.

[![.NET Version](https://img.shields.io/badge/.NET-8.0-purple)](https://dotnet.microsoft.com/)
[![Stars](https://img.shields.io/github/stars/quoclam204/DoAnCoSoMVC)](https://github.com/quoclam204/DoAnCoSoMVC/stargazers)

## 📸 Screenshots

### Homepage
![Homepage](screenshots/homepage.png)

### Product List
![Products](screenshots/products.png)

### Admin Dashboard
![Admin](screenshots/admin.png)

> Add your screenshots to the `screenshots/` folder

## ✨ Features

**Customer**
- Browse and search products
- Shopping cart & checkout
- Order tracking
- User account management

**Admin**
- Product & category management
- Order management
- Customer management
- Sales reports

## 🛠️ Tech Stack

- **Framework**: ASP.NET Core 8.0 MVC
- **Database**: SQL Server
- **ORM**: Entity Framework Core 9.0
- **Auth**: ASP.NET Core Identity
- **UI**: Bootstrap, HTML/CSS/JS

## 🚀 Quick Start

### Prerequisites
- .NET 8.0 SDK
- SQL Server 2019+

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/quoclam204/DoAnCoSoMVC.git
cd DoAnCoSoMVC
```

2. **Setup database**
- Run `HShopScript.sql` in SQL Server Management Studio

3. **Configure connection string**
Edit `EcommerceMVC/appsettings.json`:
```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=HShop;Trusted_Connection=True;TrustServerCertificate=True;"
  }
}
```

4. **Run the application**
```bash
cd EcommerceMVC
dotnet restore
dotnet run
```

5. **Access the app**
- Website: `https://localhost:5001`
- Admin Panel: `https://localhost:5001/Admin`

## 📁 Project Structure

```
DoAnCoSoMVC/
├── EcommerceMVC/          # Main application
│   ├── Areas/Admin/       # Admin area
│   ├── Controllers/       # Controllers
│   ├── Models/            # Data models
│   ├── Views/             # Razor views
│   └── wwwroot/           # Static files
├── HShopScript.sql        # Database script
└── BaoCaoDoAn.docx       # Project report
```

## 📖 Documentation

- [Project Report](BaoCaoDoAn.docx)
- [Installation Guide](HDCaiDat&SuDung.docx)
- [Presentation Slides](SlideBaoCaoLan3.pptx)

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m 'Add NewFeature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## 👨‍💻 Author

**Lam** - [@quoclam204](https://github.com/quoclam204)

## 📝 License

This project is licensed under the MIT License.

---

⭐ If you find this project helpful, give it a star!
