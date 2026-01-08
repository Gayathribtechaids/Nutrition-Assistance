NutriScan – Public Health & Nutrition Chatbot
1. Project Overview

NutriScan is a Public Health & Nutrition chatbot designed to help users get simple, reliable, and easy-to-understand nutrition guidance through a conversational interface.

The project focuses on practical application of Large Language Models (LLMs) using modern AI platforms rather than traditional manual frontend or backend development. The goal is to demonstrate how AI-powered tools can be effectively used to solve real-world problems in a short development cycle.

2. Problem Statement

Many people want to improve their food habits but struggle because:

Nutrition information is scattered across many sources

Most content is too technical or confusing for non-experts

There is no simple way to ask questions and get direct answers

NutriScan addresses this gap by providing a conversational nutrition assistant that allows users to ask questions naturally and receive understandable responses related to public health and nutrition.

3. Target Users

General public

Students and working professionals

People interested in basic nutrition awareness

Users looking for quick, conversational health guidance

4. Solution Approach

The solution follows a simple and user-focused approach:

A web interface hosts an embedded AI chatbot

Users interact using natural language questions

The chatbot responds with general nutrition and public health guidance

The system is intentionally kept minimal and easy to use

The focus is on usability and AI integration, not feature overload.

5. AI Architecture & System Flow

NutriScan uses a cloud-based LLM architecture provided through an AI agent platform.

User
 ↓
Web Interface (Base44)
 ↓
Embedded AI Agent (Jotform)
 ↓
Cloud-hosted Large Language Model
 ↓
Response displayed to user

Flow Explanation:

User enters a nutrition-related question

The AI agent processes the query

The cloud LLM generates a response

The response is shown in a conversational format

6. Use of LLMs and RAG Concepts

A Large Language Model (LLM) is used to understand user intent and generate responses

The chatbot is constrained to the nutrition and public health domain

Knowledge grounding is handled through prompt configuration and scoped AI behavior

No custom embedding models or vector databases are used

This lightweight approach demonstrates how LLM-powered systems can be deployed quickly and responsibly for practical applications.

7. Tools and Platforms Used

Base44
Used to build and host the web application

Jotform AI Agent
Used to create, configure, and embed the chatbot

Cloud-based Language Model
Used internally by the AI agent to generate conversational responses

No manual backend APIs, databases, or model training code were written.

8. Live Website

🔗 NutriScan Web App
https://nutri-scan-7e013cab.base44.app

9. Repository Scope

This repository focuses on:

Problem definition

AI system architecture

Tool selection and reasoning

Application flow explanation

Since the project was built using AI platforms, traditional frontend and backend source code files are not included. This follows the assignment’s encouragement to use modern AI tools to reduce manual development effort.

10. Project Explanation Video


The video covers:

Project motivation

Overall system design

AI architecture and flow

Tools used and reasoning

Key learnings and challenges

11. Key Learnings

Learned how AI platforms can be used to build functional applications without writing full backend or model code

Understood how conversational AI improves accessibility of public health information

Gained experience embedding AI agents into real web applications

Learned the importance of defining a clear and limited problem scope for responsible AI usage

Understood how cloud-hosted LLMs can be applied effectively in real-world scenarios

12. Challenges Faced

Clearly defining the chatbot’s role to avoid vague or overly broad responses

Keeping the system simple while still meeting assignment expectations

Structuring documentation clearly when most functionality comes from AI platforms

Ensuring the chatbot responses remain general and informative rather than prescriptive

13. Conclusion

NutriScan demonstrates a practical and responsible use of LLM-powered chatbots in the public health and nutrition domain. By focusing on clarity, simplicity, and real-world applicability, the project shows how modern AI tools can be effectively leveraged to build useful systems within limited time and resources.

Final Note

This project follows a vibe coding philosophy, where AI tools are used thoughtfully to accelerate development while maintaining clarity and correctness.
