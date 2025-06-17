# BlazorToast Showcase Website

![Demo Badge](https://img.shields.io/badge/demo-live-green) ![License](https://img.shields.io/badge/license-MIT-blue)

A visually engaging static website built with Blazor WebAssembly that demonstrates the capabilities, usage examples, and customization options of the BlazorToast library.

## 📚 Table of Contents

* [🚀 Live Demo](#-live-demo)
* [✨ Features](#-features)
* [🛠️ Prerequisites](#️-prerequisites)
* [🏗️ Getting Started](#️-getting-started)
* [📁 Project Structure](#-project-structure)

---

## 🚀 Live Demo

* **Showcase Site**: [BlazorToastShowcase](https://zl23abdessamed.github.io/BlazorToastWebTest/)
* **Library Repository**: [BlazorToast](https://github.com/Zl23Abdessamed/BlazorToast)
* **Community Chat**: [Discord](https://discord.gg/84X9nm3fKn)

---

## ✨ Features

* **Interactive Examples**: Play with all toast types (Success, Error, Warning, Info, Loading, Custom)
* **Position Control**: Switch between six screen positions
* **Theme Picker**: Toggle Light, Dark, System, and Auto themes
* **Animation Gallery**: Preview 12+ built‑in entry/exit animations
* **Advanced Scenarios**: Promise‑based toasts, progress bars, interactive actions
* **Responsive Design**: Displays beautifully on desktop and mobile
* **Accessibility**: Keyboard navigation, ARIA roles, focus management

---

## 🛠️ Prerequisites

* [.NET 7 SDK or later](https://dotnet.microsoft.com/download)
* A modern browser (Chrome, Edge, Firefox, Safari)
* Git

---

## 🏗️ Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-org/blazortoast-showcase.git
   cd blazortoast-showcase
   ```
2. **Restore dependencies**

   ```bash
   dotnet restore
   ```
3. **Run the development server**

   ```bash
   dotnet run --project src/BlazorToastWebTest
   ```

---

## 📁 Project Structure

```plaintext
blazortoast-showcase/
├─ .github/             # CI workflows (e.g., GitHub Pages deployment)
├─ Components/          # Reusable UI components for the showcase
├─ Layout/              # Layout and shared markup
├─ Pages/               # Razor pages demonstrating features
├─ Properties/          # Project properties and settings
├─ wwwroot/             # Static assets (CSS, images, favicon)
├─ App.razor            # Root component
├─ BlazorToastWebTest.csproj  # WebAssembly project file
├─ Program.cs           # App startup and service registration
├─ _Imports.razor       # Global using directives
└─ nuget.config         # NuGet feeds/configuration
```
