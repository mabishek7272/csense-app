# CSense Mobile Applications

This repository contains the mobile applications for **CSense / Apti**:

1. [**`apti-demo/`**](./apti-demo/) — **Apti Mobile Demo App ("Closed Circuit Assurance")**
   - On-device AI vision demo featuring:
     - **Register a Face**: Session-based face enrollment for identity matching.
     - **Try a Model**: Live camera and photo detection modes (Objects, Phone, Fire & smoke).
     - **Live Monitoring**: Continuous camera monitoring with detection heuristics, unknown face alerts, and local notifications.
     - **History**: Local-to-device detection history with severity filters (`Low`, `Medium`, `High`) and thumbnail review.
   - Built with Expo, React Native, and Expo Camera.

2. [**`csense-mobile/`**](./csense-mobile/) — **CSense Tenant Mobile App**
   - Full multi-tenant surveillance and security management application featuring:
     - **Multi-Brand Theming**: Supports CSense, Apti, 3RDi, and eAIgleye brand variants.
     - **Live Surveillance**: HLS video camera streaming for monitored sites.
     - **Alerts & Incidents**: Push notifications and real-time WebSocket alert feed.
     - **Authentication & Security**: Multi-factor authentication (MFA / TOTP) and secure token storage.
   - Built with Expo Router, React Native, and expo-video.

---

## Getting Started

### Prerequisites
- Node.js 18+ and npm
- Expo Go app on your physical iOS/Android device, or Xcode / Android Studio simulator

---

### Running Apti Mobile Demo (`apti-demo`)

```bash
cd apti-demo
npm install
npx expo start
```
Scan the QR code with the Expo Go app or press `i` for iOS simulator / `a` for Android emulator.

---

### Running CSense Tenant Mobile App (`csense-mobile`)

```bash
cd csense-mobile
npm install
npx expo start
```
Scan the QR code with Expo Go or run on your simulator.
