# 🔄 Reproducibility Guide

This guide explains how to reproduce the results from the study **"Impact of EU Non-Financial Reporting Regulation on Spanish Companies’ Environmental Disclosure"** using the **ClimateBERT-analysis** repository.

## 📌 Prerequisites

### ✅ **System Requirements**
- Python **3.8+**
- At least **8GB RAM** (Recommended: 16GB+ for large-scale processing)
- GPU (Optional but recommended for model inference)

### ✅ **Dependencies**
Install all required dependencies:
```bash
pip install -r requirements.txt
```

### ✅ **Data Requirements**
The repository does not include corporate reports due to legal constraints. You must download them from each corporate’s website.

Once downloaded, place them in the `data/` directory:
```
climateBERT-analysis/
│── data/
│   ├── Company_A/
│   │   ├── report_2015.pdf
│   │   ├── report_2016.pdf
│   ├── Company_B/
│   │   ├── report_2017.pdf
│   │   ├── report_2018.pdf
```

---

## 🚀 Step-by-Step Reproducibility

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/villacampaporta/climateBERT-analysis.git
cd climateBERT-analysis
```

### 2️⃣ **Run the Jupyter Notebook**
Start Jupyter and open `Climate_Disclosure_Analysis.ipynb`:
```bash
jupyter notebook
```

Run the notebook **step by step** to:
1. **Extract** text from PDFs
2. **Preprocess** data using NLP techniques
3. **Fine-tune ClimateBERT** (Optional if using pre-trained models)
4. **Analyze the results**

---

## 🛠 Troubleshooting

| Issue | Solution |
|--------|----------|
| Notebook crashes | Run with fewer reports or use a **GPU** |
| Missing dependencies | Re-run `pip install -r requirements.txt` |
| Model inference too slow | Enable **GPU acceleration** using PyTorch |

---

## 📝 Citation
If you use this code, please cite:
```
@article{VillacampaPorta2025,
  author    = {Javier Villacampa-Porta and María Coronado-Vaca and Eduardo C. Garrido-Merchán},
  title     = {Impact of EU Non-Financial Reporting Regulation on Spanish Companies’ Environmental Disclosure},
  journal   = {Environmental Sciences Europe},
  year      = {2025},
  doi       = {10.1186/s12302-025-01067-z}
}
```

---

### 🚀 **Ready to Explore Climate Disclosures with AI? Let’s Get Started!**
