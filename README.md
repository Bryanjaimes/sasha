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

## What SASHA Does (Phase 1: Medical Imaging and AI Diagnosis)

The first phase of SASHA focuses on **medical imaging** and **AI-assisted diagnosis**, starting with eye health. The initial project involves building an AI model to assist doctors in diagnosing eye conditions using advanced imaging techniques.

### Key Features:

- **AI for Eye Health**
  - Analyze images of the **cornea**, **anterior chamber**, **iris**, and **lens** captured via slit-lamp biomicroscope and indirect ophthalmoscope.
  - Provide real-time analysis alongside the doctor to identify abnormalities such as **diabetic retinopathy (DR)**, **uveitis**, **glaucoma**, and more.

- **Image Upload and Disease Detection**
  - A website interface where users can upload eye images for disease detection.
  - The AI model processes the image to detect potential conditions and provides a detailed report.

- **Real-Time Computer Vision**
  - The final product will leverage computer vision to analyze the eye in real-time during examinations.
  - Assist doctors by highlighting abnormalities and providing clear visualizations of detected issues.

- **Safety & next steps**
  - QC checks, confidence scores, and educational information with citations. *Not for diagnosis.*

---

## Architecture (high level)

## Step 1: Diabetic Retinopathy Detection