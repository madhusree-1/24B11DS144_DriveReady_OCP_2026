# Routine Rescue AI — Day 4

## Overview
Routine Rescue AI is a student productivity agent that helps students manage their daily tasks, estimate task durations, organize study time and store tasks in Google Sheets.

Day 4 introduces tool-based agent functionality and structured data validation.

## Objectives
- Integrate Google Sheets with the AI agent.
- Create structured task data using Pydantic.
- Develop tools using the LangChain `@tool` decorator.
- Estimate task completion time.
- Check available study time.
- Add tasks to Google Sheets.
- Retrieve previously saved tasks.
- Integrate tools with a LangChain agent.

## Technologies Used
- Python
- Google Colab
- Groq LLM
- LangChain
- Google Sheets
- gspread
- Pydantic

## Implementation

### 1. LLM Integration
Connected the Groq model using LangChain's ChatGroq.

### 2. Google Sheets Integration
Created a Google Sheets task tracker to store student task details.

### 3. Structured Task Model
Implemented a Pydantic Task model with task description, subject, priority, deadline, estimated duration and status.

### 4. Tools
Created the following tools:

- `estimate_task_time()` — estimates task duration.
- `get_available_time()` — checks the student's available time.
- `add_task()` — validates and stores tasks.
- `view_tasks()` — retrieves saved tasks.

### 5. Agent Creation
Integrated the tools using LangChain's `create_agent()` function.

### 6. Chat and Memory
Implemented a chat function with conversation history to support multi-turn interactions.

## Architecture

Student Input → LLM Agent → Tool Selection → Tool Execution → Google Sheets / Tool Result → Agent Response

## Testing
- Task planning
- Task duration estimation
- Available time retrieval
- Task confirmation and saving
- Task retrieval

## Outcome
Routine Rescue AI evolved from a conversational planning assistant into a tool-using agent capable of interacting with a Google Sheets task tracker.

