# FetalAI — Automated Obstetric Ultrasound Biometry System

> **AI-powered system that automatically detects the correct fetal plane, freezes the image, and measures fetal biometric parameters in real time**

[![Demo](https://img.shields.io/badge/▶%20Watch%20Demo-Google%20Drive-red)](https://drive.google.com/file/d/1WRIEi4XRJ5RyelRQXkY52ocSb7L69OZ5/view?usp=drive_link)
[![CPU Only](https://img.shields.io/badge/Deployment-CPU%20Only-orange)]()
[![Real-time](https://img.shields.io/badge/Processing-Real--time-brightgreen)]()
[![Gates Foundation](https://img.shields.io/badge/Problem%20Space-Gates%20Foundation%20Funded-blue)]()
[![Python](https://img.shields.io/badge/Python-3.8+-yellow)]()

---

## The Clinical Problem

Obstetric ultrasound is one of the most critical tools in maternal healthcare — measuring fetal growth, estimating gestational age, and identifying complications during pregnancy.

But accurate fetal biometry depends entirely on the **operator finding the correct imaging plane**. This requires:
- Identifying the correct cross-sectional view of the fetal head (for BPD)
- Identifying the correct abdominal circumference plane
- Knowing exactly when to freeze the image
- Placing measurement calipers accurately

This is a **skilled, time-consuming task that requires a trained sonographer**.

Across Sub-Saharan Africa, trained sonographers are scarce. In many rural hospitals and primary healthcare centers, nurses or community health workers perform ultrasound scans — often without formal training in biometric measurement. The result is:
- Inaccurate fetal measurements
- Wrong gestational age estimates
- Missed growth restriction
- Preventable maternal and neonatal complications

**FetalAI addresses this directly.**

---

## What It Does

FetalAI automatically:

| Step | What Happens |
|------|-------------|
| **Plane Detection** | Recognizes when the correct fetal head (BPD), abdominal (AC), and femur (FL) planes are in view |
| **Auto-Freeze** | Freezes the image at the optimal measurement moment — no manual freeze needed |
| **Auto-Measurement** | Places calipers automatically and calculates BPD, OFD, AC, and FL instantly |
| **Manual Adjustment** | Allows the clinician to manually adjust calipers if needed — maintaining clinical control |
| **Instant Update** | Measurements recalculate immediately after any manual adjustment |

The result is **accurate, consistent fetal biometry that does not depend on operator skill level**.

---

## Measurements Supported

- **BPD** — Biparietal Diameter (fetal head width)
- **OFD** — Occipitofrontal Diameter (fetal head length)
- **AC** — Abdominal Circumference
- **FL** — Femur Length

---
## Demo

[▶ Watch FetalAI in action](https://drive.google.com/file/d/1WRIEi4XRJ5RyelRQXkY52ocSb7L69OZ5/view?usp=drive_link)

> The demo shows real-time fetal plane detection, auto-freeze, and automatic caliper placement for BPD, AC, and FL measurements.

## Why CPU-Only Matters

Point-of-care ultrasound in Africa runs on portable, battery-powered machines in mobile clinics, remote health centers, and district hospitals. There are no GPU workstations. FetalAI was built to run on the same hardware as the ultrasound machine itself — an ordinary laptop or mini-PC.

---

## Technical Approach

- **Model:** YOLOv8n — optimized for CPU inference speed
- **Plane Recognition:** Custom-trained classifier for standard obstetric planes
- **Measurement Engine:** Automated caliper placement with real-time recalculation
- **Interface:** Live ultrasound feed overlay with measurement display
- **Deployment:** CPU-only, cross-platform (Windows/Linux)

---

## Relevance to Current Global Health Initiatives

The Gates Foundation recently awarded Qure.ai a major grant specifically to develop **AI-powered point-of-care ultrasound algorithms for low-resource clinical settings** — the exact problem FetalAI was independently built to solve.

This tool demonstrates that the solution already exists, built from the clinical ground up by a practicing sonographer in Sub-Saharan Africa.

---

## Built By

**Ephraim Usani** — First-Class Radiographer, Sonographer (PgCert Distinction), and Clinical AI Engineer, Lagos, Nigeria

[LinkedIn](https://www.linkedin.com/in/ephraim-usani) | [GitHub](https://github.com/Ephraim-Usani)

> *"I built this because I have personally performed obstetric ultrasound scans in hospitals where no trained sonographer was available. I know exactly what can go wrong — and exactly what needs to be automated."*
