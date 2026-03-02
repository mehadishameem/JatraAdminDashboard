# 🚌 EWU Transport Management System (Admin Panel)

A modern, real-time administration dashboard for managing and tracking the East West University shuttle service.

---

## 🚀 Key Features

- **Live Dashboard**: Real-time stats showing Total, Active, and Inactive cars, including average fleet speed.
- **Real-Time Tracking**: Integrated **Leaflet.js** map with live location updates via **Firebase Realtime Database**.
- **Fleet Management (CRUD)**: Easily add, edit, or delete vehicle records, drivers, and routes.
- **Historical Route Mapping**: Interactive breadcrumbs and polyline trails for past trips.
- **Embedded Access Control**: A secure system to manage and grant Gmail-based access for viewing live locations.
- **Responsive Design**: Fully mobile-responsive interface with a premium, card-based layout.

## 🛠️ Technology Stack

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+).
- **Backend/Database**: Firebase Realtime Database.
- **Mappings**: Leaflet.js with OpenStreetMap.
- **Fonts**: Google Fonts (Poppins, Segoe UI).

## 📂 Project Structure

```text
├── index.html            # Main Dashboard & Fleet Management
├── bus-details.html      # Detailed Tracking & History for a specific vehicle
├── accesscontrol.html    # User Access & Gmail Approval Management
├── ewu-logo.png          # Project Branding
└── README.md             # Project Documentation
```

## ⚙️ How to Run Locally

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/mehadishameem/JatraAdminDashboard.git
    cd JatraAdminDashboard
    ```
2.  **Open in Browser**:
    Simply open `index.html` in any modern web browser.
3.  **Firebase Configuration**:
    The project is pre-configured with a Firebase Realtime Database. If you wish to use your own, update the `firebaseConfig` object in `index.html`, `bus-details.html`, and `accesscontrol.html`.

    ```javascript
    const firebaseConfig = {
      databaseURL: "YOUR_FIREBASE_DATABASE_URL"
    };
    ```

## 🤝 Contributing

1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

*This project was developed as part of the EWU Capstone project.*
