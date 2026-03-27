👑 Decoding the Crown: 10 Years of King Felipe VI’s Christmas Speeches
This repository hosts our final Text Mining project, an analytical deep dive into the rhetoric of King Felipe VI of Spain. By examining his annual Christmas addresses from 2014 to 2023, we aim to uncover the linguistic evolution of the monarchy and the "hidden" mechanics of royal persuasion.

🎯 The Mission
Does the King’s message change in times of crisis? We use data science to shift the reader's state of knowledge from "hearing a speech" to "visualizing a strategy." We answer:

Thematic Evolution: Which topics have defined his reign?

Emotional Pulse: How has sentiment fluctuated over a decade of social change?

Persuasive DNA: What specific N-grams and structures make these speeches "Royal"?

🛠 The Toolkit
We utilize the quanteda ecosystem and modern NLP techniques to process the corpus:

Tokenization & Preprocessing: Cleaning and filtering for high-signal analysis.

Document-Feature Matrices (DFM): Quantitative mapping of the King's vocabulary.

N-gram Analysis: Identifying the "signature phrases" of the Spanish Crown.

Sentiment Analysis: Tracking emotional trajectories across the decade.

Topic Modeling (STM): Uncovering latent themes without human bias.

📚 Data & Reproducibility
Source: Transcripts sourced from Casa Real.

Format: Raw .txt files organized by year (e.g., 2014_FelipeVI.txt).

Main Notebook: TM_Final_Assignment.Rmd — a fully executable, narrative-driven R Notebook containing all code, visualizations, and insights.

📂 Structure at a Glance
Plaintext
├── data/speeches/        # Raw speech transcripts (2014–2023)
├── output/               # Generated visualizations and models
├── TM_Final_Assignment.Rmd # The "Source of Truth" (Code + Story)
└── README.md             # This guide
⚙️ Requirements
To reproduce our analysis, ensure you have the following R packages installed:
quanteda, readtext, ggplot2, tidytext, and stm.
