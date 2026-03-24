<div align="center">

# 🛡️ AlertNet — Student Safety Mobile App

**A cross-platform mobile safety application designed to protect students in and around university campuses through real-time tracking, community-driven support, and instant emergency alerts.**

[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)](https://firebase.google.com/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Expo](https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev/)
[![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=google-maps&logoColor=white)](https://developers.google.com/maps)

</div>

---

## 📖 Overview

**AlertNet** is a cross-platform mobile safety application developed to address the rising crime rates affecting students at urban South African universities, particularly around the University of Johannesburg (UJ) campuses in Melville, Brixton, and Auckland Park.

Traditional personal safety measures are often reactive, expensive, or inadequate for students navigating complex urban environments. AlertNet fills this gap by combining **real-time emergency alerting**, **community-driven safety networks**, and **proactive crime zone awareness** into a single, accessible, and affordable application.

Built with **React Native**, **Firebase**, **Node.js**, and **Google APIs**, AlertNet delivers reliable, fast, and scalable performance across both Android and iOS — empowering students to move safer, smarter, and together.

> 🌍 Aligned with **UN Sustainable Development Goal 11** (Safe and Inclusive Communities) and the **Fourth Industrial Revolution (4IR)** framework.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🏠 **Home & Live Map** | Full-screen interactive map with real-time user locations, offline map download, and instant SOS access |
| 🎉 **Onboarding** | Welcoming walkthrough that introduces app features and guides new users through account creation |
| 🆘 **SOS Emergency Alert** | One-tap panic button that instantly notifies your safety circle with your live GPS location and a scannable QR code |
| 🚶 **Walk Partner System** | Connect with verified nearby users for safe, companioned journeys with live shared tracking |
| 👥 **People & Community** | Manage your safety circle, view community feeds, post local safety warnings, and message friends |
| 📞 **Emergency Helpline** | One-tap access to Police (10111), Ambulance (10177), and Campus Security with custom contact support |
| 🎙️ **Voice Activation** | Trigger SOS hands-free using a pre-configured panic passphrase |
| ⚠️ **High-Crime Zone Alerts** | Geofencing-powered notifications when entering known high-risk areas |

---

## 📱 Feature Showcase

### 🎉 Onboarding

AlertNet opens with a polished onboarding experience that introduces users to the app's core safety features before they sign up. The welcome flow highlights key capabilities and leads directly into the registration screen, where students sign up using their student email, phone number, and a secure password.

<div align="center">
  <img src="./screenshots/Onboarding.gif" alt="Onboarding" width="250"/>
</div>

---

### 🏠 Home Screen & Live Map

The Home screen is built around a **full-screen interactive map** displaying the user's current location and nearby points of interest. A prominently placed action bar at the bottom provides instant one-thumb access to all five core navigation tabs: Locator, Walk Me, People, Helpline, and SOS.

Additional home screen features include:
- 👤 **User profile** accessible from the top navigation bar
- 🔔 **Notifications icon** for real-time alerts and updates
- 📸 **Offline Map Download** — users can save a snapshot of the map for use when out of data or without a connection, allowing them to still navigate and find directions offline

<div align="center">
  <img src="./screenshots/Home.gif" alt="Home Screen" width="250"/>
</div>

---

### 🆘 SOS Emergency Alert

The SOS button is the core reactive safety feature of AlertNet. A single tap immediately broadcasts the user's live GPS coordinates to their entire safety circle and nearby app users. The SOS screen displays a **scannable QR code** containing the user's emergency contact information — allowing a bystander or security guard to access critical details even if the user is incapacitated.

The alert is deactivated when the user taps **"I'm Safe Now"**, sending a confirmation to all previously notified contacts.

<div align="center">
  <img src="./screenshots/SOS.gif" alt="SOS Emergency Alert" width="250"/>
</div>

---

### 🚶 Walk Partner System

The Walk Partner feature connects students who need a companion for a journey with verified, nearby users. A user initiates a request by specifying their destination and estimated duration. Once a partner accepts, a **time-limited shared tracking session** begins — both users see each other's live position, estimated arrival time, route overview, and have access to in-app messaging for pre-trip coordination. The session ends automatically upon safe arrival.

<div align="center">
  <img src="./screenshots/Walk.gif" alt="Walk Partner" width="250"/>
</div>

---

### 👥 People, Community & Safety Circle

The People screen is AlertNet's social safety hub, combining personal contact management with community-wide safety awareness:

- **My Contacts** — View your trusted safety circle with each contact's name, estimated location (e.g. APB Campus), online status, distance in kilometres, and live **battery percentage** so you always know if a contact is reachable
- **Messaging** — Send direct messages to friends within the app
- **Community Groups** — Emergency community group accounts where verified organisations share critical safety updates
- **Safety Feed** — A community-driven feed where users can **post about incidents in their area** to warn others in real time — turning every AlertNet user into a local safety reporter

<div align="center">
  <img src="./screenshots/People.gif" alt="People & Community" width="250"/>
</div>

---

### 📞 Emergency Helpline

The Helpline screen is a static, always-reliable resource for one-tap emergency calling — designed to work fast under pressure without needing to search for numbers. Pre-configured quick-dial contacts include:

- 🚔 **Police** — 10111
- 🚑 **Ambulance** — 10177
- 🏫 **Campus Security** — 011 559 2555

Users can also tap **+ Add** to store additional numbers such as family members or personal medical contacts.

<div align="center">
  <img src="./screenshots/Help.gif" alt="Emergency Helpline" width="250"/>
</div>

---

## 🛠️ Tech Stack

### Frontend

| Technology | Purpose |
|---|---|
| **React Native** | Cross-platform UI framework (single codebase for iOS & Android) |
| **JavaScript** | Core application logic |
| **Expo** | Device API access (biometrics, location, notifications) |
| **Kotlin / Swift** | Native extensions for background geofencing and voice recognition |

### Backend

| Technology | Purpose |
|---|---|
| **Node.js** | Primary backend — asynchronous, non-blocking real-time data handling |
| **Firebase Authentication** | Secure user registration, login, and session management |
| **Firebase Realtime Database** | Live GPS sync, alert status updates, and safety circle data |
| **SQL (Relational Layer)** | Structured data — audit logs, historical records, reporting |

### APIs & Services

| Service | Purpose |
|---|---|
| **Google Maps API** | Interactive maps and location visualisation |
| **Google Geofencing API** | High-crime zone boundary detection |
| **Google Geocoding & Directions API** | Address lookup and safe route suggestions |
| **Firebase Cloud Messaging (FCM)** | Reliable push notifications to emergency contacts |
| **YouTube API** | Linked safety resource videos (keeps app lightweight) |
| **Resend** | Automated email notifications to emergency contacts |

---

## 🧪 Testing & Performance

### Testing Methodology

AlertNet was validated through a three-phase testing process:

- **Unit Testing** — Individual module verification including SOS activation, Walk Partner request flow, and contact synchronisation
- **Integration Testing** — Verified seamless communication between the app, Firebase, and Google APIs (geofencing and location tracking)
- **User Acceptance Testing (UAT)** — Conducted with university students in simulated emergency scenarios to assess real-world performance and usability

### Performance Metrics

| Metric | Result |
|---|---|
| ⚡ Average SOS alert response time | **2.7 seconds** |
| 📍 Location tracking accuracy | **99%** |
| 🔔 Notification delivery success rate | **98%** |
| 🟢 System uptime target | **> 99%** |

### Key Test Results

| Test Case | Status |
|---|---|
| SOS Activation → Alert delivered to all contacts with live location | ✅ Passed |
| Walk Partner Request → Connection established successfully | ✅ Passed |
| Emergency Notification → Correct location delivered to contact | ✅ Passed |
| High-Crime Zone Alert → Notification triggered with route suggestion | ✅ Passed |
| Voice Activation → SOS triggered in quiet environment | ⚠️ Minor issues in noisy environments |

### Bug Fixes During Development

- **Delayed Notifications** → Resolved by integrating Firebase Cloud Messaging for faster push delivery
- **Location Lag** → Improved GPS accuracy through background caching optimisation
- **Voice Feature False Negatives** → Adjusted recognition sensitivity thresholds

---

## 👨‍💻 My Contribution

As a core member of the AlertNet development team, my contributions spanned across the full development lifecycle:

- **UI/UX Design** — Designed intuitive, stress-responsive interfaces with a focus on minimal cognitive load during emergencies. Implemented the five-tab bottom navigation system for one-thumb accessibility
- **Firebase Integration** — Configured Firebase Authentication for secure user management and implemented real-time data pipelines for location tracking and alert delivery
- **API Integration** — Integrated Google Maps, Geofencing, Geocoding, and Directions APIs to power location-based features and crime zone alerts
- **SOS Module Development** — Built the core emergency alert flow including GPS capture, contact notification, QR code generation, and the safe deactivation sequence
- **Walk Partner Algorithm** — Contributed to the proximity-based matching logic and time-limited shared tracking session implementation
- **Community Feed** — Developed the safety feed and community group features enabling users to post local warnings and stay informed
- **Testing** — Participated in unit testing, integration testing, and UAT sessions to identify and resolve usability and performance issues

---

## 🤝 Team Experience

AlertNet was developed using an **Agile (Scrum)** methodology across a cross-functional team of 7 members from the Information Systems programme, working in close collaboration with a Marketing (MM) student team.

**What made this team experience valuable:**

- 🔄 **Iterative Development** — Working in structured sprints allowed us to incorporate user feedback continuously and refine features before finalisation
- 🤝 **Cross-Functional Collaboration** — Regular communication between the technical (AIS) and marketing (MM) teams ensured the product was both technically sound and user-centered
- 🧩 **Problem-Solving Under Constraints** — With limited testing resources during an active academic term, we adapted by conducting simulated user journeys and recording usability data
- 🌍 **Real-World Impact Mindset** — Every decision was grounded in solving a genuine safety problem affecting real students in our community

---

## 🔮 Future Improvements

| Improvement | Description |
|---|---|
| 📵 **Offline SOS (SMS Fallback)** | SMS-based alert delivery for areas with no internet connectivity |
| 🚔 **Authority Integration** | Partner with SAPS and campus security for real-time response and verified data sharing |
| 🎙️ **Voice Feature Enhancement** | Improve passphrase recognition accuracy in high-noise environments |
| 🔋 **Battery Optimisation** | Implement adaptive GPS refresh rates to reduce power consumption |
| 🌐 **Multilingual Support** | Add isiZulu, Afrikaans, and Sesotho for broader accessibility |
| ♿ **Accessibility Features** | Voice feedback and screen reader support for visually impaired users |
| 🏫 **Campus Pilot Deployment** | Structured pilot testing within UJ campuses before public release |

---

## 🎯 Conclusion

AlertNet demonstrates that mobile technology, when thoughtfully designed, can serve as a powerful equaliser for community safety. By combining proactive alerts, community-driven features, and reactive emergency tools into a single, affordable, and accessible application, AlertNet addresses a genuine and urgent need for South African students navigating high-risk urban environments.

The project proved that real-world problems can be tackled with well-chosen technology, collaborative teamwork, and a user-first design philosophy. With further development — particularly offline capability, authority integration, and broader deployment — AlertNet has strong potential to become a meaningful safety infrastructure tool across South Africa and beyond.

---

## 👥 Team

| Name | Student Number |
|---|---|
| Mpilonle Radebe | 222087503 |
| Kevin Serakalala | 223088123 |
| Thembinkosi Madiba | 222223279 |
| Siphephile Mtshali | 223125261 |
| Okuhle Mgudlwa | 222073209 |
| Musa Buthelezi | 222023907 |
| Nathi Gumede | 222021634 |

**Supervisor:** Thamie Mhlanga  
**Module:** Information System 3B — 250PRO001  
**Institution:** University of Johannesburg

---

## 📄 License

This project was developed as an academic submission. All rights reserved by the AlertNet development team © 2025.

---

<div align="center">

**Built with ❤️ to make campuses safer — one alert at a time.**

</div>
