# Routine Rescue AI — Day 3

## Smart Daily Planning Assistant

###  Day 3 Overview
Day 3 enhances Routine Rescue AI using LangChain prompt templates, chains, conversation history and CSV-based testing.

###  Day 3 Objectives
- Implement ChatPromptTemplate.
- Use MessagesPlaceholder for conversation context.
- Connect the prompt, LLM and output parser using a chain.
- Maintain conversational history.
- Create a reusable ask function.
- Test the assistant using CSV test cases.

### Technologies Used
- Python
- Google Colab
- LangChain
- LangChain Groq
- Groq API
- CSV

### Implementation

**1. Prompt Templates**

Used ChatPromptTemplate to structure the system instructions and user inputs.

**2. Conversation History**

Used MessagesPlaceholder to pass previous conversation messages into the prompt.

**3. Chain Creation**

Connected the prompt, LLM and StrOutputParser using LangChain's pipe syntax.

**4. Conversation Memory**

Maintained recent conversation messages within the current session.

**5. CSV-Based Testing**

Created a test dataset and implemented a function to check responses against expected keywords.

**6. Interactive Chat**

Implemented an interactive chat loop for continuous user interaction.

###  Testing
- Daily task planning.
- Assignment prioritization.
- Unfinished task rescheduling.
- Task-related conversation memory.
- CSV keyword-based testing.

###  Day 3 Architecture

User Input → Prompt Template + History → Groq LLM → Output Parser → Response → Updated History

### Day 3 Outcome

Developed a prompt-template-based conversational planning assistant with conversation context and basic automated testing.
---

*Routine Rescue AI — Turning tasks into achievable plans.*
