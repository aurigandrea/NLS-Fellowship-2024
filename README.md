# NLS Fellowship 2024
 
This repository contains a series of Jupyter Notebooks developed during the National Librarian’s Research Fellowship in Digital Scholarship 2024-25  to interact with the Archive of Tomorrow - Talking about Health web archive collection metadata. The notebooks guide users through various data processing and analysis steps, from metadata conversion to visualization.

## Project Structure

- `Step_1_JSON_metadata_to_CSV.ipynb`: Converts JSON metadata files into CSV format for easier analysis.
- `Step_2_Link_checker.ipynb`: Validates URLs in the dataset to ensure they are accessible.
- `Step_3_Enhancing_the_metadata.ipynb`: Enriches the existing metadata with additional information.
- `Step_4_LLM_Summaries.ipynb`: Generates summaries using Large Language Models (LLMs).
- `Step_5_keyword_wordcloud.ipynb`: Creates word clouds based on extracted keywords.
- `Step_6_Text analysis and visualisation`: Coming soon.
- `Experiments`: Some codes and outputs for performance evaluation.
- `AoT_data_enhanced_labeled`: The final enhanced dataset. It contains a URL valid at the time of uploading, scraped information (title, keywords, summaries, full_text -if available-, LLM-generated summaries, manual category labels, predicted category labels, and the confidence score of the prediction.
- `Data`: The `data` directory contains datasets used across the notebooks. Ensure that the required data files are present before running the notebooks.

## Setup Instructions

To set up the environment and run the notebooks locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/aurigandrea/NLS-Fellowship-2024.git

2. **Create a virtual environment (optional):**

   ```bash
   python -m venv venv
   source venv/bin/activate
  ***On Windows: venv\Scripts\activate***

2. **Install requirements:**
     ```bash
   pip install -r requirements.txt

4. **Lanuch jupyter notebook**
     ```bash
     jupyter notebook

## 🔗 Launch on Binder

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aurigandrea/NLS-Fellowship-2024/HEAD)

Or launch a specific notebook directly (make sure to grab the relevant data or use your own):

- 📄 [Step 1 – JSON to CSV](https://mybinder.org/v2/gh/aurigandrea/NLS-Fellowship-2024/HEAD?filepath=Step_1_JSON_metadata_to_CSV.ipynb)
- 🔗 [Step 2 – Link Checker](https://mybinder.org/v2/gh/aurigandrea/NLS-Fellowship-2024/HEAD?filepath=Step_2_Link_checker.ipynb)
- 🧠 [Step 3 – Enhancing Metadata](https://mybinder.org/v2/gh/aurigandrea/NLS-Fellowship-2024/HEAD?filepath=Step_3_Enhancing_the_metadata.ipynb)
- 🤖 [Step 4 – LLM Summaries](https://mybinder.org/v2/gh/aurigandrea/NLS-Fellowship-2024/HEAD?filepath=Step_4_LLM_Summaries.ipynb)
- ☁️ [Step 5 – Keyword Wordcloud](https://mybinder.org/v2/gh/aurigandrea/NLS-Fellowship-2024/HEAD?filepath=Step_5_keyword_wordcloud.ipynb)


👤 Author and license
Andrea Kocsis
Developed during the NLS Fellowship 2024.
Feel free to explore, use, or build upon this work! MIT License. 
Data owner: National Library of Scotland, CC_BY4
