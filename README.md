# 🎓 Excuse-o-Tron 3000 (AI Zero-Shot Classifier)

**Proiect realizat de:** [CALINESCU-IVAN VLAD], [IONESCU TIBI].

## 🚀 Despre Proiect
Excuse-o-Tron 3000 este o aplicație web demonstrativă care folosește Inteligența Artificială pentru a evalua automat scuzele studenților sau ale angajaților și a le încadra în categorii de tipul: *Minciună, Lene Absolută, Probleme Tehnice, sau Scuză Validă*.

## 🧠 Tehnologia din spate (De ce este special?)
Proiectul **nu folosește niciun API extern și niciun server backend**. 
Inima aplicației este un model de tip **Zero-Shot Classification**, rulat 100% în browser-ul utilizatorului folosind biblioteca `Transformers.js` (Hugging Face).

Acest lucru demonstrează concepte cheie de AI modern:
1. **Edge AI / In-Browser Inference:** Modelul este descărcat și executat local (pe procesorul dispozitivului client), asigurând intimitate totală a datelor și zero costuri de server.
2. **Zero-Shot Classification:** Modelul nu a fost antrenat special pe seturi de date cu scuze. Îi pasăm un text și o listă de categorii definite de noi dinamic în cod, iar AI-ul folosește raționamentul semantic pentru a încadra textul în categoria potrivită.

## 🛠️ Cum se testează?
Pagina este publică prin GitHub Pages.
👉 **[ACCESEAZĂ APLICAȚIA LIVE AICI](aici-pui-linkul-de-la-github-pages)**

*Notă: Deoarece modelele mici optimizate pentru web (in-browser) sunt antrenate predominant pe limba engleză, aplicația necesită introducerea scuzelor în limba engleză pentru rezultate precise.*

## 📁 Structura Repository-ului
- `index.html` - Interfața UI, CSS-ul și logica AI (Vanilla JS + Transformers.js)
- `Prezentare_Proiect.pdf` - Slide-urile prezentării noastre.
