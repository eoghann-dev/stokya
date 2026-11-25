# Stokya

A mobile inventory and point-of-sale application for sari-sari store owners, using barcode scanning to track stock and record sales.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat&logo=android&logoColor=white)

## Overview

Many sari-sari store owners still track inventory and sales by hand or by memory, which makes it hard to know what is in stock, what is selling, and whether the store is actually earning. Stokya replaces manual tracking with a barcode-based workflow that runs on a phone.

Store owners scan their products to build an inventory. When a customer buys an item, the owner scans it with the phone camera and the app deducts it from stock and records the sale. The app also turns that data into sales and profit summaries, so owners can make restocking and pricing decisions with real numbers.

## Features

- **Barcode Inventory Setup:** Scan product barcodes with the device camera to add items to the inventory.
- **Scan-to-Sell:** Scan a product during a sale to record the purchase and deduct it from stock automatically.
- **Low-Stock Alerts:** Get notified when a product runs low so it can be restocked in time.
- **Sales History:** Review a record of past transactions.
- **Sales and Profit Reports:** View total sales and profit by day, week, and month.
- **Cloud Sync:** Inventory and sales data are stored and synced through Firebase.

## Tech Stack

| Category | Technology |
|---|---|
| Framework | Flutter |
| Language | Dart |
| Backend | Firebase |
| State Management | Riverpod  |
| Barcode Scanning | mobile_scanner |

## Getting Started

### Prerequisites

- Flutter SDK (stable channel)
- Dart SDK (bundled with Flutter)
- Android Studio or Visual Studio Code
- A Firebase project
- An Android device or emulator with camera support

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/eoghann-dev/YOUR_REPOSITORY_NAME.git
   cd YOUR_REPOSITORY_NAME
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Configure Firebase:

   - Create a project in the Firebase console.
   - Add an Android app and download `google-services.json`.
   - Place it in `android/app/`.

4. Run the application:

   ```bash
   flutter run
   ```

Barcode scanning requires camera access, so test on a physical device when possible.

## Download

An Android APK is available for testing:

[Download Stokya APK](https://drive.google.com/file/d/1hI2pN2v_p0xmQK325FE4lg2PhdHelP1v/view?usp=sharing)

## Author

**Owen Casabuena**
GitHub: [@eoghann-dev](https://github.com/eoghann-dev)
