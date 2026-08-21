# AI-Resume-Automation
1. Project Title
AI Resume Automation
2. Project Overview
This project automates the process of extracting and processing resume content using Make.com. The workflow receives resume-related text, identifies the required information using a Text Parser, retrieves additional content from Google Docs, and returns the processed result.
3. Problem Statement
Manually extracting and processing information from resumes can be time-consuming. This project uses automation to reduce manual work and make resume-content processing faster and more consistent.
4. Technologies Used
Make.com – workflow automation
Text Parser – pattern matching and text extraction
Google Docs – resume/content source
Make Scenarios – processing and returning the output
5. Step-by-Step Workflow
Step 1 — Input
The automation receives the required resume-related input.
⬇️
Step 2 — Text Parser
The Text Parser module processes the input and uses pattern matching to identify the required information.
⬇️
Step 3 — Google Docs
The workflow connects to Google Docs and retrieves the required document content.
⬇️
Step 4 — Process the Information
The extracted text and document content are processed within the Make.com scenario.
⬇️
Step 5 — Return Output
The processed information is returned through the Scenarios / Return Output module.
6. Overall Architecture
Resume/Input
     ↓
Text Parser
     ↓
Pattern Matching
     ↓
Google Docs
     ↓
Get Document Content
     ↓
Process Information
     ↓
Return Output
7. Project Benefits
Reduces manual resume processing
Automates repetitive tasks
Extracts information quickly
Integrates with Google Docs
Creates a reusable automation workflow
Can be extended with additional AI services and APIs
8. GitHub Contents
Your repository currently contains:
AI-Resume-Automation/
│
├── README.md
│
└── Get Resume Content.blueprint (1).json
The blueprint JSON allows the Make.com scenario configuration to be shared/reused.
