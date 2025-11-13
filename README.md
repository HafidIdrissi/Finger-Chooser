# Finger Chooser — Multi-Touch Random Picker App 🎉

Finger Chooser is a lightweight mobile application that implements **real-time multi-touch detection** to randomly select a single participant among multiple users touching the screen simultaneously.  
Built with **React Native + Expo**, the app focuses on performance, smooth animations, and a clean, customizable user interface.

---

## 🧩 Core Features

### 🔹 Multi-touch Input Handling
- Tracks any number of simultaneous touch points  
- Normalized event handling for consistent behavior across devices  
- Robust touch lifecycle management (press → move → release)  

### 🔹 Random Selection Engine
- Deterministic pseudo-random generator for unbiased results  
- Stable mapping between finger IDs and bubble styles  
- Instant visual + haptic feedback  

### 🔹 Flexible Customization
- Bubble styles: **colors**, **numbers**, **shapes**, **names**  
- Custom player name entry  
- Background themes (**Sunset**, **Ocean**, **Aurora**, …)  
- Modular UI allowing easy extension of styles and effects  

### 🔹 UX Feedback Layer
- **expo-haptics** for tactile feedback  
- Confetti animation using **react-native-reanimated**  
- Smooth transitions & state-driven rendering  

---

## 📱 Screenshots

| Main Screen | Bubble Style | Players | Background Picker |
|------------|--------------|---------|--------------------|
| ![](./assets/screenshots/main-screen.png) | ![](./assets/screenshots/bubbles-style.png) | ![](./assets/screenshots/add-players.png) | ![](./assets/screenshots/background-picker.png) |

---

## ⚙️ Technical Overview

### **Architecture**
- Component-driven UI  
- Centralized state with React Hooks  
- Low input latency + predictable touch handling  
- Minimal dependencies for reliability  
- Clean folder structure for maintainability  

### **Key Libraries**
| Library | Purpose |
|--------|---------|
| **Expo** | Build system, device APIs |
| **react-native-reanimated** | GPU-accelerated animations |
| **expo-haptics** | Haptic feedback |
| **expo-linear-gradient** | Background styling |
| **EAS Build** | Generate APK & AAB |

### **Performance Considerations**
- Debounced touch updates to avoid render floods  
- GPU-accelerated animations via Reanimated  
- Memoized components to reduce re-renders  
- Optimized static assets (PNG compression + caching)  

---

## 🚀 Build & Installation

### 📥 Download (Android APK)
Available via Expo EAS:  
https://expo.dev/accounts/hafez_id/projects/finger-chooser/builds/68b5f23e-f773-4e88-9c2a-beef882d4417
