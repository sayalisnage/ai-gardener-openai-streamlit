# The AI Gardener: Helping Users Cultivate Plants with Confidence

An AI-powered plant care assistant built using a fine-tuned OpenAI model and deployed via Streamlit. This project combines natural language processing and a user-friendly interface to provide personalized plant care guidance to users of all experience levels.

---

## Abstract

The AI Gardener delivers real-time, customized gardening guidance by fine-tuning a large language model on a curated dataset of plant care topics. From watering schedules to pest solutions, this assistant provides intelligent, practical support to plant owners.

---

## Introduction

Plant care can be overwhelming due to varying environmental needs, pest issues, and plant-specific requirements. This project addresses those challenges by using OpenAI's fine-tuning capabilities to create a chatbot trained on expert gardening knowledge, offering clear, context-aware responses.

---

## Dataset Overview

The training dataset includes structured Q&A pairs on:
- Seasonal care routines
- Pest prevention and treatment
- Watering, lighting, and soil requirements
- Disease identification and treatment
- Location-specific plant advice

The dataset was formatted in JSONL for compatibility with OpenAI’s fine-tuning pipeline.

---

## Methodology

### 1. Environment Setup
- Imported essential libraries (`openai`, `pandas`, `tiktoken`, `jsonlines`)
- Configured OpenAI credentials securely
- Parsed and validated dataset using `pandas` and token counters

### 2. Dataset Preparation
- Structured data into prompt-completion format
- Validated token count and formatting requirements
- Uploaded using the OpenAI CLI

### 3. Fine-Tuning Process
- Initiated fine-tuning with the `gpt-3.5-turbo` model
- Monitored fine-tuning job status and events using CLI and Python SDK
- Retrieved fine-tuned model ID for deployment

### 4. Model Testing and Evaluation
- Compared fine-tuned vs. base model responses
- Evaluated output tone, specificity, and relevance
- Conducted response analysis on user-input prompts

---

## Results

- Fine-tuned model demonstrated improved accuracy and domain relevance
- Provided tailored and context-aware advice to common gardening queries
- Significantly reduced general or vague responses found in base models

---

## Streamlit Deployment

The final model was integrated into a Streamlit app interface for ease of use.  
To run the deployed app locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-gardener-openai-streamlit.git
2. Install required packages:
   ```bash
   pip install -r requirements.txt
3. Launch the app:
   ```bash
   streamlit run app.py

The public version is also deployed online [link your app here]

---

## Future Work

- Add image-based plant issue detection
- Expand dataset coverage to include more plant species
- Integrate local weather APIs for context-aware recommendations
- Improve error handling and personalization options in the app

---

## Tech Stack

- Python
- OpenAI API (GPT-3.5 Turbo fine-tuning)
- Streamlit
- Pandas, JSONL, tiktoken
- GitHub CLI and OpenAI CLI

---

## References

- OpenAI Fine-Tuning Documentation: https://platform.openai.com/docs/guides/fine-tuning
- Streamlit Documentation: https://docs.streamlit.io
- Plant care knowledge base and articles used in dataset curation

---

## Contact

For questions or collaborations, contact via [E-mail](sayalinage@gmail.com) or connect on [LinkedIn](www.linkedin.com/in/sayali-nage-34303b136)

---

