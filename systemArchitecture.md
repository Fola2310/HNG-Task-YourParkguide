YourParkguide is a mobile-first application that helps users save and locate their parked cars using GPS and AR navigation. The system is designed to be lightweight, scalable, and user-friendly.

Frontend

Technology: React Native

Purpose: Cross-platform mobile app (iOS & Android)

Key Components:

•	Save Parking button

•	Map view with AR overlay

•	Reminder notifications

•	Parking history screen
 
Backend

Technology: Node.js with Express

Purpose: API layer for handling requests

Key Components:

•	User authentication

•	Parking location storage

•	Reminder scheduling

•	Data sync with frontend

Database

Technology: Firebase Firestore (NoSQL)

Purpose: Store user data and parking history

Data Models:

•	User profile

•	Parking location (GPS coordinates, timestamp)

•	Reminder settings

Communication Flow

1. User saves parking location: frontend sends GPS data to backend.

2. Backend stores data in Firebase.

3. Reminder service triggers notifications via Firebase Cloud Messaging.

4. User requests navigation: frontend fetches data from backend; displays AR route.

 Technical Feasibility

•	Cross-platform: React Native ensures single codebase for iOS and Android.

•	Scalability: Firebase handles real-time data and push notifications.

•	Reliability: Google Maps API + ARCore provide accurate navigation.

•	Security: Firebase Authentication for secure login and data protection.
