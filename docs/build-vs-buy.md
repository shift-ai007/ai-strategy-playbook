# Build vs Buy: A Decision Framework for AI Systems

Every engineering team eventually faces this decision. Here's a practical framework.

## The Decision Isn't Binary

Most production AI systems are a mix. You might use a commercial LLM API for text generation but build your own retrieval pipeline.

## When to Build

- **AI is your competitive advantage**: The ML model IS your product
- **Unusual data requirements**: Specialized terminology, regulatory constraints
- **Cost at scale**: API pricing becomes prohibitive at high volumes

## When to Buy

- **Speed to market matters**: Need AI capabilities next quarter
- **Problem is well-solved**: OCR, sentiment analysis, speech-to-text
- **Lack ML ops expertise**: Production ML needs monitoring and retraining

## Evaluation Matrix

For each layer of your system, score (1-5):

| Factor | Build Signal | Buy Signal |
|--------|-------------|------------|
| Differentiation | High (5) | Low (1) |
| Complexity | Low (1-2) | High (4-5) |
| Data Sensitivity | High (4-5) | Low (1-2) |
| Scale | High (4-5) | Low (1-2) |
| Talent | Available (4-5) | Scarce (1-2) |

## The Third Option

Working with an AI consulting partner who builds custom solutions but transfers ownership. Best when you need something custom but lack ML expertise.

---

[Back to main playbook](../README.md) | [AI Strategy Planning](https://shift-ai.cloud/ai-strategy-planning/)
