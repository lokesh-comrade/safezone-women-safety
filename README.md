# Real-Time Women Safety Monitoring and Emergency Response Platform

A hybrid safety platform integrating responsive web runtime interfaces with native Android telephony and sensor hardware.

## 📱 Download Application
- 📥 **[Download SafeZone-v1.0.apk](SafeZone-v1.0.apk)**

---

## 🚀 Key Features
- **Zero-Cost Background Telephony:** Employs native `SmsManager` and `Intent.ACTION_CALL` over cellular basebands, bypassing commercial SMS gateways.
- **Continuous Path Telemetry:** Live kinematic tracking using `navigator.geolocation.watchPosition` streamed directly to Google Cloud Firestore.
- **Multi-Modal Distress Triggers:**
  - 1-Tap SOS dispatch.
  - 5-Shake inertial filter with temporal throttling ($\Delta t \ge 100$ ms, $\Delta a > 20$ m/s²).
  - Background voice keyword recognition ("help", "emergency", "bachao").
  - Steganographic stealth calculator interface (PIN: `9999=`).
- **Emergency Resolution:** One-touch "I Am Safe Here" state clearing with automated guardian notification.

## ⚠️ Installation Instructions (Android 13/14+)
1. Download and install `SafeZone-v1.0.apk`.
2. When prompted by Google Play Protect, select **More details ➔ Install anyway**.
3. If background SMS/Calling is restricted by Android OS:
   - Go to phone **Settings ➔ Apps ➔ SafeZone**.
   - Tap the three dots (**⋮**) in the top right corner ➔ **Allow restricted settings**.
   - Open **Permissions** and enable **SMS**, **Phone**, and **Location**.