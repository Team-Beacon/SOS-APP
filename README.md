# 🚨 Beacon: The Proximity SOS System

> **"Because in an emergency, 10 minutes is too long to wait."**

![Beacon Logo](https://via.placeholder.com/150)
![WhatsApp Image 2025-12-24 at 5 08 53 PM](https://github.com/user-attachments/assets/d33468a6-6cea-4f80-bc70-0390011e237b)


## 👋 Why We Built Beacon
We realized that in India, the biggest problem during an emergency isn't that people don't want to help—it's that they don't know help is needed. 

Most SOS apps rely on the Internet. But what if you are in a basement? Or a remote highway with no 4G? 
**Beacon** is our answer to that. We stripped away the dependency on data servers and built a system that uses the most basic, reliable technology: **SMS and GPS**.

If you have a phone signal, you have a lifeline.

## 🚀 What Makes It Special?

* **No Internet? No Problem:** Unlike WhatsApp or Uber, Beacon works purely on GSM. It sends coordinates directly via SMS.
* **The "Panic Slider":** Typing during a crisis is impossible. We created a unique **Threat Slider** UI. Just slide to "Medium" or "High" to tell responders if it's a medical issue or a physical threat.
* **One-Tap Accident Mode:** A dedicated button for instant medical alerts.
* **Real-Time Tracking:** We don't just send text; we send a direct **Google Maps Link** precise to your current location (using High-Accuracy GPS).

## 🛠️ How We Built It (Tech Stack)
We wanted the app to be lightweight but powerful, so we used a **Hybrid Approach**:

* **The Brain (Backend):** Written in **Java (Android Native)**. This handles the tough stuff—waking up the GPS sensor, managing permissions, and sending background SMS.
* **The Face (Frontend):** Built using **HTML5, CSS3, & JavaScript**. This allowed us to design a fluid, animated interface that feels modern and responsive.
* **The Bridge:** We used Android's `WebView` to let JavaScript talk to Java code securely.

## 📱 How to Test It
1.  Clone this repo.
2.  Open in Android Studio.
3.  **Important:** When you run the app, please grant **SMS** and **Location** permissions.
4.  Add your friend's number in the code (we hardcoded ours for the hackathon demo!).
5.  Slide the SOS button and watch the magic happen.

## 🔮 Future Roadmap
This is just **Version 1.0**. In the future, we plan to:
* Add a mesh network feature (using Bluetooth) for areas with NO signal.
* Integrate directly with local police dispatch APIs.
* Add "Safe Zones" geofencing.

---
### 👨‍💻 Built with ❤️ by Team Beacon
* **DEEPENDRA SINGH SOLANKI** 
* **DIVYANSH CHAUDHARY** 
* **GURUTWA SINGH SHAKYA** 
* **SOMIL JAIN**

*Submitted for [DevSprint By GDGoc]*
