# German-English-Translation-using-Pre-trained-LLMs-and-Fine-tuning

In this project, I've aimed to improve the translation quality and fluency from German to English by leveraging pre-trained translation models and fine-tuning them on the Multi30K dataset.

## Key Findings

- Initial exploratory data analysis on the Multi30K dataset revealed characteristics of both German and English languages, with an average of 20 words per German sentence and 18 words per English sentence.
- We utilized three pre-trained translation models (BART, T5, and Pegasus) to translate random German sentences to English. Evaluation of translation quality using BLEU scores resulted in an average score of 0.5.
- After fine-tuning the selected translation model on the Multi30K corpus and adjusting hyperparameters, we observed an increase in BLEU score from 0.5 to 0.6 on the test set. This improvement indicates enhanced translation accuracy and fluency post-fine-tuning.

## Methodology

1. Conducted initial exploratory data analysis on the Multi30K dataset.
2. Utilized pre-trained translation models (BART, T5, and Pegasus) for translation tasks.
3. Evaluated translation quality using BLEU scores.
4. Fine-tuned the selected translation model on the Multi30K corpus and adjusted hyperparameters.
5. Evaluated performance on the test set to measure the impact of fine-tuning.

## Dependencies

- PyTorch
- Transformers
- NLTK
- NumPy
