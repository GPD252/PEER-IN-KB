# 🔐 Private P2P End-to-End Encrypted Messenger (2025)

Yeh ek fully private aur serverless messenger hai jo **WebRTC** aur **LocalStorage** par chalta hai. Iska code GitHub par private rakha gaya hai taaki security bani rahe.

## 🚀 Key Features
- **Unlimited Reach:** Duniya mein kahin bhi kisi se bhi connect karein.
- **Ultra-Low Bandwidth:** Session start karne ke liye sirf 1-2 KB data exchange (Handshake) ki zaroorat hoti hai.
- **ID-Based Persistence:** Apni **Unique ID** se login karein aur purani chats wapas payein.
- **Zero Server Lag:** Data kisi server par nahi jata, direct P2P (Peer-to-Peer) transfer hota hai.
- **Privacy:** No phone number, no email, no tracking.

## 🛠 Setup & Usage
1. **Login:** Website open karke apni ek Unique ID banayein ya purani ID enter karein.
2. **Handshake (The 1KB Step):**
   - "Generate Offer" par click karein aur code copy karke apne dost ko bhejien.
   - Dost ka "Answer Code" paste karein aur **Connect** dabayein.
3. **Chatting:** Connection banne ke baad internet ki zaroorat minimal ho jati hai. Saari chats aapke browser mein save rahengi.

## 💾 Data Storage
Aapka chat data browser ke `IndexedDB / LocalStorage` mein aapki **Unique ID** ke saath encrypted format mein save hota hai. 
- **Zaruri:** Agar aap browser cache delete karenge, toh us ID ka data delete ho sakta hai. Isliye apni ID hamesha sambhaal kar rakhein.

## 🛡 Security & Encryption
- **Media:** DTLS/SRTP Encryption (WebRTC Standard).
- **Text:** End-to-End Encrypted (E2EE).
- **Hosting:** Private repository on GitHub, deployed via Vercel for maximum security.

---
*Created for secure and private communication in 2025.*
