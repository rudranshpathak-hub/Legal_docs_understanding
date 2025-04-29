# ⚖ Legal Document Understanding using Deep NLP Techniques

This repository contains the complete implementation of a domain-specific AI system for understanding, summarizing, and interpreting legal documents using Deep Natural Language Processing techniques.

It combines Rhetorical Role Labeling (RRL), Abstractive Summarization (AS), and Explainable AI (XAI) into one unified pipeline designed specifically for legal judgments and case documents.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `RRL.ipynb` | Classifies each sentence in a legal document into rhetorical roles (Facts, Arguments, Judgments, etc.) using fine-tuned transformer models. |
| `Abstractive.ipynb` | Generates coherent and human-like summaries from legal texts using models like BART and PEGASUS. |
| `XAI.ipynb` | Adds transparency by providing explainability through SHAP and LIME for AI outputs (feature importance, prediction rationale). |
| `README.md` |  Project overview, objectives, usage, and guidance documentation. |

---

## 🔍 Project Objective

The primary objective of this project is to build an AI system that:
- Understands the structure of legal documents through rhetorical role classification.
- Generates coherent, human-like summaries preserving legal intent.
- Provides model explainability to ensure transparency and trust in AI decisions.

---

## 🧠 Technologies Used

- **Python 3.8+**
- **HuggingFace Transformers**
- **SpaCy + LegalNER**
- **BART / PEGASUS for summarization**
- **SHAP & LIME** for explainability
- **Jupyter Notebooks** for interactive development

---

## 🚀 How to Run the Notebooks

### Prerequisites:
- Python 3.8+
- `pip install -r requirements.txt` (create one with transformers, shap, lime, spacy, etc.)

### Running the Modules:
1. **Clone the repository**
   ```bash
   git clone https://github.com/n-ikitasingh/Legal_docs_understanding.git
   cd Legal_docs_understanding
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
3. **Run Notebooks**
- `RRL.ipynb` → Run rhetorical role classification.
- `Abstractive.ipynb` → Generate abstractive summaries.
- `XAI.ipynb` → View interpretability and explanation outputs.

## 📊 Sample Outputs

### ➤ Rhetorical Role Labeling:
```csharp
[Facts] The petitioner was arrested on 18th November 2020.  
[Argument] The trial court failed to consider the prior rulings.  
[Judgment] Bail is granted under Section 438 CrPC.
```

### ➤ Abstractive Summary:
"The petitioner sought anticipatory bail under Section 438. The court granted relief considering lack of strong evidence and legal precedents."

### ➤ Explainability:
- SHAP value plots displaying feature contribution.
- LIME-based interpretability visuals for sentence importance.

---

## 🔍 Applications
- Legal document summarization
- Legal research assistance
- Case law analysis
- AI-enabled legal support systems
- Transparent AI decision-making in the legal domain

---

## 🔮 Future Scope
- Extension to multilingual legal documents (e.g., Hindi, Marathi)
- Integration with scanned document OCR pipelines
- Cloud-based API deployment
- Expansion to constitutional, criminal, and corporate law texts

---


## 📚 References
- Merchant & Pande (2018) – Latent Semantic Analysis in Legal NLP
- Kore et al. (2020) – Legal Document Summarization Approaches
- Ahmad et al. (2020) – Rhetorical Role Classification using Deep Learning
- OpenNyAI – Legal NLP Models for Indian Judgments
- SHAP & LIME – Explainable AI Tools
  
---

## 👩‍💻 Developed By

**Rudransh Pathak**  
3rd Year, Computer Science and Engineering  
Specialization in Artificial Intelligence and Machine Learning  
GitHub: [@rudranshpathak-hub](https://github.com/rudranshpathak-hub)
