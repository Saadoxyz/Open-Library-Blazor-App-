
# 📚 Open Library – Blazor Server Web App

<div align="center">

<img src="https://img.shields.io/badge/Project-Type: Library UI Clone-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Framework-Blazor Server-purple?style=for-the-badge&logo=dotnet" />
<img src="https://img.shields.io/badge/UI-Bootstrap 5-success?style=for-the-badge&logo=bootstrap" />
<img src="https://img.shields.io/badge/Language-C Sharp-lightgrey?style=for-the-badge&logo=csharp" />

</div>

---

## 🌐 Project Overview

**Open Library** is a **Blazor Server** web application that simulates a modern digital library platform. It features a **login system**, a **user-friendly book browsing interface**, and an organized layout for trending books, with dropdown filters and icons inspired by leading book platforms.  
This project was created as a **semester-based UI development task** by **Muhammad Saad Khan**.

---

## 🧩 Features

### 🔐 Login Page
- Custom styled login form
- Pre-filled credentials (for demo):  
  `Username: saad khan`, `Password: 1234`
- "Remember Me" checkbox and alert feedback via JSRuntime

### 🏠 Home Page ("/home")
- Header with `OPEN LIBRARY` branding
- Navigation controls: My Books, Browse dropdown, Search filter
- Yearly goal tracking and reading feature carousel
- Section for Trending Books with status-based UI:
  - ✅ Preview Only
  - ❌ Not in Library
  - 📕 Checked Out
- Book cover previews with interactive alerts on click

---

## 🛠 Technologies Used

| Tool / Language       | Purpose                          |
|------------------------|----------------------------------|
| **Blazor Server (.NET 6+)** | SPA framework with C# and Razor Pages |
| **Bootstrap 5**        | Responsive layout and dropdown styling |
| **HTML/CSS**           | Core layout, custom styling for cards |
| **JavaScript Runtime (IJSRuntime)** | JS alert interop |
| **C#**                 | Backend logic and Razor syntax |
| **Blazor Routing**     | `@page "/Library"` and `@page "/home"` routes |

---

---

## 🔐 Demo Credentials

```bash
Username: saad khan
Password: 1234
```

Upon successful login, a JS alert is triggered and the app redirects to the `/home` route.

---

## 📦 Book Data Sample

```csharp
new BookModel
{
    Title = "Game of Thrones",
    ImageUrl = "images/game-of-thrones.jpg",
    Status = "Checked Out",
    StatusClass = "status-checked-out"
}
```

Each book card is rendered dynamically and styled based on `StatusClass`.

---

## 👨‍💻 Developed By

**Muhammad Saad Khan**
📧 [saado652004@gmail.com](mailto:saado652004@gmail.com)
🔗 GitHub: [@saadoxyz](https://github.com/saadoxyz)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=00BFFF&height=120&section=footer&text=Happy+Reading!&fontColor=ffffff&fontSize=30" />

</div>
```
