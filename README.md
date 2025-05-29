# 🎤 Voice Cloning with Open-Source TTS Models

## 📌 Project Overview
This project explores voice cloning capabilities using state-of-the-art open-source Text-to-Speech (TTS) models: **Kokoro-82M**, **CSM-1B**, and **XTTS-v2**. The goal was to build an end-to-end pipeline for voice cloning, from dataset creation to optimized inference deployment. The project evaluated model performance in terms of voice similarity, naturalness, and computational efficiency.

## ✨ Key Features
- **📂 Dataset Preparation**: Utilized the VCTK dataset with 110 English speakers, preprocessing audio (resampling, silence trimming) and aligning transcripts.
- **⚙️ Model Fine-Tuning**: Applied parameter-efficient LoRA techniques for lightweight adaptation to new voices.
- **🚀 Inference Optimization**: Deployed models in both cloud (Google Colab) and local (Windows) environments, leveraging ONNX runtime for reduced latency.
- **📊 Evaluation**: Conducted MOS (Mean Opinion Score) tests with 10 participants and measured technical metrics like RTF (Real-Time Factor) and VRAM usage.

## 🤖 Models Explored
1. **🦾 Kokoro-82M**  
   - Lightweight (82M parameters) with efficient inference.  
   - Ideal for edge devices and low-resource environments.
  
![image](https://github.com/user-attachments/assets/5785a5d4-11bb-4bcb-8cc5-c6274af19758)

2. **💬 CSM-1B**  
   - Optimized for conversational speech (1B parameters).  
   - Excels in prosody and contextual coherence.  

![image](https://github.com/user-attachments/assets/fc97023d-5abc-4bc0-8fea-f9443af7783e)

3. **🌍 XTTS-v2**  
   - Multi-lingual, zero-shot voice cloning.  
   - Achieved the highest MOS score (4.3/5) for naturalness.  

![image](https://github.com/user-attachments/assets/9ee94031-b559-4700-84b3-ae2a21632707)

## 📈 Results
| Model       | MOS Score | RTF (GPU) | VRAM Usage | Best Use Case          |
|-------------|-----------|-----------|------------|------------------------|
| Kokoro-82M  | 3.2 ⭐    | 0.06 ⚡   | 1.2GB 💾  | Low-resource deployment|
| CSM-1B      | 4.1 ⭐⭐  | 0.72 🐢  | 6.8GB 💾  | Conversational dialogue|
| XTTS-v2     | 4.3 ⭐⭐⭐ | 0.35 ⚡   | 4.5GB 💾  | High-quality cloning   |

## ⚠️ Ethical Considerations
- Implemented watermarking for traceability. 🔒  
- Enforced consent-based data use and API access control. 👥  
- Addressed risks of voice fraud and deep-fake misuse. 🛡️  

## 🔮 Future Work
- Expand multilingual support for XTTS-v2. 🌐  
- Optimize for real-time edge device deployment. 📱  
- Incorporate emotion conditioning for expressive synthesis. 😊  

## 🔗 Resources
- **📓 Notebook**: [Google Colab Notebook](https://colab.research.google.com/drive/1qv8-7VtGRq7FsgmoyjacxGMxTvHmHkpl?usp=sharing)  
- **📊 Kaggle**: [Kaggle Code](https://www.kaggle.com/code/humaima03/voice-cloning-with-open-source-tts)  

## 👩💻 Author
**Humaima Anwar**  
🔹 Machine Learning Intern @ Arch Technologies  
📞 Contact: 0333-8298957 | 🆔 Intern ID: ARCH-2504-0225  
