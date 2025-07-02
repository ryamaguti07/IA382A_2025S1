# IA382A_2025S1

# Prompt-to-Pipeline: AI-Driven Design and Emulation of Per-Packet ML for Next-Gen Networks

This project explores the use of generative AI tools to automate the translation of high-level network policies into executable per-packet logic suitable for programmable data planes (e.g., P4 switches).

## 🔍 Project Overview
Inspired by the seminar **"Fast, Flexible, and Intelligent Next-Generation Networks and Systems"**, this project demonstrates a prompt-driven pipeline that:
1. Translates natural language policies into symbolic logic using LLMs (GPT-4o, Gemini).
2. Labels synthetic network telemetry data based on these rules.
3. Trains lightweight ML models (SVM, Logistic Regression, Shallow Neural Networks).
4. Compares model predictions to rule-based logic.
5. Converts both logic types into simplified P4-style decision code.

## 🧠 AI Tools Used
- **GPT-4o / Gemini**: Translate policies into decision logic.
- **OpenAI Code Interpreter**: Visualize metrics, confusion matrix, and distributions.
- **GitHub Copilot / FlowGPT**: Assist in logic generation and completion.
- **Mermaid Chart AI**: Generate flow diagrams of packet decision logic.
- **QuillBot / SlidesAI**: Refine writing and create visual presentations.


## 📊 Results Summary
- Best accuracy achieved: **93%** (Shallow Neural Network)
- Agreement between ML model and symbolic rule logic: **61.35%**
- Output includes deployable logic blocks, visual charts, and model metrics

## 📄 Final Report
See `projetoFinal.pdf` for the full technical report, methodology, results, and discussion.

## 📚 References
- [OpenAI GPT-4 Technical Report](https://openai.com/research/gpt-4)
- [P4 Language Specification](https://p4.org)
- [Cogram](https://www.cogram.com)
