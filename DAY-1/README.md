#  Routine Rescue AI — Day 1

## Smart Daily Planning Assistant

### Project Overview
Routine Rescue AI is an AI-powered productivity assistant designed to help students organize their tasks, prioritize work, and create realistic daily schedules based on their available time.

Day 1 focuses on establishing the LLM-powered foundation of the project using Groq and LangChain.

###  Day 1 Objectives
- Connect to a Large Language Model (LLM) using Groq.
- Initialize the AI model using LangChain.
- Create a custom system prompt for Routine Rescue AI.
- Build a reusable `ask()` function.
- Test the AI's daily planning responses.
- Explore the Prompt Guard model for suspicious prompt detection.

### Technologies Used
- Python
- Google Colab
- Groq API
- LangChain
- GPT-OSS 120B
- Prompt Guard

### Implementation

**1. LLM Setup**

Installed `langchain_groq` and initialized the Groq language model using the API key stored in Google Colab Secrets.

**2. System Prompt Design**

Defined the role, purpose, rules and response format for Routine Rescue AI to ensure it behaves as a student productivity assistant.

**3. `ask()` Function**

Created a reusable function that accepts a user question, sends it to the LLM along with the system instructions, and returns the AI-generated response.

**4. Testing the Assistant**

Tested the assistant with scenarios involving:
- DSA problems and Python assignments.
- Limited study time.
- Pending tasks and schedule planning.

**5. Prompt Guard Exploration**

Used the Prompt Guard model to examine a suspicious prompt and observe its classification output.

###  Sample Test

**Input:**

"I have 2 DSA problems and a Python assignment. I have 2 hours today. Help me plan."

**Expected Behavior:**

Routine Rescue AI generates a realistic schedule, prioritizes tasks, and suggests appropriate breaks.

### Day 1 Architecture

User Input → System Prompt → Groq LLM → AI-Generated Response

###  Day 1 Outcome

Successfully established the LLM connection and built the initial AI assistant capable of generating student-focused daily planning suggestions.

---

*Routine Rescue AI — Turning tasks into achievable plans.*
