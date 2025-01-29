# 🎵 Music Academy App 🎵  

A **React Native** mobile application for a **music academy**, allowing users to **register**, **choose subjects**, and **manage their profiles**. The app integrates **Firebase Authentication** and follows a **modern UI design**.

---

## 🚀 Features  

- 🎨 **Modern UI** – Figma-inspired design  
- 🔥 **Firebase Authentication** – Secure login & signup  
- 🎭 **Course Selection** – Users can choose from various music subjects  
- 📱 **Fully Responsive** – Works on both **iOS & Android**  
- 🎚️ **Styled Picker Component** – Custom dropdown for selecting subjects  

---

## 📷 Screenshots  

| SignUp Screen | Picker Dropdown |
|--------------|----------------|
| ![Signup Screenshot](./assets/screenshots/signup.png) | ![Picker Screenshot](./assets/screenshots/picker.png) |

---

## ⚙️ Tech Stack  

- **React Native** (Expo)  
- **TypeScript**  
- **Formik & Yup** (Form validation)  
- **Firebase Authentication**  
- **RN Picker Select** (Custom dropdowns)  


---

## 🛠 Setup & Installation  

### 1️⃣ Clone the repository  

```sh
git clone https://github.com/your-username/music-academy.git  
cd music-academy
```

2️⃣ Install dependencies
```sh
npm install
```

3️⃣ Start the app
```sh
npm start
```
OR
```sh
expo start
```

4️⃣ Run on emulator/device

Press i for iOS
Press a for Android
🔑 Firebase Setup
Go to Firebase Console
Create a project & enable Authentication
Download google-services.json & GoogleService-Info.plist
Place them in src/services/
Update firebaseConfig.ts
