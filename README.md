# **Aegis Track - Backend**

🚀 **Aegis Track Backend** is the core API service powering the **Aegis Track Anti-Doping System**. It manages athlete data, whistleblower reports, case assignments, and investigator workflows to ensure transparent and efficient doping detection.

## **🌟 Features**
- 🏆 **Whistleblower Reports API** – Securely log and track doping-related reports.
- 📊 **Athlete Data Management** – Store and retrieve athlete records efficiently.
- 🔍 **Case Assignment & Investigation** – Automate admin case assignments to investigators.
- 🔐 **Secure Authentication** – Implements JWT-based authentication for authorized access.

## **🛠️ Tech Stack**
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT

## **🚀 Installation & Setup**
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/nehasreec/AgeisTrack-Backend.git
   cd AgeisTrack-Backend
   ```
2. **Install Dependencies:**  
   ```bash
   npm install
   ```
3. **Set Up Environment Variables:**  
   Create a `.env` file in the root directory and add the following:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```
4. **Run the Server:**  
   ```bash
   npm start
   ```

## **📜 API Endpoints**
- `POST /api/auth/signup` – Register a new user
- `POST /api/auth/login` – Authenticate user and return token
- `GET /api/athletes` – Retrieve all athlete data
- `POST /api/reports` – Submit a new doping report

## **📜 License**
This project is licensed under the MIT License.

## **🤝 Contributing**
Contributions are welcome! Fork the repo, make changes, and submit a pull request.


