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
- **Models**: LLaVA, Whisper, LoRA adapters
- **RAG**: FAISS
- **APIs**: OpenWeatherMap, Market price APIs, Gov. scheme DB
- **Deployment**: (Kaggle, Colab, HuggingFace Spaces, or Cloud)
- **Frontend**: Gradio

---

## 📂 Repository Structure
```
├── notebooks/ # Kaggle or Colab notebooks
├── adapters/ # folder for 2 adapter
├── dataset/ # All the dataset 
├── README.md # Project documentation

```


## 🎨 Architecture Diagram
<img width="2921" height="2000" alt="farmnaxx-diagram" src="https://github.com/user-attachments/assets/529d902b-209f-4521-9013-a93eda34af23" />


## NoteBook Links
https://www.kaggle.com/code/ashishnewar/farmnaxx-final/edit





