
# 🌱 Sustainable Fashion Discovery using Named Entity Recognition (NER)

An NLP-based system that extracts, standardizes, and structures sustainability information from unstructured fashion product descriptions to enable ethical and informed shopping decisions.

---

## 📌 Project Overview

Online fashion platforms often lack clear, structured sustainability metadata. Product descriptions are vague, inconsistent, or misleading due to **greenwashing**, making it difficult for consumers to identify genuinely sustainable products.

This project uses **Named Entity Recognition (NER)** and **Natural Language Processing (NLP)** to automatically extract sustainability-related information such as:

* Materials
* Certifications
* Eco-labels
* Brands
* Sustainability claims (badges)

The extracted data is then used to power intelligent filters, eco-badges, and recommendation systems.

---

## 🎯 Objectives

* Automate extraction of sustainability information from unstructured text
* Standardize certifications and eco-labels for transparency
* Empower consumers with sustainable search filters and recommendations
* Support brands in aligning with **UN Sustainable Development Goals (SDGs)**

---

## 🧠 Key Features

* **NER-based Entity Extraction**

  * Materials (e.g., Organic Cotton, Bamboo, Vegan Leather)
  * Certifications (e.g., GOTS, Fair Trade, RWS)
  * Brands and sustainability claims

* **Sustainability Metadata Structuring**

  * Converts raw text into machine-readable sustainability attributes

* **Smart Filtering & Recommendations**

  * Example filters:

    * “Show only GOTS-certified products”
    * “Vegan leather items only”

* **Scalable Architecture**

  * Can be extended to greenwashing detection, ESG dashboards, and supply chain transparency

---

## 📊 Dataset

### Dataset Type

* **Synthetic dataset** generated for research and prototyping

### Dataset Details

* Created from **70 seed entries**
* Expanded to **3,000+ rows** using programmatic generation
* Uses real-world:

  * Materials
  * Certifications
  * Brands
* Natural, product-style text for realism

### Dataset Columns

| Column Name      | Description                                                |
| ---------------- | ---------------------------------------------------------- |
| `raw_text`       | Full product description                                   |
| `category`       | Product type (jackets, tops, accessories, etc.)            |
| `material`       | Extracted materials                                        |
| `certifications` | Sustainability certifications                              |
| `brand`          | Brand or manufacturer                                      |
| `badges`         | Sustainability claims (Handmade, Carbon Neutral, Upcycled) |

---

## 🔄 Workflow

1. **Data Preparation**

   * Text cleaning and preprocessing
   * Entity annotation (materials, certifications, brands, badges)

2. **NER Model Development**

   * Transformer-based models:

     * BERT
     * RoBERTa
     * DistilBERT
   * Fine-tuned for fashion-specific entities

3. **Recommendation & Filtering Layer**

   * Intelligent sustainability filters
   * Metadata-driven recommendations

4. **Web Integration**

   * User-friendly interface with eco-badges and product scorecards

---

## 🛠️ Tech Stack

### NLP & ML

* Python
* spaCy
* Hugging Face Transformers
* PyTorch

### Data & Annotation

* Pandas
* Prodigy / Label Studio

### Backend

* FastAPI / Node.js
* Elasticsearch (for smart search & filtering)

### Frontend

* React / Next.js

---

## 🌍 Sustainability Impact

This system supports multiple **UN SDGs**:

* **SDG 12** – Responsible Consumption & Production
* **SDG 13** – Climate Action
* **SDG 9** – Industry, Innovation & Infrastructure
* **SDG 8** – Decent Work & Economic Growth

---

## 🚀 Future Scope

* Greenwashing detection using claim verification
* ESG compliance dashboards for brands
* Supply chain transparency tools
* Integration with real e-commerce platforms
* Multilingual sustainability extraction

---

## 👩‍💻 Team

* **Aarushi Mathur** (23070126002)
* **Aneeka Jain** (23070126013)
* **Devershika Mohane** (23070126032)
* **Khushi Kashyap** (23070126060)

---

## 📄 Project Status

📍 **NLP Project – Phase I**
This repository represents a functional prototype with research and product scalability potential.


