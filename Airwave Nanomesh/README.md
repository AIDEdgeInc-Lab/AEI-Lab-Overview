<h1 align="center">AID Edge Inc. - NanoML Acceleration Suite</h1>

<p align="center">
  Empowering Scalable and Efficient AI on Resource-Constrained Devices for Telecom and Beyond.
</p>

<p align="center">
  <img src="AEI-Tiny ML-Lab.png" alt="AID Edge Inc. NanoML Logo" height="400"/>
</p>

<p align="center">
  <a href="https://github.com/AIDEdgeInc-Lab/NanoML-Acceleration-Suite/tree/main/satellite"><img src="https://img.shields.io/badge/Orbital%20NanoML-Pastel%20Blue?style=for-the-badge&color=CCE7FF" alt="Orbital NanoML" title="Explore TinyML solutions for satellite networks"></a>
  <a href="https://github.com/AIDEdgeInc-Lab/NanoML-Acceleration-Suite/tree/main/wireless"><img src="https://img.shields.io/badge/Airwave%20NanoML-Pastel%20Green?style=for-the-badge&color=E6E6FA" alt="Airwave NanoML" title="Explore TinyML solutions for wireless networks"></a>
  <a href="https://github.com/AIDEdgeInc-Lab/NanoML-Acceleration-Suite/tree/main/wireline"><img src="https://img.shields.io/badge/Wired%20NanoML-Pastel%20Mint?style=for-the-badge&color=CCFFE5" alt="Wired NanoML" title="Explore TinyML solutions for wireline networks"></a>
  <a href="https://github.com/AIDEdgeInc-Lab/Documentation-and-Learning"><img src="https://img.shields.io/badge/Knowledge%20Hub-Pastel%20Lavender?style=for-the-badge&color=FFE5CC" alt="Knowledge Hub" title="Learn about NanoML concepts and tools"></a>
  <a href="https://github.com/AIDEdgeInc-Lab/Supporting-Tools"><img src="https://img.shields.io/badge/AI%20Enablement%20Suite-Pastel%20Sky%20Blue?style=for-the-badge&color=F0F0F0" alt="AI Enablement Suite" title="Explore tools and resources to accelerate NanoML development"></a>
</p>

---

<p align="center">💡 Transforming Network Optimization with TinyML 🚀</p>

---

## ![image](https://github.com/user-attachments/assets/f78950af-963e-4b28-ac4f-0cc8172e808e) Our Mission

Advancing the possibilities of AI for resource-constrained environments with **TinyML**, enabling low-latency optimization for telecom networks.

---

## ![image](https://github.com/user-attachments/assets/f43525b1-5776-4894-85f1-0c7db11fe97b) Projects Overview: NanoML Acceleration Suite

<div align="justify">
The **NanoML Acceleration Suite** is designed to bring lightweight AI capabilities to **telecom networks**. By combining **TinyML** models and optimization workflows, we empower resource-constrained devices to deliver real-time analytics, predictive maintenance, and outage prevention.
</div>

---

### Key Highlights:
- **Lightweight Inference**: TinyML models optimized for low-power devices in telecom networks.
- **Domain-Specific Optimization**: Tailored solutions for Satellite, Wireless, and Wireline telecom networks.
- **Deployment-Ready Models**: Compact pre-trained models for seamless deployment.
- **Efficient Scripts**: Tools for model compression, quantization, and edge-specific optimization.

---

### Explore Our Domains

#### 🛰️ Orbital NanoML

NanoML-powered insights for satellite systems:
- Real-time fault detection for satellite communication systems.
- Predictive analysis for environmental monitoring using low-power models.
- Low-latency models for disaster response.

[Explore: Orbital NanoML Models](https://github.com/AIDEdgeInc-Lab/NanoML-Acceleration-Suite/tree/main/satellite)

---

#### 📡 Airwave NanoML

Optimized TinyML frameworks for wireless communication systems:
- Latency reduction for IoT and 5G systems.
- Real-time outage prediction using resource-efficient models.
- Dynamic optimization for network reliability and performance.

[Explore: Airwave NanoML Models](https://github.com/AIDEdgeInc-Lab/NanoML-Acceleration-Suite/tree/main/wireless)

---

#### 🔌 Wired NanoML

Lightweight AI solutions for wireline networks:
- Proactive maintenance to prevent outages.
- Model-driven fault detection and resolution.
- Data flow optimization for improved throughput and performance.

[Explore: Wired NanoML Models](https://github.com/AIDEdgeInc-Lab/NanoML-Acceleration-Suite/tree/main/wireline)

---

### Why Choose NanoML Acceleration Suite?

Our repository delivers:
- **Scalable Optimization**: Real-time AI for resource-constrained devices in telecom.
- **Predictive Maintenance**: Lightweight AI models to prevent network outages.
- **Energy Efficiency**: Advanced TinyML techniques for low-power consumption in edge environments.

Explore the project: [NanoML Acceleration Suite](https://github.com/AIDEdgeInc-Lab/NanoML-Acceleration-Suite)

---

## ![image](https://github.com/user-attachments/assets/839ca94d-0488-44c7-bfa5-2009d8b48d79) How to Run the Projects

### **Step 1: Clone the Repository**

Clone the NanoML Acceleration Suite repository to your local machine:

```bash
git clone https://github.com/AIDEdgeInc-Lab/NanoML-Acceleration-Suite.git

```


---

- **Step 2: Set Up the Environment**

Install required dependencies:

```bash
pip install -r requirements.txt
```


Configure necessary environment variables (if applicable):
```bash
export DATA_PATH=/path/to/dataset
export MODEL_PATH=/path/to/model
```


---

- **Step 3: Run Specific Domains**

#### 🛰️ Orbital NanoML

- Navigate to the Satellite folder:

```bash
cd scripts/satellite
```
- Run the TinyML satellite optimization script::

```bash
python nano_satellite.py --input datasets/satellite/sample_input.json --config configs/satellite_config.yaml

```
---
#### 📡 Airwave NanoML

- Navigate to the Wireless folder:

```bash
cd scripts/wireless

```

- Run the wireless network optimization script:

```bash
python nano_wireless.py --input datasets/wireless/sample_data.json --config configs/wireless_config.yaml

```
---
#### 🔌 Wired NanoML

- Navigate to the Wireline folder:
  
```bash
cd scripts/wireline
```

- Run the wireline optimization script:


```bash
python nano_wireline.py --input datasets/wireline/sample_data.json --config configs/wireline_config.yaml

```

**Notes**
-  Ensure you have the appropriate dataset and configuration files in the respective folders before running the scripts.
-  Modify config.yaml files as needed for custom settings.
-  Output files will be saved in the outputs/ directory of each domain.


---
## ![image](https://github.com/user-attachments/assets/157e2fad-5086-4904-a30a-a4aa2063300d) Transparency and Feedback

<div align="justify">
  
At **AID Edge Inc.**, we prioritize transparency and collaboration in delivering scalable TinyML solutions for telecom. While the code is accessible for viewing, all development is managed internally to ensure the highest standards.

### For Our Customers:

Feel free to explore the code and workflows for our solutions:
- **Edge AI Frameworks:** Real-time AI deployment tailored for edge devices.
- **Orbital, Airwave, and Wired Intelligence Models:** Explore pre-trained models and deployment-ready solutions across different domains with a focus on network optimization and outage prediction.
- **Comprehensive Documentation:** Access tutorials, FAQs, and step-by-step guides for seamless integration of Edge AI technologies into network operations.
</div>


---

### Internal Development

These repositories are actively maintained by our dedicated in-house team. To maintain quality and security:
- Only the internal team has access to modify and develop the codebase.
- Regular updates ensure compatibility with the latest industry standards, particularly in the areas of network reliability and predictive maintenance.

---

## ![image](https://github.com/user-attachments/assets/89a2c1f3-347c-4290-a003-716e9b155d8c) Knowledge Hub

Explore our detailed guides and tutorials designed to help users understand and effectively deploy Edge AI Solutions, with a focus on:
- Real-time outage prediction and mitigation strategies.
- Optimized network performance through predictive analytics and AI-powered insights.

- **Getting Started:** Step-by-step instructions to set up and begin using Edge AI Frameworks.
- **FAQs:** Common questions answered to guide you through challenges in predictive maintenance and network optimization.
- **Domain-Specific Guides:** Tutorials tailored for Orbital, Airwave, and Wired Intelligence applications.

📖 Access the full documentation [Knowledge Hub](https://github.com/AIDEdgeInc-Lab/Documentation-and-Learning).

---

## ![image](https://github.com/user-attachments/assets/71b21b12-f55c-4813-847c-4526d794d96e) AI Enablement Suite

Leverage our suite of supporting tools to enhance your Edge AI development process:

- **Data Preparation Tools:** Simplify dataset preprocessing and formatting for outage prediction and network performance analysis.
- **Model Evaluation Scripts:** Benchmark and evaluate model performance, particularly for Orbital, Airwave, and Wired Intelligence domains.
- **Deployment Scripts:** Streamline workflows for deploying AI models on edge devices to optimize network reliability and uptime.

🔗 Explore the AI Enablement Suite repository [AI Enablement Suite repository](https://github.com/AIDEdgeInc-Lab/Supporting-Tools).



---

##  ![image](https://github.com/user-attachments/assets/7868b320-bc13-4065-85a8-073dd6698163)  Contact

For questions, feedback, or to learn more, reach out to us:

- 📧 **Email**: [info@aidedgeinc.com](mailto:info@aidedgeinc.com)
- 🌐 **Website**: [www.aidedges.com](https://www.aidedges.com)

We value your feedback and are happy to assist with any questions or requirements!

---



<p align="center"> ✨ Follow us on:  </strong> </p> 


<p align="center">
  <a href="https://www.aidedges.com"><img src="https://img.shields.io/badge/Website-AID%20Edge%20Inc.-Pastel%20Mint?style=for-the-badge&color=A3E4D7" alt="Website"></a>
  <a href="https://www.linkedin.com/company/aid-edge-inc"><img src="https://img.shields.io/badge/LinkedIn-AID%20Edge%20Inc.-Pastel%20Blue?style=for-the-badge&color=CCE7FF" alt="LinkedIn"></a>
  <a href="https://github.com/AIDEdgeInc-Lab"><img src="https://img.shields.io/badge/GitHub-AID%20Edge%20Inc.-Pastel%20Gray?style=for-the-badge&color=E6E6FA" alt="GitHub"></a>
  <a href="mailto:info@aidedgeinc.com"><img src="https://img.shields.io/badge/Email-Contact%20Us-Pastel%20Pink?style=for-the-badge&color=FFE5CC" alt="Email"></a>
  
</p>

---

<p align="center">
  <a href="#" style="text-decoration:none; display:inline-block;">
    <img src="https://img.shields.io/badge/©%202025%20AID%20Edge%20Inc.%20All%20Rights%20Reserved-Pastel%20Lavender?style=for-the-badge&color=E8E8E8" alt="© 2025 AID Edge Inc. - All Rights Reserved">
  </a>
</p>

---


