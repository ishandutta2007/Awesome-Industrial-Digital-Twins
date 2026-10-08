# Awesome Industrial Digital Twins ⚡

![Awesome Industrial Digital Twins Banner](./assets/banner.svg)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License"/>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen.svg" alt="Status"/>
  <img src="https://img.shields.io/badge/Category-Industrial%20Digital%20Twins-blue.svg" alt="Category"/>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

## 🏭 Top Industrial Digital Twins Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Asset Modeling, Real-Time Synchronization, Physics-Based Simulation & Self-Hosted Digital Twin Platforms*  

**Last updated: October 2026**

This repository tracks notable **commercial industrial digital twin platforms** and **open-source projects** that create virtual representations of physical assets, processes, and systems — enabling real-time IoT monitoring, predictive maintenance, 3D spatial visualization, and operational optimization.

**Leading Commercial Solutions**: Amazon Web Services (AWS IoT TwinMaker), Microsoft Azure Digital Twins, Siemens Insights Hub (MindSphere), Dassault 3DEXPERIENCE, GE Vernova Digital Twin, Unity Digital Twin, Bentley iTwin, Ansys Twin Builder, Matterport, and Cosmo Tech.

**Open-Source Open Ecosystem**: Anchored by **Eclipse Ditto** (Device-as-a-Service abstraction and IoT digital twin framework), **OpenTwins** (compositional digital twins with 3D visualization and ML), **MuPIF** (distributed multiphysics simulation workflows), **FA³ST** (Fraunhofer Asset Administration Shell Industry 4.0 tools), and **EDDIE** (environmental digital twin engine).

---

## 📑 Table of Contents

- [☁️ SaaS/Hosted Platforms](#️-saashosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
  - [⚙️ Digital Twin Frameworks & Infrastructure](#️-digital-twin-frameworks--infrastructure)
  - [🏢 Specialized Digital Twins & Domain Models](#-specialized-digital-twins--domain-models)
  - [🧪 Simulation, Physics & Modeling Tools](#-simulation-physics--modeling-tools)
  - [🌟 Additional Open-Source Options & Components](#-additional-open-source-options--components)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#️-disclaimer)
- [📊 Star History](#-star-history)

---

## ☁️ SaaS/Hosted Platforms

> **📈 Sector Market Size & Industry Dynamics:**  
> The Global Industrial Digital Twin Market is projected to reach **$110.1 Billion by 2030**, growing at a CAGR of ~35.7%. The market is **moderately fragmented** — dominated at the infrastructure level by major cloud hyperscalers (AWS, Azure) and industrial automation software giants (Siemens, Dassault, GE Vernova, Ansys), alongside specialized spatial capture and simulation innovators (Matterport, Unity, Cosmo Tech).

| Platform | Description | Specific Starting Pricing | Free Tier Limit | Company Size (Rev / Valuation) |
| :--- | :--- | :--- | :--- | :--- |
| **[AWS IoT TwinMaker](https://aws.amazon.com/iot-twinmaker/)** | AWS's managed digital twin service to model real-world systems (factories, production lines). Connects to AWS IoT SiteWise, video feeds, and CAD files. | Pay-as-you-go starting at $0.02 per 10,000 unified data access API calls after free tier | Free for 12 months with up to 50 Million data access API calls per month | **$1.8 Trillion+** (Amazon Market Cap) / ~$600B Amazon Revenue |
| **[Azure Digital Twins](https://azure.microsoft.com/en-us/products/digital-twins/)** | Microsoft's digital twin platform modeling physical environments via DTDL with IoT Hub & Event Grid integrations. | Pay-as-you-go starting at $2.50 per 1M operations ($0.025 per 10,000 ops) | No dedicated free tier; $200 free credit valid for 30 days via Azure Free Account | **$3.1 Trillion+** (Microsoft Market Cap) / ~$245B Microsoft Revenue |
| **[Siemens MindSphere](https://www.siemens.com/)** | Industrial IoT operating system (consolidated into Siemens Insights Hub) for asset connection, telemetry, and smart factory operations. | Enterprise capability packages starting at ~€1,000/month (varies by asset count & data volume) | "Start for Free" freemium entry tier available with limited connected assets & features | **$150 Billion+** (Siemens AG Market Cap) / ~$85B Siemens AG Revenue |
| **[GE Vernova Digital Twin](https://www.gevernova.com/)** | Industrial APM and digital twin suite focused on power generation, energy grid assets, and predictive asset performance. | Custom enterprise subscription quote-based pricing | No public free tier/trial; interactive demos and 16-hour cloud training environment provided | **$50 Billion+** (GE Vernova Market Cap) / ~$34B GE Vernova Revenue |
| **[Dassault 3DEXPERIENCE](https://www.3ds.com/)** | Unified collaborative platform for product lifecycle, 3D digital twin design, multiphysics simulation, and smart manufacturing. | Commercial SOLIDWORKS on 3DEXPERIENCE starts at ~€290/user/month (€3,480/year); Makers tier at $99/year | No perpetual free plan; 3-month evaluation offer (~$345 total) or paid trial | **$45 Billion+** (Dassault Systèmes Market Cap) / ~$6.5B Dassault Revenue |
| **[Ansys Twin Builder](https://www.ansys.com/)** | Multiphysics digital twin platform to build, validate, and deploy complex engineering and structural dynamic twins. | Quote-based enterprise software license | 30-day free trial upon consultation request; free Student Edition capped at 15 components | **$28 Billion+** (Ansys Market Cap) / ~$2.3B Ansys Revenue |
| **[Bentley iTwin](https://www.bentley.com/)** | Infrastructure digital twin platform for AEC, civil engineering, and utilities. (iTwin.js core is open-source). | Standard Plan starts at $199/month (includes 200 monthly credits & 50 GB storage) | Free Community Plan forever with 100 credits/month, 10 GB cloud data, and 100 GB reality data | **$15 Billion+** (Bentley Systems Market Cap) / ~$1.2B Bentley Revenue |
| **[Unity Digital Twin](https://unity.com/)** | Real-time 3D engine and platform for interactive industrial digital twins, HMI simulation, and high-fidelity 3D spatial visualization. | Unity Pro starts at $210/month per seat ($2,310/year prepaid) | Unity Personal free forever for entities with under $200,000 USD annual revenue/funding | **$7.5 Billion+** (Unity Software Market Cap) / ~$2.1B Unity Revenue |
| **[Matterport](https://matterport.com/)** | 3D spatial capture and digital twin platform creating immersive, dimensionally accurate 3D models of physical facilities. | Starter Plan starts at $10/month (for up to 5-20 active spaces) | Free Plan forever with 1 active space limit (private sharing, mobile capture only) | **$1.6 Billion+** (Valuation / Acquisition by CoStar Group) |
| **[Cosmo Tech](https://cosmotech.com/)** | Prescriptive AI decision intelligence and simulation digital twin platform for enterprise supply chain & industrial asset optimization. | Enterprise custom subscription pricing per module and deployment scale | No free tier or public free trial; enterprise demonstration available upon request | **$100 Million+** (Estimated Venture Valuation / Series C) |

---

## 🔓 Open-Source GitHub Projects

### ⚙️ Digital Twin Frameworks & Infrastructure

- **[Eclipse Ditto](https://github.com/eclipse-ditto/ditto)** [![GitHub stars](https://img.shields.io/github/stars/eclipse-ditto/ditto?style=social&color=white)](https://github.com/eclipse-ditto/ditto/stargazers)  
  **The leading open-source digital twin framework**, EPL-2.0 licensed. **Device-as-a-Service abstraction** — provides a higher-level API for working with physical IoT devices. **State management** — cleanly separates reported (sensor) vs. desired (command) states. **Policy-based access control** across all APIs. **Integrates with AMQP, MQTT, and Apache Kafka**. Production-grade with active releases (3.9.0+). *Best for enterprise IoT digital twin abstraction.*

- **[OpenTwins](https://github.com/ertis-research/opentwins)** [![GitHub stars](https://img.shields.io/github/stars/ertis-research/opentwins?style=social&color=white)](https://github.com/ertis-research/opentwins/stargazers)  
  **Open-source platform for next-gen compositional digital twins**. Designed to cover end-to-end digital twin requirements — from real-time telemetry checking to predictive/simulated state forecasting. **Integrates 3D visualization, ML models, and IoT acquisition**. Distributed Digital Twin (DDT) architecture compatible with ARM and edge environments. Stack: TimescaleDB, Redis, K3s, Flink, and ML serving. *Best for research & next-gen digital twin architectures.*

- **[FA³ST Service](https://github.com/FraunhoferIOSB/FAAAST-Service)** [![GitHub stars](https://img.shields.io/github/stars/FraunhoferIOSB/FAAAST-Service?style=social&color=white)](https://github.com/FraunhoferIOSB/FAAAST-Service/stargazers)  
  **Fraunhofer Advanced Asset Administration Shell Tools for Digital Twins**. Implements official Asset Administration Shell (AAS) specifications for Industry 4.0 interoperability. Provides REST, OPC UA, and MQTT interfaces for asset models. *Best for Industry 4.0 Asset Administration Shell compliance.*

- **[MuPIF](https://github.com/mupif/mupif)** [![GitHub stars](https://img.shields.io/github/stars/mupif/mupif?style=social&color=white)](https://github.com/mupif/mupif/stargazers)  
  **Modular, object-oriented simulation platform for distributed multiphysics workflows with integrated Digital Twin tech**, LGPLv3 licensed. **MuPIFDB** builds digital twin representations with full traceability. **Entity Data Model (EDM)** defines assets using JSON schema. Includes Graphical Workflow Editor and HPC job integration. *Best for complex multiphysics digital twins.*

---

### 🏢 Specialized Digital Twins & Domain Models

- **[ertis-research/opentwins](https://github.com/ertis-research/opentwins)** [![GitHub stars](https://img.shields.io/github/stars/ertis-research/opentwins?style=social&color=white)](https://github.com/ertis-research/opentwins/stargazers)  
  **Compositional IoT & 3D Digital Twin Platform**. Full stack edge-to-cloud digital twin platform featuring TimescaleDB telemetry, Kafka event streaming, and 3D web rendering.

- **[EDDIE (Environmental Digital Data Intelligence Engine)](https://github.com/Geospatial-Research-Institute/EDDIE)** [![GitHub stars](https://img.shields.io/github/stars/Geospatial-Research-Institute/EDDIE?style=social&color=white)](https://github.com/Geospatial-Research-Institute/EDDIE/stargazers)  
  **Free and open-source framework for building environmental Digital Twins**, AGPL-3.0 licensed. Modular containerized architecture assembling PostGIS, GeoServer, TerriaJS, and Python processing stack. *Powers Flood Resilience Digital Twins and spatial environmental models.*

- **[civic-digital-twins](https://github.com/fbk-most/civic-digital-twins)** [![GitHub stars](https://img.shields.io/github/stars/fbk-most/civic-digital-twins?style=social&color=white)](https://github.com/fbk-most/civic-digital-twins/stargazers)  
  **Python framework for defining digital twin models and evaluating them in simulated environments**. Features embedded DSL compiler with NumPy backend for urban, civic, and environmental scenario evaluation.

- **[ditto-fleet](https://github.com/SINTEF-9012/ditto-fleet)** [![GitHub stars](https://img.shields.io/github/stars/SINTEF-9012/ditto-fleet?style=social&color=white)](https://github.com/SINTEF-9012/ditto-fleet/stargazers)  
  **Digital Twin-based Secure Software Update platform built on Eclipse Ditto**. Manages firmware/software lifecycles across connected IoT & edge device fleets via state synchronization.

- **[OpenDT](https://github.com/atlarge-research/opendt)** [![GitHub stars](https://img.shields.io/github/stars/atlarge-research/opendt?style=social&color=white)](https://github.com/atlarge-research/opendt/stargazers)  
  **Open-source digital twin for datacenter monitoring and operation**. Continuous telemetry integration, discrete-event simulation with self-calibration (MAPE 4.39%), and SLO-aware feedback loops.

---

### 🧪 Simulation, Physics & Modeling Tools

- **[Unity3D Robotics UR Digital Twin](https://github.com/rparak/Unity3D_Robotics_UR)** [![GitHub stars](https://img.shields.io/github/stars/rparak/Unity3D_Robotics_UR?style=social&color=white)](https://github.com/rparak/Unity3D_Robotics_UR/stargazers)  
  **High-fidelity digital twin implementation for industrial robots (Universal Robots UR3)** integrated with Unity3D engine and real-time controller interfaces.

- **[Equation-Free Digital Twins](https://github.com/zenodo/records/20110416)** [![GitHub stars](https://img.shields.io/github/stars/rparak/Unity3D_Robotics_UR?style=social&color=white)](https://github.com/rparak/Unity3D_Robotics_UR/stargazers)  
  **Python implementation of Hankel-DMD / Koopman-Hankel digital twin framework for nonlinear structural dynamics**. Features virtual sensing, missing sensor reconstruction, and OpenFAST case pipelines.

- **[iMETRO Dynamic Simulation Environment](https://github.com/rice-robotics/iMETRO-Dynamic-Simulation)** [![GitHub stars](https://img.shields.io/github/stars/rice-robotics/iMETRO-Dynamic-Simulation?style=social&color=white)](https://github.com/rice-robotics/iMETRO-Dynamic-Simulation/stargazers)  
  **Dynamic simulation environment for intravehicular space robotics** developed by NASA Johnson Space Center and Rice University. High-fidelity digital twin of space vehicles and lunar habitats.

- **[HP2C-DT Framework](https://github.com/bsc-wdc/HP2C-DT)** [![GitHub stars](https://img.shields.io/github/stars/bsc-wdc/HP2C-DT?style=social&color=white)](https://github.com/bsc-wdc/HP2C-DT/stargazers)  
  **High-Precision High-Performance Computer (HPC) enabled Digital Twin framework**, providing reference implementations for distributed supercomputing simulation.

---

### 🌟 Additional Open-Source Options & Components

- **[Eclipse Mnestix AAS Browser](https://github.com/eclipse-mnestix/mnestix-browser)** [![GitHub stars](https://img.shields.io/github/stars/eclipse-mnestix/mnestix-browser?style=social&color=white)](https://github.com/eclipse-mnestix/mnestix-browser/stargazers) — Next-gen web browser interface for viewing and managing Asset Administration Shell (AAS) digital twins.
- **[Eclipse Ditto Examples](https://github.com/eclipse-ditto/ditto-examples)** [![GitHub stars](https://img.shields.io/github/stars/eclipse-ditto/ditto-examples?style=social&color=white)](https://github.com/eclipse-ditto/ditto-examples/stargazers) — Quickstarts, code samples, and tutorials for Eclipse Ditto digital twin integrations.
- **[IndustryFusion DigitalTwin](https://github.com/IndustryFusion/DigitalTwin)** [![GitHub stars](https://img.shields.io/github/stars/IndustryFusion/DigitalTwin?style=social&color=white)](https://github.com/IndustryFusion/DigitalTwin/stargazers) — Core digital twin implementation for multi-vendor smart factory automation and Industry 4.0.
- **[OPC UA Cloud Library](https://github.com/OPCFoundation/UA-CloudLibrary)** [![GitHub stars](https://img.shields.io/github/stars/OPCFoundation/UA-CloudLibrary?style=social&color=white)](https://github.com/OPCFoundation/UA-CloudLibrary/stargazers) — Global repository of OPC UA information models ("industrial digital twins") hosted by the OPC Foundation.
- **[UA Cloud Viewer](https://github.com/OPCFoundation/UA-CloudViewer)** [![GitHub stars](https://img.shields.io/github/stars/OPCFoundation/UA-CloudViewer?style=social&color=white)](https://github.com/OPCFoundation/UA-CloudViewer/stargazers) — Web-based visualization tool for OPC UA information models and industrial asset twins.

---

## 🤝 How to Contribute

Contributions are warmly welcome! Help make industrial digital twins more open, transparent, and interoperable. 🚀

1. 🍴 **Fork the repository**
2. 📝 **Create a new branch** (`git checkout -b add-digital-twin-platform`)
3. ➕ **Add your entry** to `README.md` following the table / list format (include platform name, official site, description, pricing, and open-source star badges).
4. 🚀 **Commit your changes** (`git commit -m "add: new industrial digital twin solution"`)
5. 📤 **Push to your fork** (`git push origin add-digital-twin-platform`)
6. 🔀 **Submit a Pull Request** with a brief summary of the project.

---

## 💖 Support & Sponsorship

If you find this curated list of **Industrial Digital Twin** tools, frameworks, and commercial platforms valuable, please consider supporting the project! 🌟

- ⭐ **Star this repository** to help others discover it!
- 🔀 **Fork and share** with fellow industrial engineers, digital twin architects, and IoT developers!
- ☕ **Sponsor & Buy Me a Coffee**: If you'd like to support ongoing updates and open-source curation, visit the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated list** — not an exhaustive registry nor an endorsement.
- **Security & Safety**: Industrial digital twins interact with real-world infrastructure and critical physical assets. Self-hosted platforms require proper OT/IT security hardening, role-based access control, and adherence to industrial standards (e.g., IEC 62443).
- **Maturity Variance**: Open-source tools range from production-ready enterprise platforms (**Eclipse Ditto**) to research-stage frameworks (**OpenTwins**). Evaluate licenses (EPL-2.0, AGPL-3.0, LGPLv3) and readiness before production deployment.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Industrial-Digital-Twins&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Industrial-Digital-Twins&type=date&legend=top-left)

---

<p align="center">
  <b>Made with ❤️ for Industrial Engineers, Digital Twin Architects &amp; Industry 4.0 Pioneers.</b>
</p>
