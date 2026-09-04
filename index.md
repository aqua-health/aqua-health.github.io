# Privacy Policy for AQUA

**Effective Date: September 2026**

AQUA ("the App") is developed by Manman Zhang as an offline-first metabolic telemetry engine. We believe your physiological data belongs exclusively to you. 

This Privacy Policy explains how we handle your data when you use AQUA.

### 1. On-Device AI & One-Time Model Download
AQUA is built around a Small Language Model (SLM) that runs entirely locally on your iPhone. To enable this offline capability, the App requires a one-time internet connection upon initial launch to download the necessary open-source model weights. 
* **Strictly One-Way Fetch:** This network request is used exclusively to download the model files. **We do not collect, transmit, store, or share your personal data, health metrics, or usage logs to any external servers during this download or at any other time.** Once the model is mounted, AQUA's core engine operates 100% offline.

### 2. Apple HealthKit Integration
AQUA requests read and write access to specific Apple Health data (such as Blood Glucose, Heart Rate Variability, Resting Heart Rate, Sleep Analysis, and Active Energy) via the HealthKit framework. 
*   **How we use it:** We use this data strictly to compute local metabolic residual trajectories and render your personalized dashboard. 
*   **Data Protection:** Your HealthKit data never leaves your device. We do not sell your HealthKit data to advertising platforms, data brokers, or information resellers. AQUA fully complies with Apple's HealthKit data and privacy guidelines.

### 3. Microphone & Speech Recognition
AQUA requests Microphone and Speech Recognition access to allow hands-free logging of your physiological context (e.g., meals or stress events).
*   Audio is processed using Apple's native, on-device frameworks. We do not upload your voice recordings to any third-party APIs or external cloud services.

### 4. Third-Party Services
Because AQUA operates primarily offline after the initial setup, it does not integrate with third-party analytics trackers, crash reporters, or advertising networks. 

### 5. Contact Us
If you have any questions or concerns about this Privacy Policy or your data, please contact us at:
**Email:** aqua.health.feedback@gmail.com