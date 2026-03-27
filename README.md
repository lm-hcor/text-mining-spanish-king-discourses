👑 Decoding the Crown: King Felipe VI
A text-mining deep dive into 10 years of Spanish Royal rhetoric (2014–2023) — identifying the evolution of themes, sentiment, and persuasive linguistic markers.

📊 Interactive Analysis → Your_LastName_TMFinalAssignment.Rmd

📂 Repository Structure
Plaintext
TM-Final-Assignment-FelipeVI/
├── data/
│   └── speeches/          # Raw .txt files (2014_FelipeVI.txt, etc.)
├── output/
│   ├── plots/             # Visualizations (Sentiment arcs, Wordclouds)
│   └── models/            # STM (Structural Topic Models) objects
├── TM_Final_Assignment.Rmd # Main executable R Notebook
└── README.md              # Project documentation
🎯 The Mission
Does the King’s message change in times of crisis? We use data science to shift the reader's state of knowledge from "hearing a speech" to "visualizing a strategy." We answer:

Thematic Evolution: Which topics have defined the decade of his reign?

Emotional Pulse: How has sentiment fluctuated across years of social change?

Persuasive DNA: What specific N-grams and structures make these speeches "Royal"?

🛠 The Toolkit
We utilize the quanteda ecosystem and modern NLP techniques to process the corpus:

Preprocessing: Cleaning, stopword removal, and Spanish-specific stemming.

DFM Construction: Quantitative mapping of the King's vocabulary via Document-Feature Matrices.

N-gram Analysis: Extracting bigrams and trigrams to identify "signature phrases" of the Crown.

Topic Modeling (STM): Uncovering latent themes and their evolution over time.

⚙️ Requirements
To reproduce this analysis, ensure the following libraries are installed in your R environment:
