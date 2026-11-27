## Day 4 – Tools, Structured Output & Google Sheets Integration

On Day 4 of the Agentic AI Workshop, I explored how AI agents can use tools to perform tasks, validate structured data using Pydantic, and interact with Google Sheets. I built a bakery order assistant for Sweet Crumbs Home Bakery that can check prices, verify opening hours, and record customer orders.

### Implementation

- Installed `langchain`, `langchain-groq` and `gspread` libraries.
- Configured the Groq API key using Google Colab Secrets.
- Initialized the language model using `ChatGroq`.
- Connected Google Colab with Google Sheets using Google authentication and `gspread`.
- Created a Google Sheet to store bakery order details.
- Defined structured order data using a Pydantic `Order` model.
- Created tools using LangChain's `@tool` decorator:
  - `get_price()` – calculates the total price of bakery items.
  - `is_open()` – checks bakery opening hours.
  - `log_order()` – validates and stores customer orders in Google Sheets.
- Created an AI agent using `create_agent()` with the defined tools and system instructions.
- Implemented a `chat()` function to interact with the agent and maintain conversation history.
- Tested the agent with queries related to bakery timings, prices and order booking.

### Key Takeaways

- Understanding how AI agents use tools to perform actions.
- Creating custom tools using LangChain.
- Validating structured data using Pydantic.
- Integrating Google Sheets with an AI agent.
- Building tool-based conversational workflows.
- Maintaining conversation history during agent interactions.

**Day 4 Completed – Tool Calling, Structured Output & Google Sheets Integration.**
