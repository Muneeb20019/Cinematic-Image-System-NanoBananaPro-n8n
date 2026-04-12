# 🎬 Cinematic Image Generation System (Nano Banana Pro + n8n)

![n8n](https://img.shields.io/badge/Workflow-n8n-FF6C37?style=flat&logo=n8n&logoColor=white)
![Gemini](https://img.shields.io/badge/Vision-Gemini_1.5_Flash-4285F4?style=flat&logo=googlegemini&logoColor=white)
![Nano Banana Pro](https://img.shields.io/badge/Model-Nano--Banana--Pro-yellow?style=flat)
![Google Drive](https://img.shields.io/badge/Storage-Google_Drive-4285F4?style=flat&logo=googledrive&logoColor=white)

---

## 🚀 The Solution: Autonomous Agentic Design Engine
Developed for **high-end creative studios** and digital agencies, this system is a **Fully Autonomous Design Engine**. It transforms raw creative concepts into cinematic, 2K visual assets by orchestrating a multi-stage production pipeline.

The system functions as a **Virtual Art Director**: it performs **Multi-Modal Scene Analysis** on reference images, generates hyper-structured production briefs, and manages the complex, long-running asynchronous rendering process of the **Nano Banana Pro** model. This is not just a generator; it is a full-lifecycle asset production system. 🤖🎨✨

---

## ✅ Problems Solved
- **🛑 Style Inconsistency:** By using **Gemini 1.5 Flash** to analyze reference images, the system extracts precise lighting, texture, and composition metadata to ensure brand-consistent style transfer. 👁️
- **🛑 Prompt Fatigue:** Users no longer need to write 500-word prompts. The AI Agent takes a simple idea and expands it into a high-fidelity technical brief. ✍️
- **🛑 API Timeouts:** Traditional workflows crash during long renders. This system uses a **Recursive Polling Loop** to monitor 2K renders that take minutes to complete, ensuring 100% task success. ⏳
- **🛑 Manual Asset Filing:** Automatically handles raw binary buffers and syncs high-resolution files to the correct **Google Drive** directory instantly. 📂

---

## 🖼️ System Architecture

### Workflow Orchestration (Cinematic Production Pipeline)
The master blueprint of the orchestration logic—handling vision gates, agentic briefing, and the asynchronous render lifecycle.
<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/Cinematic-Image-System-NanoBananaPro-n8n/main/Screenshot%202026-02-19%202.33.35%20PM.png" width="100%" alt="n8n Cinematic Image Workflow" style="border-radius:10px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);"/>
  <p><i>Full Agentic Orchestration for Nano Banana Pro Image Synthesis</i></p>
</div>

---

## 🧠 Core Technical Pillars

### 1. 👁️ Multi-Modal Vision Intelligence (Gemini 1.5 Flash)
The workflow features an **Intelligent Logic Gate** at the entry point. If a user provides a reference image, the system triggers a **Visual Audit**. Gemini 1.5 Flash extracts metadata—lighting temperature, depth of field, and subject positioning—translating visual aesthetics into a technical **Style Brief**.

### 2. 🤖 Agentic Art Direction & Schema Enforcement
A central **AI Agent** acts as the lead designer. It merges user intent with vision analysis to generate a production-ready JSON brief. By utilizing **Structured Output Parsers**, the system ensures the prompt follows the exact schema required by the **Nano Banana Pro** model, eliminating model hallucinations.

### 3. ⏳ Asynchronous Lifecycle & Polling Logic
High-fidelity rendering is a **Long-Running Operation (LRO)**. I implemented a robust **Recursive Wait-and-Retry Loop**:
- **Task Initiation:** Captures a unique `taskId` from the KIE.AI engine.
- **State Management:** Enters a controlled "Wait" state to allow for GPU compute.
- **Verification:** Polls the status endpoint until the 2K render is verified as "Success," preventing workflow timeouts. ⚙️⚡

### 4. 📂 Binary Data & Cloud Persistence
The final stage performs deep **Binary Buffer Management**. Once the generation is complete, the workflow fetches the raw high-resolution data and utilizes the **Google Drive API** for permanent persistence, ensuring assets are organized and instantly accessible for professional use. 📤☁️

---

## ✨ Advanced Technical Features
- **🛤️ Dual-Path Logic:** Unified canvas handles both "Text-to-Image" and "Image-to-Image" workflows automatically via conditional routing.
- **🛡️ Fault-Tolerant Rendering:** The polling logic includes safety checks to handle failed tasks without crashing the entire orchestration.
- **⚡ Nano Banana Pro Optimization:** Specialized prompt engineering tailored for the Nano Banana architecture to maximize photorealism and textural detail in every 2K asset.

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **🔄 Automation** | **n8n** (Multi-Modal Orchestration & Async Loops) |
| **🧠 Vision AI** | **Google Gemini 1.5 Flash** (Scene Analysis) |
| **🎨 Image Model** | **Nano Banana Pro** via KIE.AI (2K Synthesis) |
| **💾 Cloud Storage** | **Google Drive API** (Asset Persistence) |
| **📜 Scripting** | **JavaScript & JSON** (Data Sanitization & Schema Mapping) |

---

## ✍️ Author
**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)

---

## 📜 License
This project is licensed under the MIT License.
