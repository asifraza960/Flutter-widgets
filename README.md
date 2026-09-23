# 🧩 Flutter Widgets: Complete Guide & Examples

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

A comprehensive, production-ready repository featuring practical code examples and structured documentation for Flutter UI widgets. 

This repository serves as an interactive reference guide and UI catalog, covering core layout foundations to advanced form controls for Flutter developers.

---

## 🛠️ Widget Catalog & Overview

### 🟢 1. Core & Basic Widgets
The foundational building blocks for creating visual interfaces and application layouts.

| Widget | Primary Use Case |
| :--- | :--- |
| `Text` | Renders styled text strings with custom typography. |
| `Container` | Versatile box decoration, padding, margin, and constraints wrapper. |
| `Row` | Positions multiple child widgets in a horizontal array. |
| `Column` | Positions multiple child widgets in a vertical array. |
| `Image` | Displays local assets, network images, or raw bytes. |
| `Icon` | Renders vector icons from material or custom icon sets. |
| `Scaffold` | Implements the basic Material Design visual layout structure. |
| `AppBar` | Top application header for actions, titles, and navigation controls. |
| `Center` | Aligns its child widget directly in the middle of available space. |

---

### 🔵 2. Layout & Positioning Widgets
Tools for managing screen responsiveness, spatial distribution, and component layering.

| Widget | Primary Use Case |
| :--- | :--- |
| `Expanded` | Forces a child of a `Row`, `Column`, or `Flex` to expand and fill available space. |
| `Flexible` | Controls how a child widget flexes within a `Row`, `Column`, or `Flex`. |
| `SizedBox` | Fixed-size box wrapper useful for precise spacing or dimension forcing. |
| `Padding` | Insets its child by given offsets. |
| `Align` | Positions a single child within itself and sizes according to the child's bounds. |
| `Wrap` | Displays children in multiple horizontal or vertical runs to prevent overflow. |
| `Stack` | Overlays multiple child widgets on top of each other. |
| `Positioned` | Controls where a child of a `Stack` is positioned using absolute bounds. |
| `AspectRatio` | Attempts to size the child to a specific aspect ratio. |

---

### 🟡 3. Input & Form Widgets
Interactive components for capturing user input and handling form validation state.

| Widget | Primary Use Case |
| :--- | :--- |
| `TextField` | Basic text input field for capturing user input. |
| `TextFormField` | Form-integrated text field supporting validation and state saving. |
| `Checkbox` | Two-state toggle for selecting boolean options. |
| `Radio` | Selects a single option from a mutually exclusive set. |
| `Switch` | Material-style toggle switch for binary preferences. |
| `Slider` | Continuous or discrete range selector. |
| `DropdownButton` | Selectable menu list trigger for picking single options. |
| `Form` | Container for grouping and validating multiple form input fields. |

---

### 🔴 4. Buttons & Interactive Controls
Action-oriented widgets for user triggers and gesture interactions.

| Widget | Primary Use Case |
| :--- | :--- |
| `ElevatedButton` | Filled button with elevated shadow effect for primary actions. |
| `OutlinedButton` | Medium-emphasis button with an explicit border boundary. |
| `TextButton` | Flat text-only button typically used in dialogs and cards. |
| `IconButton` | Compact icon target for localized bar and card actions. |
| `FloatingActionButton` | Prominent circular action button floating over app content. |

---

### 🟣 5. Scrollable & Data Presentation Widgets
High-performance components designed for large datasets, lists, and paginated flows.

| Widget | Primary Use Case |
| :--- | :--- |
| `ListView` | Scrollable linear list of widgets (supports lazy loading via `.builder`). |
| `ListTile` | Standardized single-line or multi-line row structure with leading/trailing slots. |
| `GridView` | 2D scrollable grid array of widgets with customizable grid delegates. |
| `PageView` | Scrollable list that works page-by-page. |
| `SingleChildScrollView` | Single box wrapper that enables scrolling for overflowing children. |

---

## 📦 Getting Started

### Prerequisites

* Flutter SDK (Latest Stable Version)
* Dart SDK

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/flutter-widgets-guide.git](https://github.com/your-username/flutter-widgets-guide.git)
