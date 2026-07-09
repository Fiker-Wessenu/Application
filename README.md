# Application Backend: Group B1: Infrastructure & Setup (one-time, early work)

Firebase project setup (Auth, Firestore, Storage, FCM enabled)
SHA-1/SHA-256 fingerprint registration for Android phone auth
Firebase Emulator Suite setup for local rules testing
Cost/usage monitoring setup (Firestore reads/writes budget alerts)

Group B2: Data Model & Security Rules

Firestore data model design (users, chats, messages, groups)
Firestore security rules (users, chats, messages, groups)
Storage security rules (chat media, profile photos)
Firestore indexes (composite indexes for chat queries)
Presence system setup (Realtime Database, separate from Firestore)

Group B3: Cloud Functions & Notifications

Cloud Function: addGroupMember / removeGroupMember
Cloud Function: fan-out logic for FCM notifications on new messages
Cloud Function: cleanup/maintenance (orphaned Storage files on message deletion)



backend folder: https://github.com/Fiker-Wessenu/Orbit

Frontend folder1: https://github.com/Mahiii43m/Telegram-clone
