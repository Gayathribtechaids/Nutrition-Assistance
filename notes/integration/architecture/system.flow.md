# System Architecture and Flow

## High-Level Flow
1. User opens the NutriScan website
2. User types a nutrition-related question into the chatbot
3. The embedded AI agent receives the input
4. A cloud-hosted language model processes the query
5. The response is generated and displayed to the user

---

## Design Choice
The architecture avoids unnecessary complexity. Instead of building custom APIs or databases, the project relies on stable AI platforms that already provide natural language understanding and response generation.

This approach improves development speed and reduces maintenance overhead.
