# The Potters Edu Services
Full-stack Expo/React Native + Node/Express school-management starter for Potters Academy Bida.

## Mobile features
Home, About, Admissions, Fees/Opay payment, receipt Google Form, Results, Portal roles, Attendance entry point, Timetable entry point, Assignments entry point, Announcements, Gallery, Contact and school dashboard.

## Backend features
Express API, SQLite, JWT authentication, bcrypt password hashing, role-based authorization, applications, results, announcements and payment records.

## Run
1. `cd server && npm install`
2. Copy `.env.example` to `.env`, set a strong JWT_SECRET, then `npm start`
3. `cd ../mobile && npm install`
4. Set `expo.extra.apiUrl` in `mobile/app.json` to your API URL.
5. `npx expo start`

Demo password: `Potters123!`
Demo accounts: student@potters.edu, parent@potters.edu, teacher@potters.edu, admin@potters.edu

## Android
`npx eas build --platform android --profile preview` = test APK
`npx eas build --platform android --profile production` = Play Store AAB

Before launch, replace demo credentials, deploy the API over HTTPS, use a production database/backups, add real push notifications and payment verification, configure privacy/terms, and review student-data requirements.
