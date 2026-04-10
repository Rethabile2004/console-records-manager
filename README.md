# C# Console Management App

A C# console application for managing employee and student records. Built using core OOP principles — inheritance, encapsulation, and composition — with a simple menu-driven interface for performing CRUD operations from the terminal.

---

## Tech Stack

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

---

## Features

- Add, list, update, and remove employee records
- Add, list, update, and remove student records
- Store address, company, and school information per record
- In-memory storage using lists and dictionaries
- Simple console menu interface for navigation

---

## Class Structure

```
Person (base class)
├── Employee.cs     — inherits Person, includes company info
└── Student.cs      — inherits Person, includes school info

Address.cs          — composition: used by Person
Program.cs          — entry point and menu logic
```

---

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (4.x or later)
- Visual Studio or any C# compatible IDE

### Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Rethabile2004/C-Sharp-Console-Management-App.git
   ```

2. Open `S1P1.sln` in Visual Studio.

3. Build and run:
   ```bash
   dotnet run
   ```

4. Use the console menu to manage records.

---

## Author

**Rethabile Eric Siase**  
[![GitHub](https://img.shields.io/badge/GitHub-Rethabile2004-181717?style=flat&logo=github&logoColor=white)](https://github.com/Rethabile2004)
