# 🌍 Climate Disclosure Analysis with NLP

This repository contains the code and data for the paper:  
**"Impact of EU Non-Financial Reporting Regulation on Spanish Companies’ Environmental Disclosure: A Cutting-Edge Natural Language Processing Approach"**  
Published in *Environmental Sciences Europe*  
📄 [Read the Paper](https://doi.org/10.1186/s12302-025-01067-z)

## 📌 Overview

This study investigates the impact of EU regulations on **environmental disclosure quality** among Spanish companies from **2015 to 2022**. We leverage **Natural Language Processing (NLP)**, specifically **ClimateBERT** and a fine-tuned version on **ClimaText**, to analyze **729 corporate sustainability reports**.

The study reveals how **mandatory disclosure requirements** improve specificity and commitment in climate risk reporting, aligning companies with international sustainability frameworks.

## 🏗 Repository Structure

```
climateBERT-analysis/
│── Climate_Disclosure_Analysis.ipynb  # Main Jupyter Notebook
│── data/  # Folder for input reports (not included)
│── results/  # Folder for generated outputs (e.g., graphs, tables)
│── requirements.txt  # Python dependencies
│── LICENSE  # Repository license
│── README.md  # This file
│── Paper.pdf  # Optional: Paper PDF
```

- 📁 **`data/`** – (Not included) Place corporate reports here before running the notebook.
- 📁 **`results/`** – Stores generated figures and tables from the analysis.
- 📄 **`Climate_Disclosure_Analysis.ipynb`** – The core analysis notebook.
- 📄 **`requirements.txt`** – Required dependencies for running the notebook.

## 🚀 Getting Started

### 1️⃣ **Clone this repository**
```bash
git clone https://github.com/villacampaporta/climateBERT-analysis.git
cd climateBERT-analysis
```

### 2️⃣ **Install dependencies**
Ensure you have **Python 3.8+** installed. Then, install the required packages:
```bash
pip install -r requirements.txt
```

### 3️⃣ **Prepare the data**
- Download corporate sustainability reports from:
  - [CNMV Reports](https://www.cnmv.es/)
  - [FactSet](https://www.factset.com/)
- Place **PDF reports** inside the `data/` folder.

### 4️⃣ **Run the Jupyter Notebook**
Start Jupyter and open `Climate_Disclosure_Analysis.ipynb`:
```bash
jupyter notebook
```
Run the notebook **step by step** to reproduce the analysis.

---

## ⚙ Features & Methods

### ✅ **Natural Language Processing (NLP)**
- **Transformers-based models:**  
  - [ClimateBERT](https://huggingface.co/ClimateBERT)
  - Fine-tuned ClimateBERT using [ClimaText](https://github.com/ClimateBERT/ClimaText)
- **Text extraction & preprocessing:**  
  - `PyPDF2`, `pytesseract`, `wand`, `Pillow` for PDF processing
  - `nltk`, `transformers`, `scikit-learn` for NLP

### 📊 **Analysis Highlights**
- **Comparing voluntary vs. mandatory disclosure (2015–2022)**
- **Measuring commitment, specificity, and neutrality in reports**
- **Assessing alignment with international sustainability standards**

---

## 📊 Example Results

> 📌 **How has environmental disclosure changed under regulation?**
  
| Year | Average Commitment Score | Reports Analyzed |
|------|--------------------------|------------------|
| 2015 | 2.1                      | 75               |
| 2018 | 3.4                      | 110              |
| 2022 | 4.8                      | 130              |

> 📌 **Model Performance: ClimateBERT vs. Fine-Tuned Model**
  
| Model                | Accuracy | Commitment Sensitivity |
|----------------------|----------|------------------------|
| ClimateBERT         | 85.2%    | Medium                 |
| Fine-Tuned Model    | 91.5%    | High                   |

---

## 🔥 Reproducibility

To replicate this study:
1. Use **Python 3.8+** and install `requirements.txt`
2. Place **reports** in `data/`
3. Run **`Climate_Disclosure_Analysis.ipynb`** in Jupyter
4. Analyze the **outputs in `results/`**

---

## 📝 Citation

If you use this code or dataset, please cite:

```
@article{VillacampaPorta2025,
  author    = {Javier Villacampa-Porta and María Coronado-Vaca and Eduardo C. Garrido-Merchán},
  title     = {Impact of EU Non-Financial Reporting Regulation on Spanish Companies’ Environmental Disclosure: A Cutting-Edge Natural Language Processing Approach},
  journal   = {Environmental Sciences Europe},
  year      = {2025},
  doi       = {10.1186/s12302-025-01067-z}
}
```

---

## 📜 License

This repository is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

Feel free to contribute! Open an issue or pull request if you have suggestions for improvements.

---

## 📬 Contact

For questions or collaboration inquiries, contact:  
📧 [[Email]](javier.villacampa.porta@gmail.com)
🔗 [[LinkedIn]](https://www.linkedin.com/in/javiervillacampaporta)

---

### 🚀 **Ready to Explore Climate Disclosures with AI? Let's Get Started!**
