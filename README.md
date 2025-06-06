# gov-public-service-chatbot-evaluation
Evaluation of generative AI chatbot responses to public service queries using Microsoft Azure AI Foundry — applying AI quality, NLP, and risk/safety metrics for responsible AI oversight.
This project evaluates the responses of a government public service chatbot, simulating an AI system that assists citizens with questions about immigration, veterans’ benefits, driver’s licenses, and passports.

The evaluation applies Microsoft Azure AI Foundry’s built-in evaluation framework, using both AI quality metrics and risk & safety metrics to assess the chatbot’s outputs.

The project demonstrates practical skills in:

Responsible AI evaluation

Application of Microsoft AI evaluation tooling

Alignment with NIST AI Risk Management Framework principles

AI governance practices relevant to national security and public-sector use of generative AI

## Data

- **Dataset:** `data/test_dataset.csv`
- **Content:** Sample public service queries and GPT-generated responses covering:
  - Immigration services
  - Veterans’ benefits
  - Driver’s license renewal
  - Passport services
  - Green card replacement

## Methodology

1. Upload test dataset to Azure AI Foundry.
2. Configure evaluation run:
    - Target: Dataset
    - Evaluation Metrics: Full suite:
        - AI Quality: Groundedness, Coherence, Fluency, Relevance, GPT Similarity
        - NLP Metrics: ROUGE, BLEU
        - Risk & Safety Metrics
3. Map dataset columns to required fields.
4. Run evaluation and analyze results.
5. Document results in `evaluation_run_report.md`.

## Results (to be updated after evaluation run)

- Summary of AI quality scores
- Summary of risk/safety scores
- Observations on model performance
- Recommendations for mitigation or improvement (if needed)

## Tools Used

- Microsoft Azure AI Foundry
- GPT-4 via Azure OpenAI Service
- Python (for dataset preparation)
- Markdown for documentation

## License

This project is provided for educational and demonstration purposes only.
