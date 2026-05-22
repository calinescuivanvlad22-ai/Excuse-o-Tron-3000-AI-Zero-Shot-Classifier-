# 🎓 Excuse-o-Tron 3000 (AI Zero-Shot Classifier)

**Project developed by:** [CALINESCU-IVAN VLAD], [IONESCU TIBI].

## 🚀 About the Project
Excuse-o-Tron 3000 is a demonstrative web application that uses Artificial Intelligence to automatically evaluate student or employee excuses and categorize them into specific buckets: *Blatant Lie, Pure Laziness, Tech Issue, or Valid Excuse*.

## 🧠 The Technology (Why is it impressive?)
This project **does not use any external API keys or backend servers**. 
The core of the application is a **Zero-Shot Classification** model running 100% locally in the user's browser via the `Transformers.js` library (Hugging Face).

This demonstrates key modern AI concepts:
1. **Edge AI / In-Browser Inference:** The model is downloaded and executed directly on the client's CPU. This guarantees complete data privacy and results in zero server costs.
2. **Zero-Shot Classification:** The model was not fine-tuned on an "excuse dataset". We pass a text and an array of dynamically defined categories, and the AI uses semantic reasoning to accurately classify the input on the fly.

## 🛠️ How to test it?
The application is publicly hosted via GitHub Pages.
👉 **[ACCESS THE LIVE APP HERE](PUT_YOUR_GITHUB_PAGES_LINK_HERE)**

## 📁 Repository Structure
- `index.html` - The UI, CSS styling, and the AI logic (Vanilla JS + Transformers.js).
- `Presentation.pdf` - Our project presentation slides.
