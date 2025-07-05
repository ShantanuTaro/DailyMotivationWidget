# 📱 DailyQuotes Widget

DailyQuotes is a beautiful iOS widget that displays a new motivational quote every day — right on your home screen. Built using SwiftUI and WidgetKit, it brings daily inspiration in a minimal and elegant format.

---

## ✨ Features

- 🗓️ Shows today's date (e.g. `05/07`)
- 💬 Rotates through 366 motivational quotes (including leap year support)
- 🎨 Elegant layout with smooth background
- 📚 Uses `AppIntentTimelineProvider` for timeline generation
- ⚙️ Widget updates automatically every day

---

## 🧠 How It Works

- Quotes are stored in a `DailyQuotes.swift` file as a static list.
- Based on the current day of the year (`1...366`), it selects the corresponding quote.
- Timeline is generated for the next 5 hours (can be updated to daily).
- The widget UI displays the current date and quote in a clean layout.

---

## 🔧 Tech Stack

- `SwiftUI`
- `WidgetKit`
- `AppIntent`
- `Xcode 15+`
- `iOS 17+`

---



