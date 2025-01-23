# Heat Equation LLM Challenge

## Methodology
1. **Data Generation**: Solved the heat equation using the Finite Difference Method (FDM) for Cases 1-4.
2. **Data Preprocessing**: Extracted temperature distributions from VTK files and saved them in a structured CSV format.
3. **Fine-Tuning**: Fine-tuned the IBM Granite 3.1 LLM using LoRA for parameter-efficient training.
4. **Evaluation**: Generated responses to the questions in `Questions.csv` and created the `submission.csv` file.

## Results
- The fine-tuned model provided meaningful physical interpretations of the heat equation solutions.
- Responses were evaluated using cosine similarity against ground truth answers.

## Files
- `heat_equation_llm.ipynb`: Kaggle notebook with the full implementation.
- `submission.csv`: Submission file containing the model's responses.
- `results_lora/`: Directory containing fine-tuning results.
