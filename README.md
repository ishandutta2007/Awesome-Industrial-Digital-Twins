# Awesome-Industrial-Digital-Twins

## Top Industrial Digital Twins Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Asset Modeling, Real-Time Synchronization & Self-Hosted Digital Twin Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial industrial digital twin platforms** and **open-source projects** that create virtual representations of physical assets, processes, and systems — enabling simulation, predictive maintenance, and operational optimization.



**Examples** include AWS IoT TwinMaker, Azure Digital Twins, Siemens MindSphere, Bentley iTwin, Dassault 3DEXPERIENCE, GE Vernova Digital Twin, Matterport, Unity Digital Twin, Cosmo Tech, and Ansys Twin Builder (the category leaders).



**Open-source emphasis**: Industrial digital twins are anchored by **Eclipse Ditto** as the leading open-source digital twin framework with 854 stars and 9,559 commits from 95 contributors , **OpenTwins** for next-gen compositional digital twins with 3D visualization and ML integration , **MuPIF** for distributed multiphysics simulation with a Data Management System building digital twin representations , and **EDDIE** for environmental digital twins with modular containerized architecture . **FA³ST** from Fraunhofer delivers Asset Administration Shell tools for digital twins , **OpenDT** provides a self-calibrating datacenter digital twin , and **civic-digital-twins** supports modeling and evaluating digital twins in simulated environments . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS IoT TwinMaker](https://aws.amazon.com/iot-twinmaker/)**  

  **AWS's managed digital twin service** — create digital twins of real-world systems like buildings, factories, and production lines . **Connects to data sources including AWS IoT SiteWise, video feeds, and CAD files** . **Best for AWS-native digital twin deployments** .



- **[Azure Digital Twins](https://azure.microsoft.com/en-us/products/digital-twins/)**  

  **Microsoft's digital twin platform** — model physical environments with DTDL (Digital Twins Definition Language) . **Integration with Azure IoT Hub, Event Grid, and Time Series Insights** . **Best for Azure-native digital twins** .



- **[Siemens MindSphere](https://www.siemens.com/)**  

  **Industrial IoT operating system** — connect products, plants, systems, and machines . **Note**: MindSphere has been consolidated into Siemens Insights Hub . **Best for Siemens-centric industrial operations** .



- **[Bentley iTwin](https://www.bentley.com/)**  

  **Infrastructure digital twin platform** — synchronized physical and digital infrastructure for AEC and utilities . **iTwin.js is available as open-source** . **Best for infrastructure digital twins** .



- **[Dassault 3DEXPERIENCE](https://www.3ds.com/)**  

  **Unified collaborative platform** — digital twin for product design, simulation, and manufacturing . **Best for comprehensive product lifecycle management** .



- **[GE Vernova Digital Twin](https://www.gevernova.com/)**  

  **Industrial digital twin solutions** — asset performance and predictive maintenance . **Best for power generation and energy** .



- **[Matterport](https://matterport.com/)**  

  **3D spatial capture and digital twin platform** — create immersive 3D models of physical spaces . **Best for real estate and facilities management** .



- **[Unity Digital Twin](https://unity.com/)**  

  **Real-time 3D platform** — create interactive digital twins with Unity engine . **Best for high-fidelity visualization and simulation** .



- **[Cosmo Tech](https://cosmotech.com/)**  

  **Digital twin simulation platform** — decision intelligence for complex industrial systems . **Best for supply chain and industrial optimization** .



- **[Ansys Twin Builder](https://www.ansys.com/)**  

  **Multiphysics digital twin platform** — build, validate, and deploy digital twins for complex systems . **Best for engineering digital twins** .



## Open-Source GitHub Projects



### Digital Twin Frameworks



- **[Eclipse Ditto](https://github.com/eclipse-ditto/ditto)**  

  **The leading open-source digital twin framework**, EPL-2.0 licensed with **854 GitHub stars and 9,559 commits from 95 contributors**  . **Device-as-a-Service abstraction** — provides a higher-level API for working with individual devices . **State management** — distinguishes between reported (last known) and current (live) device states . **Policy-based access control** at all APIs . **Organize and search** sets of digital twins by metadata and state data . **Integrates with AMQP, MQTT, and Apache Kafka** for pushing IoT data to backend systems  . **Production-grade with regular releases** (3.9.0 released May 2026)  . **Best for enterprise digital twin abstraction** .



- **[OpenTwins](https://github.com/ertis-research/opentwins)**  

  **Innovative open-source platform specializing in next-gen compositional digital twins**, open-source . **Designed to cover all functionalities a digital twin may require** — from real-time state checking to predictive/simulated data  . **Integrates 3D visualization, ML models, and data acquisition from IoT devices** . **Distributed Digital Twin (DDT) architecture** — enables distribution across different infrastructures with multiple OpenTwins instances collaborating  . **Lightweight and compatible with ARM architectures** for IoT and edge environments  . **Components**: PostgreSQL with TimescaleDB, Redis, K3s, Flink, ML model serving, and DataHub . **Note**: Currently under development — not recommended for production use at this stage  . **Best for research and next-gen digital twin development** .



- **[MuPIF](https://github.com/mupif/mupif)**  

  **Open-source, modular, object-oriented simulation platform for distributed multiphysics workflows with integrated Digital Twin technology**, LGPLv3 licensed . **Data Management System (MuPIFDB)** builds digital twin representations with full traceability . **Entity Data Model (EDM)** identifies entities, attributes, and relations — defined using JSON schema . **Graphical Workflow Editor** for low-code workflow development . **Standardizes application and data component interfaces** for seamless integration of simulation models . **HPC integration** for high computational needs . **SSL or VPN-based secure communication**  . **Best for complex multiphysics digital twins** .



- **[FA³ST](https://github.com/FraunhoferIOSB/FAAAST-Service)**  

  **Fraunhofer Advanced Asset Administration Shell Tools for Digital Twins**, open-source . **Implements Asset Administration Shell (AAS) specifications** for Industry 4.0 digital twins . **Part of the broader AAS ecosystem** including AASPortal and Eclipse Mnestix AAS Browser  . **Best for Industry 4.0 Asset Administration Shell** .



### Specialized Digital Twins



- **[OpenDT](https://github.com/atlarge-research/opendt)**  

  **Open-source digital twin for datacenter monitoring and operation**, open-source . **Continuous integration cycle**: live telemetry data, discrete-event simulation with self-calibration, and SLO-aware feedback to physical ICT  . **Self-calibration improves accuracy** — MAPE 4.39% vs. 7.86% in peer-reviewed work  . **Adheres to FAIR/FOSS principles** . **Best for datacenter performance and sustainability** .



- **[EDDIE (Environmental Digital Data Intelligence Engine)](https://github.com/Geospatial-Research-Institute/EDDIE)**  

  **Free and open-source framework for building environmental Digital Twins**, AGPL-3.0 licensed . **Modular, containerized architecture** assembling FOSS4G components: PostGIS, GeoServer, TerriaJS, and Python processing stack  . **Plugin-based module system** for domain-specific environmental models . **OGC-standard service interfaces** (WPS, WFS, WMS) for interoperability . **Powers Flood Resilience Digital Twin (FReDT), Ōtākoro Digital Twin, and Te Awarua Kai Ora**  . **Best for environmental modeling and management** .



- **[civic-digital-twins](https://github.com/fbk-most/civic-digital-twins)**  

  **Python framework for defining digital twin models and evaluating them in simulated environments**, open-source . **Three-layer architecture**: engine (embedded DSL compiler with NumPy backend), model/simulation layer (Index, Model, Evaluation abstractions), and usage patterns  . **Distribution and formula-based indexes** . **Evaluation over weighted scenarios** . **Best for civic and environmental digital twin modeling** .



- **[ditto-fleet](https://github.com/SINTEF-9012/ditto-fleet)**  

  **Digital Twin-based Secure Software Update platform built on Eclipse Ditto**, open-source . **Manages software throughout operational lifecycle of connected IoT and edge devices**  . **Desired/reported state synchronization** — automatically triggers software update workflows when states differ . **Features**: context-aware software assignment, guaranteed delivery to intermittently connected devices, one-to-one/one-to-many/fleet-wide deployments, hierarchical updates via gateways  . **Best for secure IoT software lifecycle management** .



### Simulation & Modeling Tools



- **[Equation-Free Digital Twins](https://zenodo.org/records/20110416)**  

  **Reproducible Python implementation of Hankel-DMD / Koopman-Hankel digital twin framework for nonlinear structural dynamics**, open-source . **Hankel-DMD modal identification, rolling-horizon virtual sensing, missing/failed sensor reconstruction, SSI-COV comparison utilities, and OpenFAST case-generation pipeline**  . **Tutorial notebook, documentation, and smoke tests included** . **Best for structural dynamics digital twins** .



- **[HP2C-DT](https://github.com/bsc-wdc/HP2C-DT)**  

  **High-Precision High-Performance Computer-enabled Digital Twin framework**, open-source . **Reference implementation for HPC-enabled digital twins**  . **Best for HPC digital twin applications** .



- **[iMETRO Dynamic Simulation](https://github.com/rice-robotics/iMETRO-Dynamic-Simulation)**  

  **World's first open-source dynamic simulation environment for intravehicular space robotics**, open-source . **Developed by NASA Johnson Space Center and Rice University**  . **High-fidelity digital twin of NASA's physical iMETRO facility** — full-scale mockups of future space vehicles and lunar habitats . **Remote development and deployment** — researchers worldwide can create and test robotic software remotely . **Best for space robotics digital twins** .



### Additional Strong Open-Source Options



- **Eclipse Ditto Examples** — Samples and tutorials for Eclipse Ditto digital twins (106 GitHub stars)  .

- **AASPortal** — Node.js web portal for visualization and management of Asset Administration Shells  .

- **Eclipse Mnestix AAS Browser** — Easily get started with AAS and browse through repositories  .

- **OPC UA Cloud Library** — OPC UA information model database with REST interface (global instance hosted by OPC Foundation)  .

- **UA Cloud Viewer** — Tool for managing OPC UA information models ("industrial digital twins")  .

- **Digital Twin based building env management** — IoT and LSTM-based building environment management (JavaScript)  .

- **Samples for Industrial IoT Design Patterns** — Jupyter Notebook samples  .

- **National Digital Twin Platform Pilot Service** — UK national digital twin pilot  .



**Frameworks for building custom industrial digital twin solutions**: Combine **Eclipse Ditto** for production-grade digital twin abstraction with state management and policy-based access control  . Use **OpenTwins** for next-gen compositional digital twins with 3D visualization and ML integration  . Deploy **MuPIF** for distributed multiphysics simulation with a Data Management System building digital twin representations  . Integrate **FA³ST** for Industry 4.0 Asset Administration Shell compliance  . Choose **OpenDT** for self-calibrating datacenter digital twins  . Use **EDDIE** for environmental digital twins with FOSS4G components  . Note that true enterprise industrial digital twins with managed infrastructure, CAD integration, and vendor-supported SLAs (AWS IoT TwinMaker, Azure Digital Twins, Bentley iTwin) remain primarily commercial territory; open-source stacks provide strong digital twin frameworks, simulation platforms, and modeling tools that require integration for complete industrial digital twin deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Industrial digital twin platforms handle sensitive operational data and may control physical equipment. Self-hosted solutions require proper security hardening, access controls, and compliance with industrial safety standards (IEC 62443).

- **Open-source digital twin projects vary significantly in maturity** — Eclipse Ditto is production-grade with regular releases  ; OpenTwins is explicitly **under development and not recommended for production use**  . Evaluate before relying on them for safety-critical applications.

- **Digital twin modeling requires domain expertise** — proper asset hierarchy design, data mapping, and simulation parameters are critical for accurate representation .

- **License considerations**: Eclipse Ditto uses EPL-2.0  , OpenTwins is open-source  , MuPIF uses LGPLv3  , and EDDIE uses AGPL-3.0  . Verify licensing against your use case before committing.

- The open-source ecosystem provides strong digital twin frameworks, simulation platforms, and modeling tools, but **managed infrastructure, CAD integration, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for industrial engineers, digital twin architects, and organizations seeking digital twin sovereignty.**  

Let's make industrial digital twins more open, transparent, and interoperable.
