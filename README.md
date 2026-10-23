Hero'sBill 🍽️

Offline Restaurant POS Android Application

Hero'sBill is an offline-first restaurant Point of Sale (POS) application built with Java for Android. It helps restaurants manage food items, process orders, handle cash payments, track sales, generate receipts, and maintain local business records.

«Project Status: Phase 1–9 completed. Table-by-Table POS is planned for a future update and is not yet implemented.»

---

📱 About

Hero'sBill is designed to provide a simple, reliable, and offline restaurant billing experience.

The application uses a local SQLite database to store restaurant data, allowing users to manage their POS operations without requiring an internet connection.

✨ Features

🛒 Normal POS

- Food selection and cart management
- Add and remove food items
- Quantity adjustment
- Automatic bill calculation
- Cash payment processing
- Cash received and change calculation
- Bill review before payment
- Persistent draft cart recovery

🍔 Food Management

- Manage food items and categories
- Add, edit, and remove food records
- Local food image management
- Food image selection and processing
- Local food price management

🧾 Billing & Payments

- Bill generation
- Cash payment handling
- Bill details
- Completed bill editing
- Bill cancellation
- Partial and full refund handling
- Payment and refund records

📜 History

- View previous bills
- Search bills
- Filter bills by status
- Filter bills by date
- View completed, edited, refunded, and cancelled bills
- Open detailed bill information

📊 Reports

- Today, weekly, and monthly reports
- Custom date range reports
- Gross sales
- Refunds
- Edit returns
- Cancellation totals
- Net sales
- Bill count
- Average bill
- Cash summary
- Top-selling food items
- Daily sales breakdown

🧾 Receipt & PDF

- Receipt preview
- Bill item details
- Payment information
- PDF receipt generation
- Save receipts
- Share receipts
- Existing bill receipt regeneration

⚙️ Settings

- Bengali and English language support
- Dark, light, and system themes
- Application information
- Developer information
- Privacy policy
- App lock functionality

💾 Backup & Restore

- Create local backups
- Restore application data
- SQLite database backup
- Food image backup
- Backup validation
- SHA-256 checksum verification
- Restore confirmation
- Automatic safety backup
- Restore rollback and recovery mechanisms

🌐 Offline Architecture

- Local SQLite database
- Offline food management
- Offline billing
- Offline reports
- Offline receipt generation
- Local backup and restore

No internet connection is required for the core POS functionality.

---

🚧 Upcoming Features

Table-by-Table POS

A Table-by-Table restaurant ordering system is planned for a future release.

Planned functionality includes:

- Normal POS and Table POS available simultaneously
- Unlimited table management
- Custom table names and numbers
- Available, Occupied, and Reserved table statuses
- Independent running orders for each table
- Add food to existing table orders
- Edit item quantities
- Remove order items
- Table order cancellation
- Preparing and Served kitchen statuses
- Full table billing
- Partial and full payment
- Table information in bill history
- Integration with existing reports
- Integration with existing receipts
- Backup and restore support for table data

These Table POS features are planned and are not included in the currently completed Phase 1–9 implementation.

Split billing and table transfer are not included in the current planned scope.

---

🛠️ Tech Stack

Component| Technology
Language| Java
Platform| Android
Database| SQLite
Development Environment| AIDE / Android IDE
Minimum SDK| Android 7.0 (API 24)
Target SDK| Android API 34+
Architecture| Offline-first
UI| Native Android Views
Localization| Bengali & English

---

📦 Installation

1. Download the latest available APK from the GitHub Releases section.
2. Install the APK on a compatible Android device.
3. Open Hero'sBill.
4. Configure the application settings.
5. Add food items and categories.
6. Start using the Normal POS.

An internet connection is not required for normal POS operations.

---

🔐 Privacy

Hero'sBill is designed for offline restaurant management.

Core business data is stored locally on the device.

Backup files may contain business records and food images. Users should keep backup files secure.

The application does not require Firebase authentication or a cloud account for its core offline POS functionality.

---

👨‍💻 Developer

Shahriyar Razin Shams

Android Application Developer

---

📄 License

The repository license will determine how this project may be used, modified, and redistributed.

Check the repository's LICENSE file before using or redistributing the source code.

---

📌 Project Status

- Phase 1–9: Completed
- Normal POS: Existing implementation
- Food Management: Existing implementation
- Billing & Payments: Existing implementation
- History & Reports: Existing implementation
- Receipt & PDF: Existing implementation
- Backup & Restore: Existing implementation
- Table-by-Table POS: Upcoming

Hero'sBill — Offline Restaurant POS
