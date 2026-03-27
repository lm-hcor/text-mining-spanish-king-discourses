👑 Decoding the Crown: King Felipe VI
A Text Mining project that analyzes a decade of Spanish Royal rhetoric (2014–2023) — identifying the evolution of themes, sentiment, and persuasive linguistic markers.

| 📊 Main Executable → _____

📂 Repository Structure
Plaintext
TM-Final-Assignment-FelipeVI/
├── data/
│   └── speeches/          # Raw .txt transcripts (2014–2023)
├── output/
│   ├── plots/             # Visualizations (Sentiment arcs, Wordclouds)
│   └── models/            # STM (Topic Models) and DFM objects
├── TM_Final_Assignment.Rmd # Full Narrative + Analysis Pipeline
└── README.md              # Project documentation
📋 Overview
This project applies computational linguistics to answer a central question: Does the King’s message change in times of crisis? We shift the reader's state of knowledge by visualizing 10 years of political strategy through text data.

🛠️ Technical Methodology
Preprocessing: Custom cleaning pipeline using quanteda for Spanish-specific stemming and stopword removal.

Analysis: Quantitative mapping of the King's vocabulary via Document-Feature Matrices (DFM).

Visualization: A narrative-driven R Notebook featuring:

Sentiment Trajectory: Tracking emotional fluctuations across a decade of social change.

N-gram Mining: Identifying the "signature phrases" and bigrams that define Royal discourse.

Topic Modeling (STM): Uncovering latent themes and their evolution over time.

🚀 How to Run
Clone this repository.

Ensure you have the .txt files in the data/speeches/ folder.

Open TM_Final_Assignment.Rmd in RStudio.

Run the first code cell to install and load the Requirements (quanteda, tidytext, stm).

Click "Knit" or "Run All" to generate the final report.

Data Source: All transcripts are sourced from the official Casa Real archive.
