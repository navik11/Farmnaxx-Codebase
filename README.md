# 🌱 Farmnaxx – AI Advisor for Farmers

Agriculture in India faces uncertainties from weather, crop diseases, market fluctuations, and complex policies, making reliable decision
support critical. We present Farmnaxx, a human-aligned agentic AI advisor
that combines multimodal inputs (text, voice, images) with retrieval-augmented
generation (RAG) to deliver grounded, explainable, and multilingual answers.
Farmnaxx integrates fine-tuned LLaVA models for disease detection and crop
recommendation, Whisper for speech queries, and APIs for weather, prices,
and government schemes. By dynamically selecting tools and grounding
outputs in factual data, the system reduces hallucinations and improves trust.
Designed for accessibility, Farmnaxx empowers farmers to make informed
decisions through a natural, farmer-first interface.

---

## 🚀 Features
- 🌾 Crop disease detection using fine-tuned **LLaVA** models (image input).
- 🎙️ Voice query support via **Whisper** for multilingual farmers.
- ☁️ Real-time weather forecasts with OpenWeatherMap API.
- 📊 Market price and government scheme retrieval through APIs.
- 🤖 Agentic orchestration with **RAG** to reduce hallucinations.
- 🌍 Multilingual support for farmer-first accessibility.

---

## 🛠️ Tech Stack
### Core Components
- **Fine-tuning & Adaptation**  
  - LoRA adapters with **Hugging Face Transformers**, **PEFT**, and **BitsAndBytes**  
  - Efficient parameter tuning for **domain-specific agriculture knowledge**  

- **Retrieval & Reasoning**  
  - **FAISS** for similarity search and document retrieval  
  - **RAG (Retrieval-Augmented Generation)** to ground answers in reliable data sources  

- **Speech & Translation**  
  - **Whisper AI** → Speech-to-Text  
  - **Coqui TTS** → Text-to-Speech  
  - **IndicTrans2 / NLLB** → Multilingual support for Indian languages  

- **Deployment**  
  - **Quantized models (AWQ/GGUF)** for efficient performance on **edge devices**  
  - Optimized for rural and low-connectivity zones  


---

## 📂 Repository Structure
```
├── notebooks/ # Kaggle or Colab notebooks
├── adapters/ # folder for 2 adapter
├── dataset/ # All the dataset 
├── README.md # Project documentation

```


## 🎨 Architecture Diagram
<img width="1068" height="664" alt="image" src="https://github.com/user-attachments/assets/6e1f1fb5-c4d2-4f42-8699-7717f8bf2d23" />



## Links
- Kaggle - https://www.kaggle.com/code/ashishnewar/farmnaxx-final/edit
- Documentation - [farmnaxx__Copy_.pdf](https://github.com/user-attachments/files/21840797/farmnaxx__Copy_.pdf)






