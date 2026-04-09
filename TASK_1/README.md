LangChain Mini Prompt Engine 🚀
Objective
This project demonstrates the transition from basic hardcoded f-strings to dynamic, reusable prompt systems using LangChain. Built as part of a Generative AI assignment, this engine handles multi-input templates, chat-based personas, and input validation logic.

🛠️ Tech Stack
Language: Python

Framework: LangChain (langchain-core)

Environment: Jupyter Notebook / Google Colab

🌟 Key Features
Dynamic Templates: Replaced static strings with PromptTemplate for modularity.

Multi-Input Support: Systems that adapt to topic, audience, and tone.

Persona Switching: A ChatPromptTemplate system that toggles between Teacher, Interviewer, and Motivator roles.

Safety Layer: Custom validation to ensure inputs (audience/tone) fall within expected parameters before being sent to the LLM.

Prompt Variation Engine: A single topic can be converted into a step-by-step guide, an interview script, or a narrative story.

📂 Project Structure
Assignment_LangChain.ipynb: The main notebook containing all 7 tasks.

README.md: Project documentation and overview.

🚀 Getting Started
1. Prerequisites
Ensure you have the latest version of LangChain installed:

Bash
pip install -U langchain-core
2. Execution
Open the .ipynb file in your preferred editor (VS Code, Jupyter, or Colab) and run the cells sequentially. The output will demonstrate the generated prompts for various test cases like "Neural Networks," "Machine Learning," and "Quantum Physics."

📝 Learning Outcomes
Decoupling prompt logic from Python code.

Implementing SystemMessage and HumanMessage roles for Chat LLMs.

Designing "DRY" (Don't Repeat Yourself) prompt architectures for production environments
