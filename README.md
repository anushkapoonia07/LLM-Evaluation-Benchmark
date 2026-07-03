# LLM Evaluation Benchmark

## Project Overview

This project demonstrates a structured human evaluation workflow for comparing Large Language Model (LLM) outputs across reasoning, translation, summarization, multilingual, safety, and coding tasks.

The current workbook is designed to support evaluator-style annotation with:

- Accuracy
- Completeness
- Instruction Following
- Reasoning
- Fluency
- Hallucination detection
- Safety
- Issue severity
- Confidence
- Error type

---

## Evaluation Rubric

The evaluation sheet tracks each response with the following fields:

- Prompt ID
- Category
- Difficulty
- Prompt
- ChatGPT Response
- Accuracy
- Completeness
- Instruction Following
- Reasoning
- Fluency
- Hallucination
- Safety
- Error Type
- Issue Severity
- Confidence
- Evaluator Comments
- Overall Score

## Evaluation Categories

- General Knowledge
- Logical Reasoning
- Translation
- Summarization
- OCR
- AI Safety
- English
- Hindi
- Hinglish

---

## Repository Flow

1. Project Overview
2. Evaluation Rubric
3. Prompt Dataset
4. Evaluation Sheet
5. Results
6. Conclusion

## Evaluation Metrics

| Metric | Description |
|---------|-------------|
| Accuracy | Is the information correct? |
| Completeness | Does it answer everything? |
| Fluency | Is it natural? |
| Instruction Following | Did it follow the prompt? |
| Reasoning | Is the logic sound? |
| Hallucination | Did it invent facts? |
| Safety | Is the response safe? |

---

## Screenshots

### Evaluation Sheet Preview

![Evaluation sheet preview](screenshots/evaluation_sheet_preview_v2.png)

### Earlier Preview

![Evaluation sheet preview](screenshots/evaluation_sheet_preview.png)

---

## Results

The first-pass evaluation shows a strong baseline for most prompts, with clearer separation appearing when prompts are intentionally incomplete or safety-sensitive. The updated rubric now captures more realistic annotation signals by including severity, confidence, and error type.

## Conclusion

This repository is moving from a simple spreadsheet exercise toward a practical AI evaluation workflow that looks closer to real annotation work used in industry.

---

## Tools Used

- ChatGPT
- Gemini
- Google Sheets
- Microsoft Excel
- GitHub

---
