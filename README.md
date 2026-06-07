# ByteVault 🔐

## E-Commerce Inventory Management System

ByteVault is an industry-level REST API for managing e-commerce inventory. It provides comprehensive features for product management, stock tracking, supplier management, order processing, and invoice generation.

---

## Features

✅ **Product Management** - Create, update, delete products with SKU tracking
✅ **Stock Management** - Real-time inventory tracking with low stock alerts
✅ **Supplier Management** - Manage supplier information and relationships
✅ **Order Management** - Complete order lifecycle with status tracking
✅ **Invoice Generation** - Automated invoice creation and tracking
✅ **Audit Logging** - Track all system changes and user actions
✅ **JWT Authentication** - Secure API with role-based access control

---

## Tech Stack

- **Backend:** ASP.NET Core 8
- **Database:** PostgreSQL
- **Authentication:** JWT (JSON Web Tokens)
- **ORM:** Entity Framework Core
- **Architecture:** Clean Architecture / Repository Pattern

---

## Project Structure

```
ByteVault/
├── ByteVault.API/          # Main API project
├── ByteVault.Data/         # Database layer (EF Core)
├── ByteVault.Core/         # Core business logic
└── Tests/                  # Unit and integration tests
```

---

## Getting Started

### Prerequisites
- .NET 8 SDK
- PostgreSQL 13+
- Visual Studio Code or Visual Studio

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Tharumika/ByteVault.git
cd ByteVault
```

2. Update database connection string in `appsettings.json`

3. Apply migrations:
```bash
dotnet ef database update
```

4. Run the API:
```bash
dotnet run
```

The API will be available at `https://localhost:5001`

---

## API Documentation

(Coming soon - detailed API documentation)

---

## Contributing

This is a learning project demonstrating industry-level .NET development practices.

---

## License

MIT License - See LICENSE file for details

---

## Author

**ByteVault Development Team**
Learning .NET Core REST API Development
