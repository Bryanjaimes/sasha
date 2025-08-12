# SASHA — Such A Smart Healthcare Assistant

**Tagline:** A voice-first, sensor-aware health companion that generates a personalized UI and detection plan, then runs analysis **on-device** in seconds.

> ⚠️ **Safety:** SASHA is an educational/wellness tool — **not a medical device** and **not for emergency use**. If you’re experiencing an emergency, call local emergency services.

---

## Mission

Enable anyone, anywhere to use a smartphone **website/app** for **early insights** and **ongoing guidance** about their health — **private**, **fast**, and **explainable**.

We commit to:
- **On-device AI** whenever possible (privacy & latency)
- **Explainability** (heatmaps, audio annotations) with **confidence** and **calibration**
- **Clinically meaningful metrics** (sensitivity, specificity, ECE)
- **Transparent model cards** and known limitations
- A clear path toward real-world validation — starting with **eye** and **heart** health

---

## What SASHA Does (MVP)

- **Voice → Intent → Plan**  
  Natural request (e.g., “my vision is blurry,” “I hear a murmur”) becomes a structured **detection plan**.

- **Generative UI**  
  SwiftUI renders screen with personalized charts, sensors and displays/animations 

- **Sensors when available**  
  Camera (retina/skin), microphone (heart/lung/cough), motion (gait/tremor), depth/LiDAR (wound/edema size), and PPG via camera (HR/HRV).

- **On-device models**  
  Quantized Core ML models; **Grad-CAM** for images, segment highlights for audio.

- **Safety & next steps**  
  QC checks, confidence, red-flag escalation, and educational info with citations. *Not for diagnosis.*

---

## Architecture (high level)

