# 🎓 Excuse-o-Tron 3000 (AI Zero-Shot Classifier)

**Project developed by:** CALINESCU - IVAN VLAD & IONESCU TIBI , MDBI.

## 🚀 About the Project
Excuse-o-Tron 3000 is a fully interactive, multimodal web application that uses Artificial Intelligence to evaluate student or employee excuses and categorize them into specific buckets: *Blatant Lie, Pure Laziness, Tech Issue, or Valid Excuse*. 

What started as a simple text classifier is now a complete conversational loop: you can **speak** your excuse to the AI, and it will **speak** its verdict back to you, complete with visual polygraph-style feedback.

## ✨ Key Features
* **🎙️ Voice Dictation (Speech-to-Text):** Users can speak their excuses directly into their microphone using native browser APIs.
* **🤖 Robotic Voice Feedback (Text-to-Speech):** The AI reads its final verdict and confidence percentage out loud.
* **🚨 Polygraph Visual Effects:** The UI dynamically reacts to the AI's classification (e.g., the screen shakes violently and turns red if a "Blatant Lie" is detected, or glows green for a "Valid Excuse").
* **🎲 "Surprise Me" Generator:** Instantly loads a hilariously bad, pre-written excuse for quick and frictionless live testing.

## 🧠 The Technology (Why is it impressive?)
This project **does not use any external API keys or backend servers**. 
    
1. **Edge AI / In-Browser Inference:** The core logic is powered by a **Zero-Shot Classification** model running 100% locally in the user's browser via the `Transformers.js` library (Hugging Face). This guarantees zero server costs and absolute data privacy.
2. **Zero-Shot Classification:** The model uses semantic reasoning to accurately classify input into dynamically defined categories on the fly, without needing a pre-trained "excuse dataset".
3. **Multimodal Web APIs:** We seamlessly integrated `window.SpeechRecognition` and `window.speechSynthesis` to create a fully interactive voice loop without relying on paid third-party voice APIs.

## 🛠️ How to test it?
The application is publicly hosted via GitHub Pages.
👉 **[ACCESS THE LIVE APP HERE](https://calinescuivanvlad22-ai.github.io/Excuse-o-Tron-3000-AI-Zero-Shot-Classifier-/)**

## 📁 Repository Structure
- `index.html` - The UI, CSS styling, and the AI logic (Vanilla JS + Transformers.js).
- `Presentation.pdf` - Our project presentation slides.
