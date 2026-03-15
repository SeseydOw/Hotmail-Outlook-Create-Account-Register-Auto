# Igyx UI - Modern WinForms Control Library

A custom, modern, dark-themed UI control library for C# WinForms, designed to provide a consistent and visually appealing user experience.

---

### ✨ Features

- **Modern Dark Theme:** A consistent and sleek dark color palette used across all controls.
- **Custom-Drawn Controls:** All components are drawn manually using GDI+ for pixel-perfect rendering and full control over appearance.
- **High-Quality Rendering:** Utilizes anti-aliasing for smooth and crisp visuals.
- **Easy to Use:** Designed to be used like any standard WinForms control.
- **Fully Open Source:** Licensed under the MIT license.

### 🚀 Usage

#### Prerequisites
- **.NET Framework 4.8** (or a compatible version like 4.7.2).
- Visual Studio 2019 or later.

#### Example: Creating a Borderless Form
```csharp
// In your Form's constructor or Load event:

// The IgyxContainer handles the borderless window and title bar dragging.
IgyxContainer container = new IgyxContainer();
container.Dock = DockStyle.Fill;
this.Controls.Add(container);

// Add custom title bar buttons
CloseButton closeButton = new CloseButton { Dock = DockStyle.Right };
MaxButton maxButton = new MaxButton { Dock = DockStyle.Right };
MinButton minButton = new MinButton { Dock = DockStyle.Right };

this.Controls.Add(closeButton);
this.Controls.Add(maxButton);
this.Controls.Add(minButton);
```

### 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
