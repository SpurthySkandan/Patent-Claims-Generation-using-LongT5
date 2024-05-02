# Patent-Claims-Generation-using-LongT5

Patent claims are essential in defining the boundaries of intellectual property. Traditionally, drafting claims is a slow, error-prone process requiring detailed legal knowledge. This project aims to streamline this process through automation.

## Dataset
The dataset comprises 10,000 patents from the United States Patent and Trademark Office, issued starting from the year 2005. It includes:
- **Training Set**: 8,000 patents
- **Validation Set**: 1,000 patents
- **Test Set**: 1,000 patents

## Solutions
### Baseline Models
- **Models Used**: T5 and GPT-3.5
- **BLEU Scores**: Evaluated using zero-shot and fine-tuned scenarios with the provided descriptions to generate claims.

### LongT5
- **Model Enhancement**: Extended T5 model handling up to 16,000 tokens, improving context retention and generation capability.
- **Applications**: Trained specifically for longer sequences found in complex datasets like patents.

## Challenges
- **Claim Structure Complexity**: Managing the intricate structure of patent claims.
- **Input Length Limitation**: Encountered issues with handling long texts, resolved by upgrading to Colab Pro+.
- **Hardware Limitations**: Faced restrictions with memory capacity when using advanced models.

## Results
- **Evaluation Metrics**: BLEU for precision, ROUGE for recall, and BERTScore for semantic similarity.
- **Performance Insight**: The model's performance improves with increased context provided during training.

## Future Work
- Increase the volume and diversity of training data.
- Experiment with even longer context lengths.
- Implement advanced sampling techniques to enhance output uniqueness and relevance.

---
