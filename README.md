# 🧮 Calculate

[![Version](https://img.shields.io/badge/version-0.1.1-blue.svg)]()
[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)]()
[![Dart](https://img.shields.io/badge/Dart-3.13-0175C2?logo=dart)]()
[![License](https://img.shields.io/badge/license-MIT-green.svg)]()

> A fast, minimal cross-platform calculator built with **Flutter** — live expression preview,
> calculation history with JSON backup/restore, light/dark themes & in-app update checks.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔴 **Live Auto-Calculation** | Result preview as you type — no need to press `=` every time |
| 🧮 **Modern Keypad** | Digits, operators `+ − × ÷`, `%`, `+/−`, backspace & clear |
| 🕘 **Calculation History** | Local history (Hive) — tap any entry to restore it instantly |
| 💾 **Backup / Restore** | Export & import full history as a `.json` file (duplicate-safe) |
| 🌗 **Light / Dark Theme** | System-aware themes with persisted preference |
| 🎨 **Accent Colors** | Multiple accent swatches to personalize the app |
| 🔄 **In-App Update Check** | Checks GitHub Releases & shows release notes with direct download |
| 📱 **Responsive UI** | ScreenUtil-based responsive design — no overflow on any screen |

---

## 🛠️ Tech Stack

- **Framework:** Flutter (Material 3)
- **Language:** Dart ^3.13.5
- **State Management:** Provider (`ChangeNotifier` + MVC-style separation)
- **Local Storage:** Hive
- **Expression Engine:** `math_expressions` (ShuntingYard parser)
- **Responsive:** `flutter_screenutil` (design size 390×844)
- **Others:** `file_picker`, `shared_preferences`, `package_info_plus`, `http`, `url_launcher`, `flutter_markdown_plus`
