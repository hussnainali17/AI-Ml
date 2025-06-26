# 4th Task: HealthBot using Google Generative AI

## Task Objective

The objective of this notebook ([4thTask.ipynb](4thTask.ipynb)) is to create a simple conversational HealthBot using Google's Generative AI API. The bot is designed to answer general health-related questions in simple language while avoiding medical advice or treatment instructions.

## Dataset Used

- **No dataset used**: This project utilizes the `google-generativeai` API to generate responses to user questions. There is no training data or dataset involved.

## Models Applied

- **Google Generative AI (Gemini 2.5 Flash)**:
  - The notebook uses the `google-generativeai` Python package to access the Gemini 2.5 Flash model.
  - A prompt template is used to instruct the model to act as a friendly and cautious medical assistant.
  - The bot is programmed to avoid giving specific medical advice and to recommend consulting a professional for personal health concerns.

## Key Results and Findings

- **Conversational Bot**: The HealthBot successfully interacts with users, providing general health information in a safe and responsible manner.
- **Safety Measures**: The prompt ensures that the bot does not provide medical advice or treatment instructions, and always encourages users to consult qualified professionals for specific or risky questions.
- **User Experience**: The bot responds in simple, friendly language, making it accessible for general health queries.

---
