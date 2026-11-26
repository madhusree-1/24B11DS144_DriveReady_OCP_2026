## Day 3 – Building a Conversational AI Chain with LangChain

On Day 3 of the Agentic AI Workshop, I explored building a conversational AI assistant using LangChain and Groq. I worked on structuring the conversation using prompt templates, integrating chat history into the chain, and testing the assistant's responses against predefined test cases to evaluate its performance.

### Implementation

- Installed the `langchain` and `langchain-groq` libraries.
- Configured Groq API access through Google Colab Secrets.
- Initialized the LLM using `ChatGroq` with the `openai/gpt-oss-120b` model.
- Used `ChatPromptTemplate` to structure the system and user messages.
- Integrated `MessagesPlaceholder` to dynamically include conversation history.
- Used `StrOutputParser` to convert the model output into a readable string.
- Created a LangChain pipeline using the chain expression language (`prompt | llm | StrOutputParser()`).
- Implemented an `ask()` function to handle user queries and maintain conversation history.
- Tested the assistant's ability to remember details from previous messages during a conversation.
- Loaded test cases from a CSV file using Python's `csv` module.
- Created a `run_tests()` function to evaluate responses based on expected keywords.
- Executed test cases to identify response failures and evaluate the assistant's performance.
- Reviewed the test results and modified the system instructions to improve the assistant's responses.

### Testing & Evaluation

- Executed predefined test cases using `test.csv`.
- Evaluated the assistant's responses against expected keywords.
- Identified failed test cases and analyzed the responses.
- Improved the system instructions and re-evaluated the assistant.

### Key Takeaways

- Understanding LangChain prompt templates and chains.
- Integrating chat history into conversational applications.
- Building a reusable LLM pipeline.
- Evaluating AI responses through automated test cases.
- Iteratively improving an AI assistant based on testing results.

**Day 3 Completed – LangChain, Conversational Memory, Chain Building & AI Testing.**
