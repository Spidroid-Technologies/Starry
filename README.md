# Starry 🌟  
*A Social Platform for Authentic Connection & User Empowerment*  

<img src="/assets/ic_logo.jpg" width="100%" alt="Starry App Banner">  

![Android SDK](https://img.shields.io/badge/Android_SDK-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Material Design](https://img.shields.io/badge/Material_Design_3-757575?style=for-the-badge&logo=material-design&logoColor=white)

---

## Why Starry? ❤️  
In an era of algorithm-driven feeds and data exploitation, Starry reimagines social networking with:  

**✨ Chronological Transparency**  
See posts exactly as they're shared — no hidden sorting or engagement manipulation.  

**🔒 Privacy by Design**  
Your data stays yours. No selling personal information or cross-app tracking.  

**🎨 Creative Expression**  
Text, images, and rich media in customizable post formats. Stylish, personal profiles.  

**🌐 Decentralization Roadmap**  
User-owned communities and distributed architecture on the way (2024).  

**💸 Creator Economy**  
Planned token rewards and microtipping system (Q3 2024 target).  

---

## Features 🚀  
- Pure chronological feed  
- Granular post privacy controls  
- Rich media posts (images/videos/links)  
- Real-time Firebase chat  
- Profile verification system  
- Dark/Light theme toggle  
- Cross-device sync  
- PWA-ready structure  

---

## Tech Stack ⚙️  
**Core Technologies**  
- Android SDK (Java)  
- Firebase Authentication  
- Firebase Realtime Database  
- Firebase Storage  
- Firebase Cloud Messaging  

**UI/UX**  
- Material Design 3  
- Dark/Light Mode Support  
- Adaptive Layouts  

**Architecture**  
- MVVM Pattern  
- Repository Pattern  
- LiveData Observables  

**Build Tools**  
- Android Studio Giraffe+  
- Gradle (Groovy DSL)  
- ProGuard/R8 Optimization  
- GitHub Actions CI/CD  

---

## Getting Started 💠  
**Prerequisites**  
- Android Studio Giraffe+  
- Java JDK 17  
- Android SDK 33+  
- Firebase project  

**Installation**  
1. Clone the repository:  
```bash
git clone https://github.com/Spidroid-Technologies/Starry.git
```
2. **Firebase Configuration**  
   a. Obtain `google-services.json`:  
      1. Create/access your Firebase project at [console.firebase.google.com](https://console.firebase.google.com/)  
      2. Navigate: *Project Settings > Your Apps > Add App > Android*  
      3. Enter package name: `com.spidroid.starry`  
      4. Register app and download config file  

   b. File Placement:  
      ```text
      📁 Project Root/
        └── 📁 app/
            └── google-services.json  <-- Place here
      ```

   c. Validate Integration:  
      - Verify file exists in correct location  
      - Ensure these Gradle dependencies exist:  
        ```gradle
        // Project-level build.gradle
        classpath 'com.google.gms:google-services:4.3.15'

        // App-level build.gradle (bottom of file)
        apply plugin: 'com.google.gms.google-services'
        ```

3. **Build & Run**  
   ```bash
   # Sync Gradle dependencies
   ./gradlew clean build --refresh-dependencies

   # Install debug build
   ./gradlew installDebug
   ```

4. **Post-Install Verification**  
   - Check Android Monitor for "Firebase initialization successful" log  
   - Test authentication flow in app  
   - Verify Realtime Database writes in Firebase console


## Legal

This project, **Starry**, is the proprietary software of [Spidroid Technologies Inc.](https://spidroid.com) and is protected under international copyright and intellectual property laws.

**All Rights Reserved.** Unauthorized use, modification, redistribution, or reverse-engineering is strictly prohibited.

- [License](./LICENSE)
- [Terms of Use](./TERMS.md)
- [Privacy Policy](./PRIVACY.md)
- [Contributor License Agreement (CLA)](./CLA.md)
