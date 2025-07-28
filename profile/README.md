---

# 🧠 TuSight AI Medical Imaging Platform

[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE.md)
[![Status](https://img.shields.io/badge/Status-In%20Development-blue.svg)](https://github.com/Raoof-Altaher/TuSight/pulse)
[![Contributions](https://img.shields.io/badge/Contributions-Welcome%20(CLA%20Required)-brightgreen.svg)](CONTRIBUTING.md)
[![Built with](https://img.shields.io/badge/Built%20with-C%23%20%7C%20Python%20%7C%20Docker-lightgrey.svg)](#-technology-stack)

> **Ensemble Intelligence for Clinical Decision Support**

TuSight is an AI-augmented medical imaging platform designed to assist doctors in underserved communities with MRI tumor detection and segmentation.

---

## 🎯 Our Mission

Our mission is to democratize access to state-of-the-art medical diagnostics. TuSight provides clinicians with powerful AI tools to augment their expertise, reduce diagnostic times, and improve patient outcomes. **We believe in technology that serves humanity.**

## ⚠️ Important Notice: License and Usage

This is a proprietary, source-available project. It is **not open source**.

The source code is made publicly visible on GitHub to promote transparency, allow for security audits, and to welcome community contributions under the strict terms of our license.

*   **Usage:** You may **not** use, copy, modify, or distribute this software for any commercial, production, or clinical purpose without explicit written permission from the owner.
*   **Contribution:** We welcome contributions. However, all contributions are subject to our Contributor License Agreement (CLA), which assigns copyright of the contributed code to the project owner.
*   **All Rights Reserved:** All rights, title, and interest in and to the Software and its underlying ideas are the sole property of its founder, Raoof Altaher.

**Please read the full [LICENSE.md](LICENSE.md) file before cloning, forking, or contributing to this repository.**

---

## 📈 Project Status

**Current Stage:** Milestone 0.1 - Single Model MVP

We are actively developing the core backend services and infrastructure. The foundational database and API projects are complete. Our current focus is on implementing the authentication and file management systems.

---

## 🤝 How to Contribute

We are looking for passionate developers, AI researchers, and medical professionals to help us achieve our mission.

1.  Read our **[LICENSE.md](LICENSE.md)** to understand the terms of use and contribution.
2.  Read our **[CONTRIBUTING.md](CONTRIBUTING.md)** file for guidelines on setting up the dev environment, our branch strategy, and coding standards.
3.  Fork the repository and submit a pull request to the `dev` branch.
4.  You will be prompted to sign our **Contributor License Agreement (CLA)** before your pull request can be merged. This is a mandatory step to protect the project's intellectual property.

---

## 🚀 Getting Started (For Contributors)

To set up a local development environment for making contributions:

**Prerequisites:**
*   Docker & Docker Compose
*   Git
*   .NET SDK
*   Python

**Instructions:**

```bash
# 1. Clone the repository
git clone https://github.com/TuSight/TuSight.git
cd TuSight

# 2. Set up environment variables
# This contains necessary secrets and configurations.
cp .env.example .env

# 3. Build and run all services using Docker
# This is the recommended way to start.
docker-compose up --build
```
Once running, the main services will be accessible:
- **Frontend:** `http://localhost:3000`
- **Backend API:** `http://localhost:5206/swagger`

---

## ⚕️ Medical Disclaimer

**This software is an investigational tool for clinical decision support. It is NOT a medical device and is NOT intended for primary diagnostic use.** All results and suggestions produced by the AI must be reviewed and validated by a qualified medical professional. The project owner assumes no liability for its use.

---

## 📞 Contact

*   For bugs and feature requests, please open an issue on GitHub.
*   For other inquiries, you can reach out to Raoof Altaher.
