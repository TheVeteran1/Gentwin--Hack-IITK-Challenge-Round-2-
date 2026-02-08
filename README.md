# Gentwin---GenAI-Driven-Digital-Twin-for-ICS-Cybersecurity-Hack-IITK-Challenge-Round-2-


# GenTwin: Intelligent Digital Twin for Industrial Cyber Attack Detection

## Overview

GenTwin is a cyber-aware Digital Twin prototype designed to identify hidden cybersecurity gaps in Industrial Control Systems (ICS) using the SWaT (Secure Water Treatment) dataset. The project combines **Digital Twin simulation** with **Generative-AI-inspired anomaly reasoning** to detect, explain, and visualize cyber attacks that impact physical processes.

Unlike traditional IDS solutions that focus only on network traffic, GenTwin correlates cyber anomalies with **process-level deviations**, enabling early detection of unsafe system states and improving operator trust through explainable insights.

---

## Problem Statement

Critical infrastructure systems such as water treatment plants are vulnerable to stealthy cyber attacks that bypass signature-based detection. Many attacks only become visible when physical processes are already impacted.

GenTwin addresses this gap by:

* Learning normal system behavior
* Simulating expected behavior using a Digital Twin
* Detecting deviations using data-driven, generative-style reasoning
* Explaining the cyber-physical impact of each anomaly

---

## Solution Architecture

**Data Source**

* SWaT Dataset (iTrust, SUTD)
* Normal operation + attack scenarios

**Core Components**

1. Baseline Behavior Learning (Normal Data)
2. Digital Twin Simulation (Expected Process Response)
3. Residual & Trend Analysis (Observed vs Expected)
4. Attack Inference Engine (Spoofing, Replay, PLC Manipulation)
5. Interactive Cyber Defense Dashboard

---

## How the Model Works

1. Normal-operation SWaT data is used to learn baseline process statistics.
2. A simplified Digital Twin predicts expected sensor behavior.
3. Real sensor values are compared with twin predictions.
4. Residuals, drift, and temporal consistency are analyzed.
5. Detected anomalies are mapped to known ICS attack signatures.
6. Alerts, confidence scores, and explanations are generated.

This approach follows **Generative AI principles** where deviations from learned normal patterns indicate abnormal or malicious behavior.

---

## Detected Cybersecurity Gaps

* Sensor spoofing tolerance beyond static thresholds
* Replay attacks causing delayed detection
* PLC logic drift affecting control stability
* Lack of cross sensor validation
* Weak resilience to slow, stealthy attacks

---

## Dashboard Features

* Real-time system health monitoring
* Digital Twin vs actual signal comparison
* Residual, CUSUM, and energy-based anomaly charts
* Attack confidence and kill-chain stage estimation
* Explainable reasoning for each alert
* Cyber alert timeline for forensic analysis

---

## Innovation & Uniqueness

* Tight integration of Digital Twin + GenAI-inspired reasoning
* Cyber-physical attack interpretation instead of raw alerts
* Explainable detection logic (no black-box behavior)
* Designed for real-world ICS operator usability
* Ready for migration to full AI/ML pipelines

---

## Future Enhancements

* Full Python-based AI/ML implementation
* Variational Autoencoders (VAE) for reconstruction-based detection
* Diffusion or GAN-based synthetic attack generation
* Real-time streaming ingestion
* Multi-sensor correlation modeling
* Deployment on live ICS testbeds

---

## Technology Stack

* HTML, CSS, JavaScript
* Chart.js (Visualization)
* SWaT Dataset

---

## How to Run

1. Clone this repository
2. Open `index.html` in a modern browser
3. Upload a SWaT CSV file
4. Observe real-time detection and visualization

---

## References

* iTrust Centre for Research in Cyber Security, SUTD – SWaT Dataset
* ICS Attack Taxonomy (MITRE ATT&CK for ICS)
* Digital Twin Modeling for CPS Security
* Generative AI for Anomaly Detection


