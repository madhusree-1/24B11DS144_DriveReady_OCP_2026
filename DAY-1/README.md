# Agentic AI Workshop – Day 1

## Day 1 – Getting Started with LLMs

On Day 1 of the Agentic AI Workshop, I set up my environment to work with the Groq-hosted language model and built a basic AI assistant for Sweet Crumbs Home Bakery. I also explored Prompt Guard to understand how AI systems can detect potentially unsafe inputs.

### Implementation

- Installed the `langchain_groq` library and imported `ChatGroq`.
- Configured the Groq API key using Google Colab Secrets.
- Initialized the language model using `ChatGroq`.
- Defined a `SYSTEM` variable containing the assistant's role, business facts and response rules.
- Created an `ask()` function using `llm.invoke()` to send user queries along with system instructions.
- Tested the assistant using a sample bakery-order query.
- Integrated Groq's Prompt Guard model `meta-llama/llama-prompt-guard-2-22m`.
- Tested Prompt Guard using a sample input containing an instruction to ignore previous instructions.
- Observed the Prompt Guard output score.

### Key Takeaways

- Setting up and connecting to a language model through Groq.
- Understanding how system and user messages are passed to an LLM.
- Building a basic question-and-answer assistant.
- Exploring prompt safety and input detection using Prompt Guard.

**Day 1 Completed – LLM Setup, Basic Assistant & Prompt Guard.** setup and Prompt Guard exploration.
