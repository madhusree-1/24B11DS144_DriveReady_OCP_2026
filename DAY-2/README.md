# Agentic AI Workshop – Day 2

#  Routine Rescue AI — Day 2

## Smart Daily Planning Assistant

###  Day 2 Overview
Day 2 extends the basic Routine Rescue AI assistant developed on Day 1. The project incorporates structured data handling, few-shot prompting, Python functions, decorators, conversation memory and error handling.

###  Day 2 Objectives
- Understand messages and roles.
- Implement few-shot task classification.
- Represent tasks using JSON.
- Store priority information using dictionaries.
- Create reusable functions with type hints and docstrings.
- Implement decorators for logging.
- Maintain conversational memory.
- Handle API errors.
- Integrate the concepts into the project.

###  Technologies Used
- Python
- Google Colab
- Groq API
- OpenAI-compatible API client
- JSON

###  Implementation

**1. Messages and Roles**

Used system, user and assistant messages to structure AI conversations.

**2. Few-Shot Prompting**

Provided examples to classify messages into TASK, QUESTION or GREETING.

**3. JSON Task Representation**

Represented a task using structured fields such as task name, category, priority, duration and completion status.

**4. Python Dictionaries**

Used dictionaries to represent task priorities.

**5. Functions and Type Hints**

Implemented reusable task-duration utilities.

**6. Decorators**

Created a logging decorator to observe function calls.

**7. Conversation Memory**

Maintained a conversation history so the assistant could refer to recent messages.

**8. Error Handling**

Handled API rate limits, authentication errors, connection errors and general exceptions.

###  Testing
- Task classification
- Structured task representation
- Task-duration validation
- Function logging
- Conversation memory
- API error handling

###  Day 2 Architecture

User Input → Conversation History → Groq LLM → AI Response → Updated History

### Day 2 Outcome

Enhanced the initial AI assistant with structured task-related data, conversational memory, reusable functions and error-handling mechanisms.

---

*Routine Rescue AI — Turning tasks into achievable plans.*
