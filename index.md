<div align="center">
  <img src="assets/logo.png" width="96" height="96" alt="AQUA Logo" style="border-radius: 20px; margin-bottom: 12px;" />
  <h1>Privacy Policy for AQUA</h1>
  <p><strong>Effective Date:</strong> September 2026<br>
  <strong>Engine Architecture:</strong> v2.0 Deterministic Kinetic Engine</p>
</div>

---

AQUA (“the App”) is engineered by Manman Zhang as an entirely offline, deterministic metabolic telemetry engine. The system operates under the principle that physiological metrics belong exclusively to the individual and should never leave the local device.

This Privacy Policy outlines how your data is handled strictly on-device within AQUA v2.0.

---

### 1. 100% Offline & Deterministic Mathematical Architecture
AQUA is built without remote cloud dependencies, external relays, or neural network downloads:
- **Zero Outbound Network Requests:** The App does not ping external servers, upload telemetry, or communicate across the internet during setup or regular operation.
- **No User Accounts:** AQUA requires no sign-up, email verification, cloud profiling, or tracking credentials.
- **Deterministic Kinetic Simulation:** All postprandial glucose curves, digital twin calibrations, and morning readiness metrics are solved locally using two-compartment differential equations and online Bayesian parameter updates running in native Swift. No artificial intelligence models, cloud APIs, or external weights are utilized.

---

### 2. Apple HealthKit Integration (Strictly Read-Only)
AQUA requests explicit **read-only** authorization via the Apple HealthKit framework for the following physiological markers:
- Blood Glucose
- Heart Rate Variability (SDNN)
- Resting Heart Rate
- Sleep Analysis intervals
- Active Energy Burned (Workouts)

**Purpose of Telemetry:**  
This data is fetched strictly to establish personal baseline parameters and project short-term postprandial metabolic responses locally. AQUA never writes to or modifies your Apple HealthKit records.

**Apple HealthKit Compliance & Safeguards (Guideline 5.1.1(v)):**
- **Strictly Sandboxed:** Telemetry from HealthKit is processed in volatile device memory and persisted only in your local SwiftData database.
- **No Advertising or Commercial Data Mining:** In accordance with Apple Developer Program Guidelines, AQUA will **never** sell, license, transmit, or disclose HealthKit data to advertising platforms, data brokers, or information resellers.
- **No Behavioral Profiling:** Your physiological information will never be utilized for advertising targeting, marketing campaigns, or behavioral tracking.

---

### 3. Local Persistence via Encrypted SwiftData
Historical records—including morning readiness briefs, food archetype sessions, and Bayesian calibration variance—are stored entirely within the application’s isolated local **SwiftData** sandbox on your iPhone. 

The developer maintains no remote servers, databases, or access keys capable of retrieving your stored records.

---

### 4. Background Processing & Local Notifications
AQUA leverages iOS native background execution frameworks (`BGProcessingTaskScheduler`) and local notifications (`UNUserNotificationCenter`):
- **On-Device Triggers:** Spike attribution alerts and morning baseline notifications are scheduled, evaluated, and displayed entirely by iOS locally.
- **No APNs Relays:** The App does not connect to Apple Push Notification service (APNs) servers or third-party notification gateways.
- **Background Integrity:** Silent background evaluations operate strictly within iOS hardware-budgeted processing windows without leaking internal state.

---

### 5. Zero Third-Party Trackers & SDKs
AQUA contains **zero** third-party software development kits (SDKs), advertising libraries, analytics trackers, or crash monitoring frameworks (e.g., Firebase, Meta SDK, Adjust, Mixpanel). Your device execution trace remains entirely unmonitored.

---

### 6. User Control & Absolute Data Deletion
- **Revoking Permissions:** You can review or revoke AQUA’s HealthKit access at any moment via iOS **Settings > Health > Data Access & Devices > Aqua**.
- **Data Erasure:** You can clear calibration events and logs inside the App. Deleting the AQUA application from your device permanently and irreversibly purges the local SwiftData database and all historical telemetry models.

---

### 7. Non-Medical Wellness Disclaimer (Guideline 1.4.1)
**AQUA is an athletic awareness and lifestyle optimization tool. It is NOT a medical device and is NOT intended for clinical diagnosis, treatment, mitigation, cure, or prevention of any disease or condition (such as Diabetes, Insulin Resistance, or Hypoglycemia).**

All kinetic trajectory models, parameter estimations, and morning readiness evaluations are computational simulations provided solely for fitness and lifestyle reference. 
- Never use AQUA to calculate or alter insulin dosages, adjust medical treatments, or replace formal medical oversight.
- Always consult a qualified physician or healthcare professional before making clinical decisions or modifying your nutritional and medical routines.

---

### 8. Contact Information
For questions or architectural inquiries regarding AQUA’s local-first privacy framework, please reach out to:

**Developer:** Manman Zhang  
**Email:** aqua.health.feedback@gmail.com  
**Website:** [https://aqua-health.github.io/](https://aqua-health.github.io/)
