# Sentiment Analysis of YouTube Reactions to the RNC’s AI‑Generated “Beat Biden” Ad
This project explores how viewers responded to the Republican National Committee’s AI‑generated political advertisement “Beat Biden,” released during the 2024 election cycle. The ad, which depicts speculative scenarios such as geopolitical conflict, civil unrest, and economic decline, sparked considerable discussion about the ethics and impact of synthetic media in political communication.
## Objectives
- Determine whether public sentiment toward the RNC’s AI‑generated ad is predominantly positive, negative or neutral.
- Identify the most frequently used words and phrases in viewer comments.
- Evaluate the broader implications of AI‑generated content on political discourse and public perception.
## Data & Methods
- Used the YouTube Data API to collect 1,274 public comments and replies from the official video.
- Preprocessed the text by converting to lowercase and removing stop words.
- Performed sentiment analysis using the VADER (Valence Aware Dictionary for sEntiment Reasoning) classifier from NLTK.
- Generated word clouds and frequency counts to highlight prominent themes.
- Conducted a small manual review to identify nuances such as sarcasm that automated tools might miss.
## Key Findings
- The majority of comments expressed negative sentiment toward the ad, citing concerns about misinformation, fear‑mongering and the ethics of AI in politics.
- Frequent terms included “Trump,” “Biden,” “GOP,” “AI,” and “fear,” reflecting the polarizing and technology‑focused nature of the discussion.
- Viewers noted that the AI imagery, although clearly labeled in the video, could be misinterpreted as authentic news footage, underscoring the need for clear disclosures.
## Implications
The analysis suggests that AI‑generated political ads evoke strong reactions, with potential to deepen polarization and sow distrust. Policymakers may need to address labeling standards and ethical guidelines to ensure transparency and prevent manipulation. Additionally, improving sentiment‑analysis tools to better detect sarcasm and context could enhance future research on digital political discourse.
