# 👑 Decoding the Crown: King Felipe VI

**A Text Mining project that analyzes a decade of Spanish Royal rhetoric (2014–2023) — identifying the evolution of themes, sentiment, and persuasive linguistic markers.**

| 📊 **Main Notebook** → [LastName_TMFinalAssignment.Rmd](./TM_Final_Assignment.Rmd)

---

### 📂 Repository Structure

```text
TM-Final-Assignment-FelipeVI/
├── data/
│   └── speeches/          # Raw .txt transcripts (2014–2023)
├── output/
│   ├── plots/             # Visualizations (Sentiment arcs, Wordclouds)
│   └── models/            # STM (Topic Models) and DFM objects
├── TM_Final_Assignment.Rmd # Full Narrative + Analysis Pipeline
└── README.md              # Project documentation
```

### 📋 Overview
This project applies Computational Linguistics to answer a central question: Does the King’s message change in times of crisis? We shift the reader's state of knowledge by visualizing 10 years of political strategy through text data, providing meaningful insights without requiring a full reading of the corpus.

### 🛠️ Technical Methodology
**Extraction**: Systematic ingestion of annual Christmas transcripts (2014–2023) from the official Casa Real archive.

**Normalization**: Custom cleaning pipeline using quanteda for Spanish-specific tokenization, stopword removal, and stemming.

**Visualization**: A narrative-driven R Notebook featuring:

**Fuzzy N-gram Mapping**: Identifies recurring multi-word "signature phrases" across different years.

**Sentiment Trajectory**: Tracks emotional fluctuations (Valence/Arousal) through Spain's social and political shifts.

**Topic Modeling (STM)**: Uncovers latent themes to identify the "pricing" of political priorities over time.

### 🚀 How to Run
Clone this repository to your local machine.

Ensure all speech files are located in data/speeches/.

Open TM_Final_Assignment.Rmd in RStudio.

Run the initialization cell to install Requirements (quanteda, tidytext, stm).

Click "Knit" to execute the full storytelling pipeline.

Data Source: All transcripts are publicly available from Casa Real.
