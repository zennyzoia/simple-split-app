# Simple Split 💸

**Simple Split** is a modern, local, offline-first Android expense-sharing app built with **Jetpack Compose** and **Material 3**. Designed for trips, roommates, and group outings, it simplifies splitting expenses fairly and transparently—defaulting to **R$**.

---

## ✨ Key Features

- **📂 Group & Member Management**: Create multiple expense groups, add members, and reorder groups on your home screen. Archive or settle groups when finished, or view/re-open past settlement histories.
- **⚖️ Flexible Splitting**: Go beyond basic equal splits with non-even splitting options:
  - **Equal**: Split evenly among selected participants.
  - **Exact (R$)**: Assign precise monetary amounts per person.
  - **Percentage (%)**: Split expenses based on custom percentage shares.
- **📊 Advanced Analytics**: Visualize group spending with custom Pie Charts (by Category & Payer) and Bar Charts (spending over time), automatically excluding settlements.
- **🏷️ Expense Categories & Calendar**: Categorize expenses (**Food**, **Transport**, **Rent**, **Toxics**) wrapped neatly with `FlowRow`, and pick precise expense dates using the native Material 3 calendar date picker.
- **💬 WhatsApp & CSV Export**: 
  - Copy WhatsApp-formatted debt summary messages with one tap.
  - Export complete group transaction reports to CSV (including a `type` column distinguishing expenses from settlements).
- **💸 Debt Simplification & History**: Automatically computes the minimum number of transactions required to settle debts, complete with a "Settle" action and full settlement history tracking.
- **🔄 In-App OTA Updates**: Built-in self-hosted update checker that automatically detects new releases and seamlessly prompts in-app downloads and installations.
- **🎨 Light/Dark Mode**: Fully adaptive Material 3 theme supporting system light and dark modes.

---

## 🔒 Privacy & Security Guarantee (100% Offline-First)

> **Your financial data stays yours.**

Simple Split is engineered with an **offline-first architecture**:
- **Zero Cloud Tracking**: There are no backend user accounts, sign-ins, or cloud databases tracking your expenses.
- **Local Storage**: All groups, members, and expenses are saved securely to your device's private internal storage (`context.filesDir`) using robust JSON persistence.
- **Safe Across Updates**: Your local database is safely preserved whenever you update the app.

---

## 🤖 Built with AI ("Vibe Coded")

This project was rapidly conceptualized, engineered, and refined through **AI-assisted development ("vibe coding")**. Every architectural decision, debt-simplification algorithm, and Jetpack Compose UI component was written, tested, and iterated on alongside AI developer agents to deliver a polished, production-grade Android application.

---

## 🚀 Tech Stack

- **UI**: Jetpack Compose & Material 3
- **Architecture**: MVVM with Kotlin Coroutines & `StateFlow`
- **Persistence**: Local JSON file serialization (`org.json`)
- **Min SDK**: Android 14 (API 34)
- **Target SDK**: Android 15/35 (API 37)

---

## 📱 Installation

Download the latest signed APK from the [Releases](https://github.com/zennyzoia/simple-split-app/releases) page and install it directly on your Android device. Future updates will notify you directly inside the app!
