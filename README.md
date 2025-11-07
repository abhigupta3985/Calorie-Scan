# Calorie Scan

## Introduction
A full-stack web app that lets users scan food dish QR codes, view nutritional details, and calculate total calories in real time.  
Built with **HTML, CSS, JavaScript, Node.js, Express, and MongoDB** — this project combines frontend interactivity with backend CRUD APIs for managing dishes and calorie data.

---

## Deployed App
- [Live Link](#) *https://caloriescanner.netlify.app/*

## Features

- **QR Code Scanning:** Reads QR codes containing dish and item data.  
- **Dynamic Calorie Calculation:** Fetches calorie data from the backend and updates totals instantly as users change quantities.  
- **Interactive UI:** Simple and intuitive interface to explore dish items and calorie breakdown.


---


## Setup Instructions

### Prerequisites
1. **Node.js** (v14+ recommended)
2. **MongoDB Database**
3. **Browser with QR Code Camera Access**

### Installation Steps
1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd calorie-calculator
   ```

2. **Install Backend Dependencies:**
   ```bash
   cd backend
   npm install
   ```

4. **Run the Backend Server:**
   ```bash
   npm start
   ```
   The backend will run on `http://localhost:5000`.

5. **Set Up Frontend:**
   - Open the `frontend/index.html` file in a browser.

---


## Screenshots
<img width="1515" height="782" alt="Screenshot 2025-11-07 222835" src="https://github.com/user-attachments/assets/b3ddfaf4-e29f-4311-85a2-ea907ead764e" />


<img width="856" height="790" alt="Screenshot 2025-11-07 222640" src="https://github.com/user-attachments/assets/bc6240aa-dc19-465d-8b13-c2822342b2ce" />

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|---------------|
| Frontend | HTML, CSS, JavaScript |
| QR Library | [qr-scanner](https://github.com/nimiq/qr-scanner) |
| Backend | Node.js, Express.js |
| Database | MongoDB |

---
