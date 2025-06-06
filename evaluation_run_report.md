# Evaluation Run Report

This report documents the evaluation results of the government public service chatbot using Microsoft Azure AI Foundry.

---

## Evaluation Overview

- **Model used:** GPT-4 via Azure OpenAI
- **Dataset:** `data/test_dataset.csv`
- **Evaluation type:** Dataset-based
- **Date run:** [Insert date]
- **Metrics applied:**
  - AI Quality (AI-assisted): Groundedness, Relevance, Coherence, Fluency, GPT Similarity
  - AI Quality (NLP): ROUGE, BLEU
  - Risk & Safety Metrics: Self-harm, Hateful/Unfair, Violent, Sexual, Protected material, Indirect attack

---

## Key Results Summary

### AI Quality Scores (AI-assisted)

| Metric        | Avg Score | Notes                            |
|---------------|-----------|----------------------------------|
| Groundedness  | [x.xx]    | [Insert interpretation]          |
| Coherence     | [x.xx]    |                                  |
| Fluency       | [x.xx]    |                                  |
| Relevance     | [x.xx]    |                                  |
| GPT Similarity| [x.xx]    |                                  |

---

### AI Quality Scores (NLP-based)

| Metric     | Score  | Notes                    |
|------------|--------|--------------------------|
| ROUGE      | [x.xx] |                          |
| BLEU       | [x.xx] |                          |

---

### Risk & Safety Evaluation

| Risk Category              | Severity Level (avg) | Findings Summary                      |
|---------------------------|----------------------|---------------------------------------|
| Self-harm                 | [Low/Med/High]       | [Insert key takeaways]                |
| Hateful & Unfair Content  | [Low/Med/High]       |                                       |
| Violent Content           | [Low/Med/High]       |                                       |
| Sexual Content            | [Low/Med/High]       |                                       |
| Protected Material        | [Low/Med/High]       |                                       |
| Indirect Attack           | [Low/Med/High]       |                                       |

---

## Analysis & Observations

- **Model strengths:**  
  [What did the model do well? Fluency? Relevance? Tone?]

- **Areas of concern:**  
  [Were there issues with hallucinations? Grounding? Risk flags?]

- **False positives or false negatives in risk flags:**  
  [If any unexpected or incorrect risk flags were triggered, note them here.]

---

## Alignment with AI Governance Standards

- **AI RMF "Measure" Function:** Metrics were selected to assess both content quality and potential harm.
- **Transparency:** Results documented and reviewed in open format.
- **Actionable Feedback:** Findings will guide future improvements to prompts, grounding techniques, or model selection.

---

## Recommendations

- [ ] Consider using grounding documents to improve factual accuracy.
- [ ] Refine prompts for sensitive queries.
- [ ] Explore additional evaluation with human-in-the-loop.
- [ ] Continue evaluation using larger or real-world test datasets.

---

## Appendix

- Link to dataset: `data/test_dataset.csv`
- Date of evaluation: [Insert date]
- Azure Foundry Evaluation run ID: [Insert ID if available]
