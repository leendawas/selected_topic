This project evaluates logical reasoning in LLMs based on belief bias.

Models tested:
- ChatGPT
- Claude
- DeepSeek
- Gemini

Each model was tested on 10 logical reasoning questions.

Files:
- original_problem.csv: base questions
- variations.csv: modified belief bias questions
- responses_*.csv: model outputs
- final_results.csv: accuracy comparison

Method:
Each model answered using: entailment / contradiction / neutral
Accuracy was calculated based on correct logical answers.
