# 📸 Image Captioning AI
> **Give Meaningful Names to Your Photos with IMG Captioning AI**

This project leverages the **Salesforce BLIP** (Bootstrapping Language-Image Pre-training) model to automatically generate descriptive text captions for any uploaded image. Built with a sleek **Gradio** interface, it provides a seamless bridge between computer vision and natural language processing.

---

### 🧠 Model Specifications
*   **Model:** `Salesforce/blip-image-captioning-base`
*   **Type:** Vision-to-Language Generative Model
*   **Framework:** Hugging Face Transformers & Gradio

### 🛠️ Tech Stack
*   **Interface:** Gradio (Web UI)
*   **Image Processing:** Pillow, NumPy
*   **AI/ML:** PyTorch, Transformers

---

### 🚀 Key Features
*   **Automated Captioning:** Instantly generates human-readable descriptions for images.
*   **One-Click Sharing:** Includes `share=True` in the launch configuration for easy external testing.
*   **Interactive UI:** Simple drag-and-drop image upload with real-time text output.

---

### ⚙️ Local Setup

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/aiedwardyi/image-captioning-ai
    cd image-captioning-ai
    ```

2.  **Install Requirements**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run Application**
    ```bash
    python app.py
    ```
    *   The app will open a local server at `http://127.0.0.1:7860`
    *   A public link will also be generated for temporary remote access.

---

### 📂 Project Architecture
| File | Description |
| :--- | :--- |
| **`app.py`** | Main application script using Gradio and BLIP model |
| **`requirements.txt`** | List of necessary Python libraries (Torch, Transformers, etc.) |

---

### 🎓 Acknowledgments
*   Powered by the **Hugging Face Hub** and **Salesforce Research**.
*   Built for the purpose of accessible AI-driven image accessibility.
