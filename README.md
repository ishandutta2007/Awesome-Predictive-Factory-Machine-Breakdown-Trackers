# Awesome-Predictive-Factory-Machine-Breakdown-Trackers

# Top Predictive Factory Machine Breakdown Trackers Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Vibration Analysis, Acoustic Monitoring & Remaining Useful Life Prediction*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Predictive Factory Machine Breakdown Tracking**. These tools monitor rotating equipment — motors, pumps, gearboxes, compressors — using vibration, temperature, acoustic, and magnetic flux sensors combined with machine learning to detect developing faults weeks or months before failure.

**Examples** include Augury, Senseye, SparkCognition, Uptake, Nanoprecise, Fiix, MaintainX, UpKeep, AVEVA Predictive Analytics, and Emerson Plantweb (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom anomaly detection, and transparent condition monitoring — ideal for maintenance engineers prioritizing data sovereignty, developers building PdM pipelines, and teams avoiding per-asset sensor subscription fees.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Augury](https://www.augury.com/)**  
  AI-powered Machine Health platform using IoT sensors to capture vibration, temperature, and magnetic data. Provides real-time visibility into equipment condition with expert validation and prescriptive guidance. Customers report 100% accuracy in predictions and elimination of unplanned shutdowns within 4-6 weeks [citation:1]. Integrates with MaintainX for alert-to-work-order workflow [citation:1].

- **[Senseye Predictive Maintenance (Siemens)](https://www.siemens.com/)**  
  Scalable, automated asset intelligence platform that predicts failures and prioritizes maintenance actions. Delivers up to 50% reduction in unplanned downtime, 25% reduction in maintenance costs, and 18% OEE improvement [citation:14]. Integrates with existing CMMS/EAM platforms and requires no data scientists for daily use [citation:14].

- **[SparkCognition SparkPredict](https://www.sparkcognition.com/)**  
  Cognitive anomaly management using supervised, unsupervised, and deep learning algorithms on sensor and control system data. Automated model-building shrinks deployment from weeks to minutes. Deployable on-premises, cloud, or hybrid with Cisco HyperFlex Edge optimization [citation:3][citation:15].

- **[Uptake Fleet](https://uptake.com/)**  
  AI-driven predictive maintenance for fleet vehicles with anomaly detection, failure prediction, and virtual diagnostics. Provides 360° view of fault codes and signals from past 30/60/90 days. Being acquired by Bosch to scale AI-powered fleet maintenance globally [citation:4][citation:16].

- **[Nanoprecise](https://nanoprecise.io/)**  
  6-in-1 wireless sensors capturing acoustic, vibration, magnetic flux, RPM, temperature, and acceleration data. RotationLF AI platform analyzes vibration patterns in real-time. Case study: commercial fishing vessel detected gearbox Z-axis vibration anomaly, preventing breakdown at sea [citation:5].

- **[Fiix by Rockwell Automation](https://fiixsoftware.com/)**  
  Cloud-based CMMS with AI-powered predictive insights, asset management, and work order scheduling. SAP Build Partner with two-way ERP sync. 4,500+ maintenance teams in 100+ countries [citation:6][citation:18].

- **[MaintainX](https://www.getmaintainx.com/)**  
  Mobile-first maintenance and asset management platform with predictive maintenance features. Integrates with SAP ERP and SAP S/4HANA. Features offline mode, QR/barcode scanning, and work order timer. 6,000+ customers [citation:7][citation:19].

- **[UpKeep](https://upkeep.com/)**  
  Mobile-first CMMS with Nova AI assistant for voice-to-work-order, smart scheduling, and autonomous data cleanup. Claims 26% less downtime and 652% ROI per Forrester study [citation:8][citation:20]. Integrates IoT sensors for condition-based maintenance triggers [citation:20].

- **[AVEVA Predictive Analytics](https://www.aveva.com/)**  
  AI and machine learning software that compares near-real-time asset information with equipment history to alert on deviations. Features sensor fault detection, Remaining Useful Life Estimation (RULE) forecasts, and AVEVA PI System Asset Framework adapter [citation:9].

- **[Emerson Plantweb Insight](https://www.emerson.com/)**  
  Predictive intelligence applications for asset health monitoring using wireless sensors. Pre-built analytics for Steam Trap, Heat Exchanger, Pressure Relief Valve, Pump, and Connected Lighting applications. Integrates with existing wireless infrastructure [citation:10].

## Open-Source GitHub Projects

- **[Open-Source Predictive Maintenance System for AC Motors](https://github.com/juanpdeleon/proyecto_motores)**  
  **Low-cost open-source PdM platform for AC induction motors** using ESP8266 microcontrollers, MEMS accelerometers, and temperature sensors. Data processed with **LSTM neural networks** to detect abnormal conditions. Experimental validation with controlled mechanical imbalance demonstrates **anomaly detection accuracy exceeding 80%** [citation:11]. Includes KiCad schematics, Python analytics, and HTML+PHP dashboard. Published March 2026.

- **[SuperCMMS Open-Source Backend](https://github.com/SuperCMMS/Open-Source-CMMS)**  
  **Free and open-source CMMS backend codebase** released under open license. Feature list includes Asset Management, Work Orders, Preventive Maintenance, **Predictive Maintenance**, Corrective Maintenance, Checklists, QR Codes, Inventory Management, and Central Document Repository [citation:12]. Backend-only — designed for organizations to build custom frontends. Currently in rapid development; production readiness pending.

### Additional Strong Open-Source Options

- **NannyML** — Open-source library for post-deployment data science, estimating model performance without ground truth labels.
- **Alibi Detect** — Open-source Python library for outlier, adversarial, and drift detection in time-series sensor data.
- **PyOD** — Python Outlier Detection toolkit for anomaly detection on multivariate sensor data.
- **Merlion** — Open-source time-series anomaly detection library from Salesforce with autoML capabilities.
- **sktime** — Unified framework for time-series machine learning including classification and anomaly detection.
- **InfluxDB + Grafana** — Open-source time-series database and visualization stack for custom vibration monitoring dashboards.
- **Apache PLC4X** — Universal protocol adapter for industrial PLCs (Modbus, OPC UA, Siemens S7) for sensor data ingestion.

**Frameworks for building custom systems**: Combine **Open-Source PdM System for AC Motors** for vibration/temperature anomaly detection with LSTM, **SuperCMMS** for work order and asset management backend, **NannyML** or **Alibi Detect** for drift and anomaly detection, **InfluxDB + Grafana** for time-series visualization, and **Apache PLC4X** for industrial protocol integration to build a complete self-hosted predictive maintenance stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Predictive maintenance tools must comply with machinery safety directives, industrial standards (ISO 10816 for vibration, ISO 13374 for condition monitoring), and data protection regulations. **Predictive alerts must be validated by qualified maintenance personnel before acting** — false positives can cause unnecessary downtime, false negatives can cause catastrophic failure.
- Self-hosted open-source solutions require proper sensor calibration, model validation against known failure events, and integration with CMMS/ERP systems.

---

**Made for maintenance engineers, reliability teams, plant managers, and developers building predictive maintenance platforms.**  
Let's make factory machine breakdown prediction more open, accurate, and maintenance-friendly.
