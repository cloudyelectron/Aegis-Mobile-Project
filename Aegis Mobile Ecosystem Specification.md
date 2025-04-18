# Aegis Mobile Ecosystem Specification

## 🌐 Brand Identity
**Aegis Mobile** is a rugged smartphone ecosystem tailored for tactical, survival, and field operations. Built on four pillars: **Durability**, **Modularity**, **Privacy**, and **Field-Readiness**.

## 📦 Product Lineup

| Model     | Frame Material     | Weight (g) | Key Audience            |
|-----------|--------------------|------------|--------------------------|
| Lite      | Polycarbonate      | ~400       | Civilian users, light-duty |
| Core      | Stainless Steel    | ~800       | Veterans, rugged nostalgia |
| Pro       | Magnesium Alloy    | 500–600    | Military/law enforcement |
| Sentinel  | Titanium           | ~600       | Special ops, high-risk    |
| Guardian  | Mag/Ti Custom      | 500–700    | Elite, customized mission |


## 🧱 Core Design Features (All Models)
- **Aegis OmniPort™**: Universal top-mounted modular port
- **Standard Sensor Set**: Accelerometer, Gyro, Proximity, Light, Compass
- **High-dB Speaker** (>100dB) with honeycomb grill layout
- **Noise-cancelling Microphones**
- **Front/Rear Aegis ShieldCam**: LED shield frame around camera
- **Reinforced Rear Strap Loop**

## 🔘 Button Layout

### Left Side:
- Top: Power Button
- Upper Mid: Primary (priority) PTT Button
- Mid: Volume Rocker

### Right Side:
- Top: Action Button (Customizable)
- Upper Mid: Secondary (non-priority) PTT Button
- Lower Mid (Pro/Sentinel+): 2nd OmniPort

### Front:
- Bottom: Android 3-Button Navigation

**PTT Logic**: If both PTTs are pressed simultaneously, the priority (left-side) PTT takes effect.


## 💡 Custom Action Button Logic
Configurable with multiple interactions:
- Single Press: Custom function
- Double Tap: Alternate function
- Long Press: Activate Stealth Mode (silent, vibration/mute, optional kill switch)
- 5x Rapid Tap: Emergency preset or full shutdown


## 🔦 Light / Camera Capabilities
| Model     | Flashlight Output | IR/Thermal | Rear Camera | Front Camera |
|-----------|-------------------|------------|-------------|--------------|
| Lite      | ~200lm            | No         | 20MP        | 8MP          |
| Core      | ~300lm            | No         | 20MP        | 8MP          |
| Pro       | Up to 800lm       | Yes        | 50MP        | 12MP          |
| Sentinel  | 800lm + IR        | Yes   (thermal) | Enhanced    | Enhanced     |
| Guardian  | Custom            | Yes   (thermal) | Enhanced+   | Enhanced+    |

## 📡 Communication & Ports
- **LoRa**: From Pro and up (Lite/Core support optional via OmniPort antennas)
- **PTT**: Hardware-based, dual-button configuration
- **Optional Satellite & RF Modules**: Attach via OmniPort
- **Offline short-range comms** (Lite/Core via modular antennas)

## 🔋 Battery & Thermal Design
- Flashlights, IR modules, and comms are optimized for 3+ hour operation under continuous load (Pro+)
- Large surface LED panels for better heat distribution
- Magnesium & Titanium models enhance passive cooling

## 🧤 UX Enhancements
- **Glove Mode** for touchscreen
- **Physical Android Navigation** for field usability
- **Secure Strap System**:
  - Lite: Basic wrist strap with metal reinforcement
  - Core+: 1-point tactical sling with fast-release buckle

## ⚙️ Expandability
- Upper OmniPort for camera/satcom/antenna
- Right-lower OmniPort for power, sensor, mount (Pro/Sentinel+)
- Modules can be simultaneously mounted (e.g., comm + power)
- Docking system optional via battery cover (reliable, rugged)

## 🔒 Security Features
- Hardware Kill Switches (Radio, Camera, Mic)
- Full Stealth Mode (no signals, LED off, vibrate/sound disabled)
- Encrypted storage (via Aegis OS)

---

## 🌌 Future Expansion Ideas
- Satellite beacon ping mode
- Onboard GPS logging for journaling/outdoor use
- Gesture-based activation (shake to turn on flashlight, etc.)

---

**Aegis Mobile**: "In a uncontrolled world, Shield is the language."
