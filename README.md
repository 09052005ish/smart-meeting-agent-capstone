An AI-powered tool-augmented agent that processes meeting transcripts and automatically generates:

✅ Role-aware meeting summaries
✅ Structured JSON action items
✅ Evidence-based retrieval from the transcript
✅ Calendar-ready event intents
All inside a Kaggle Notebook designed for the Google × Kaggle Agents Intensive Capstone Project.

🚀 Overview

Meetings often generate long, unstructured transcripts that are difficult to summarize.
The Smart Meeting Agent automates this process using an agent pipeline capable of:

Understanding and summarizing text

Extracting important tasks and decisions

Suggesting calendar events

Providing structured output for automation workflows

This project demonstrates a fully tool-augmented agent running on Kaggle CPU, using deterministic inference to ensure reproducibility.

🧠 Features
1️⃣ Meeting Summary Generation

Produces a clean, concise, role-aware summary of the entire meeting.

2️⃣ Structured Action Item Extraction

Extracts tasks with:

assignee

due date

description

priority

related conversation snippet

All in valid JSON format.

3️⃣ Evidence Retrieval

Matches extracted action items to supporting sentences in the transcript.

4️⃣ Calendar Event Intent Generation

Creates event suggestions that can be exported into Google Calendar or other scheduling tools.

5️⃣ End-to-End Notebook

All steps run directly inside your Kaggle Notebook with no external dependencies.

🏗 Architecture

Input:
Meeting transcript (.txt or pasted text)

Agent Pipeline:

Document Loader Tool

Action Item Extractor Tool

Retrieval Tool

Calendar Intent Tool

Final Output Formatter

Output:

Summary

Action Items (JSON)

Contextual Evidence

Calendar Events

📂 Repository Structure
📁 smart-meeting-agent-capstone
│
├── smart-meeting-agent-capstone-project.ipynb   # Main Kaggle Notebook
├── sample_transcripts/                          # Example meeting transcripts
├── README.md                                     # This file
└── assets/                                       # Images / diagrams

🔧 Technologies Used

Python

Kaggle Notebook (CPU runtime)

LLM tool-calling framework

Deterministic LLM inference

JSON structured output

Retrieval-based grounding

Chunk-based document processing

🎥 Demo Video (Optional)

If you create a YouTube demo, add it here:

📺 https://youtu.be/your-video-link

📝 How to Use

Open the notebook in Kaggle

Upload your transcript file

Run all cells

View:

Generated summary

Action items

Evidence retrieval

Calendar event intents

Everything works end-to-end with one click (Run All).

📌 Why This Project?

Businesses spend hundreds of hours manually capturing meeting decisions.
This agent saves time by:

Automating summaries

Extracting tasks directly from text

Preparing events for calendars

Reducing missed action points

It is a practical, real-world agent that enhances productivity.

🔮 Future Improvements

If time allowed, I would add:

Vector search with embeddings

Calendar API integration

Speaker role detection

End-to-end voice → transcript → agent pipeline

🏆 Competition Details

This project was created as part of the:
Google × Kaggle 5-Day Agents Intensive — Capstone Project

Track: Tool-Augmented Agents / Concierge Agents
👤 Author
Ishwari Bhausaheb Kadu (shiwaee21 on Kaggle)
Kaggle Profile:https://www.kaggle.com/shiwaee21
