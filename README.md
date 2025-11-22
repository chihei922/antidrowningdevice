# 💧 Intelligent Anti-Drowning Device

An automated drowning detection and rescue system combining physiological monitoring with computer vision technology.

## 🎯 Project Overview

Drowning claims 236,000 lives annually (WHO), ranking as the third leading cause of unintentional injury death worldwide. Traditional life jackets are often discarded due to bulkiness, while manual devices fail in panic situations. Our solution addresses these limitations through intelligent, automated detection and response.

## 🔧 Technical Implementation

### Hardware Architecture
- **Wristband Design**: Compact wearable with integrated sensors
- **Heart Rate Monitoring**: Real-time BPM tracking using Arduino-based sensors
- **Trigger Mechanism**: Activated when heart rate differential exceeds 15 BPM within 2 seconds
- **Alert System**: LED illumination + speaker alarms for rapid localization
- **Inflation System**: Chemical reaction-based airbag deployment

### Chemical Inflation
3NaHCO₃ + C₆H₈O₇ → C₆H₅Na₃O₇ + 3CO₂ + 3H₂O
- **Components**: Baking soda (6.5g) + Citric acid (10%, 50g)
- **Output**: Non-toxic CO₂ gas for buoyancy
- **Safety**: Environmentally friendly byproducts

### AI Vision System
- **Resolution**: 640×480 pixel processing
- **Detection Class**: "Personinwater" identification
- **Confidence Threshold**: >57% for secondary verification
- **Real-time Performance**: Continuous monitoring capability

## 🚀 Key Features

### Dual-Layer Detection
1. **Primary**: Physiological (heart rate anomalies)
2. **Secondary**: Visual (AI computer vision confirmation)

### Automated Response Protocol
- Chemical airbag inflation
- Visual/audible alerts activation
- "Detect within 10s, rescue within 20s" target

## 💡 Innovations

- **Fully Automated**: No manual activation required
- **Minimally Invasive**: Compact design without mobility restriction
- **Dual Verification**: Reduces false positives through multi-sensor fusion
- **Hygienic Inflation**: Chemical method vs. compressed gas alternatives

## 📈 Future Development

- [ ] GPS integration with privacy protection
- [ ] Enhanced detection algorithms with multiple parameters
- [ ] Improved chemical packaging (single-use pods)
- [ ] Expanded AI training datasets for diverse environments
- [ ] Multi-camera synchronization for area coverage

## 🌍 Application Value

Particularly relevant with post-pandemic tourism recovery, where water activities see increased participation. Addresses lifeguard limitations and low life jacket compliance through intelligent, wearable protection.

---

*Building safer water experiences through technology innovation.*
