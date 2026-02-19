# 🎬 Cinematic Image System (Nano Banana Pro + n8n)

**[📸 View Production Gallery](https://github.com/Muneeb20019/n8n)** 

---

<div align="center">
  <!-- Replace with your actual image file link from GitHub -->
  <img src="https://raw.githubusercontent.com/Muneeb20019/n8n/main/YouTube%20short.png" width="100%" alt="Nano Banana Pro Cinematic Result"/>
</div>

---

## 🚀 Project Overview
Developed for **High-End Creative Studios**, this system is an autonomous "Cinematic Design Engine." It manages the full production lifecycle—from **Multi-Modal Scene Auditing (Phase 1)** to **High-Fidelity Rendering via Nano Banana Pro (Phase 2)**. 

The system leverages **Google Gemini** for visual context and the **Nano Banana Pro** model for ultra-realistic textures and lighting, allowing for the creation of film-grade assets through either text or reference-based inputs.

---

## 🖼️ System Architecture & Workflow Preview

| ⚙️ n8n Agentic Orchestrator | 📂 Automated Asset Persistence |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/Muneeb20019/n8n/main/Video%20Generation%20for%20youtube.png" width="450" alt="n8n Workflow"/> | <img src="https://raw.githubusercontent.com/Muneeb20019/n8n/main/YouTube%20short.png" width="400" alt="Cloud Storage Result"/> |

---

## 🧠 Core Technical Pillars

### 1. 👁️ Multi-Modal Vision Intelligence
The system features an **Intelligent Logic Gate** at the entry point. When a reference image is provided, **Google Gemini 2.5 Flash** performs a deep visual audit, extracting cinematic metadata such as focal length, lighting temperature, and subject composition to be used as style guidance for the next phase.

### 2. 🤖 Agentic Production Briefing
A central **AI Agent** acts as the "Director." It merges user prompts with the vision analysis to generate a highly structured **Production Brief**. Using a **Structured Output Parser**, it enforces strict JSON resolution for the image API, ensuring 100% adherence to cinematic standards for the **Nano Banana Pro** model.

### 3. ⏳ Asynchronous Lifecycle Management
Since high-fidelity rendering is a **Long-Running Operation (LRO)**, I implemented a robust **Recursive Polling Loop**. The workflow captures a `taskId`, initiates a controlled **Wait state**, and queries the API status until the render is successfully verified, preventing timeout issues during heavy compute cycles.

### 4. 📂 Binary Data & Asset Management
The final stage handles deep **Binary Data Management**. Once the generation is complete, the system downloads the raw high-resolution buffer and utilizes the **Google Drive API** for permanent storage and asset versioning.

---

## ✨ Advanced Features (Production Grade)
- **🛤️ Dual-Path Logic:** Built-in conditional routing to handle both "Text-to-Image" and "Image-to-Image" workflows within a single canvas.
- **🛡️ Schema Enforcement:** Utilized **Structured Output Parsers** to guarantee that the AI Agent's instructions follow a strict data schema, eliminating model "hallucinations."
- **⚡ Cinematic Optimization:** Specialized prompt engineering tailored for the **Nano Banana Pro** architecture to maximize photorealism and textural detail.

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **🔄 Automation** | n8n Orchestration (Multi-Modal) |
| **🧠 Vision AI** | Google Gemini 2.5 Flash |
| **🎨 Image Model** | **Nano Banana Pro** (via KIE.AI) |
| **💻 Backend Code** | JavaScript & JSON Transformation |
| **🗄️ Cloud Storage** | Google Drive API |

---

## 📝 How to Use
1.  **Submit** a description and an optional reference photo via the n8n form.
2.  **The Pipeline** detects the input type and performs vision analysis if necessary.
3.  **Nano Banana Pro** generates a cinematic 2K image based on the agent's brief.
4.  **The System** polls for completion and automatically syncs the high-res file to Google Drive.

---

## ✍️ Author
**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)
