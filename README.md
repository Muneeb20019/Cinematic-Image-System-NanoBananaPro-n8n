# 🎬 Cinematic Image System (Nano Banana Pro + n8n)

![n8n](https://img.shields.io/badge/Workflow-n8n-FF6C37?style=flat&logo=n8n&logoColor=white)
![Gemini](https://img.shields.io/badge/AI-Gemini--1.5--Flash-4285F4?style=flat&logo=google-gemini&logoColor=white)
![Nano Banana Pro](https://img.shields.io/badge/Model-Nano--Banana--Pro-yellow?style=flat)
![Google Drive](https://img.shields.io/badge/Storage-Google%20Drive-4285F4?style=flat&logo=google-drive&logoColor=white)

**[📸 View Production Gallery](https://github.com/Muneeb20019/n8n)** 

---

<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/n8n/main/Video%20Generation%20for%20youtube.png" width="100%" alt="n8n Cinematic Image Workflow"/>
  <p><i>Full Agentic Orchestration for Nano Banana Pro Image Synthesis</i></p>
</div>

---

## 🚀 Project Overview
Developed for **High-End Creative Studios**, this system is an autonomous **Design Engine**. It manages the full production lifecycle—from **🔍 Multi-Modal Scene Analysis (Phase 1)** to **🎨 High-Fidelity Rendering via Nano Banana Pro (Phase 2)**. 

The pipeline allows users to generate cinematic, brand-consistent assets using either raw text prompts or by uploading a **Reference Image** to guide the AI's style and composition.

---

## 🧠 Core Technical Pillars

### 1. 👁️ Multi-Modal Vision Intelligence
The workflow features an **Intelligent Logic Gate** (If-Node) at the entry point. If a user provides a reference image, **Google Gemini 1.5 Flash** performs a deep visual audit. It extracts metadata such as lighting temperature, textures, and subject positioning, translating them into a text-based **Style Brief** for the next stage.

### 2. 🤖 Agentic Design Briefing
A central **AI Agent** acts as the "Art Director." It merges user prompts with the vision analysis to generate a highly structured **Production Brief**. Using a **Structured Output Parser**, it enforces a strict JSON schema for the image API, ensuring 100% adherence to cinematic standards for the **Nano Banana Pro** model.

### 3. ⏳ Asynchronous Lifecycle Management
Since high-fidelity rendering is a **Long-Running Operation (LRO)**, I implemented a robust **Recursive Polling Loop**. The workflow captures a `taskId`, initiates a controlled **Wait state**, and queries the API status via a GET request until the 2K render is verified, preventing any timeout issues during the compute cycle.

### 4. 📂 Binary Data & Asset Persistence
The final stage handles deep **Binary Data Management**. Once the generation is successful, the system downloads the raw high-resolution buffer and utilizes the **Google Drive API** for permanent storage, ensuring assets are organized and ready for professional use.

---

## ✨ Advanced Features (Production Grade)
- **🛤️ Dual-Path Logic:** Built-in conditional routing to handle both "Text-to-Image" and "Reference-to-Image" workflows within a single unified canvas.
- **🛡️ Schema Enforcement:** Utilized **Structured Output Parsers** to guarantee that the AI Agent's instructions follow a strict data schema, eliminating model "hallucinations."
- **⚡ Nano Banana Pro Optimization:** Specialized prompt engineering tailored for the **Nano Banana Pro** architecture to maximize photorealism and textural detail.

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **🔄 Automation** | n8n Orchestration (Multi-Modal) |
| **🧠 Vision AI** | Google Gemini 1.5 Flash |
| **🎨 Image Model** | **Nano Banana Pro** (via KIE.AI) |
| **💻 Backend Code** | JavaScript & JSON Transformation |
| **🗄️ Cloud Storage** | Google Drive API |

---

## 📝 How to Use
1.  **Submit** ✍️ a description and an optional reference photo via the n8n form.
2.  **The Pipeline** 🔍 detects the input type and performs vision analysis if necessary.
3.  **Nano Banana Pro** 🎨 generates a cinematic 2K image based on the agent's brief.
4.  **The System** ⏳ polls for completion and automatically syncs the high-res file to Google Drive.

---

## ✍️ Author
**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)
