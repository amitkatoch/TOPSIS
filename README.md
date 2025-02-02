TOPSIS Analysis of Pretrained Text Generation Models

This project applies the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method to rank state-of-the-art pretrained text generation models based on multiple performance criteria.

📌 Overview

Text generation models are evaluated based on the following metrics:

BLEU Score (higher is better)

ROUGE Score (higher is better)

Perplexity (lower is better)

Response Time (lower is better)

Using the TOPSIS method, we identify the best-performing model by considering both beneficial and non-beneficial criteria.

🚀 Models Evaluated

GPT-4

LLaMA 2

Mistral

Falcon

Claude

📊 Methodology

Normalization: The dataset is normalized to ensure fair comparison across different units.

Weight Assignment: Weights are assigned based on the importance of each criterion.

Ideal & Negative-Ideal Solutions: The best and worst performance values are identified.

TOPSIS Score Calculation: Models are ranked based on their similarity to the ideal solution.

Results Visualization: A bar chart displays the final rankings.

🔧 How to Run the Notebook

Open the Google Colab notebook (topsis_textgen_models.ipynb).

Run all the cells to compute the rankings.

The final rankings are displayed along with a graphical representation.

The results are saved in a CSV file (topsis_results.csv).


