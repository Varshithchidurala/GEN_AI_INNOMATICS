Mastering LangChain Prompt Templates 🦜🔗
📖 Overview
This project is a comprehensive implementation of Dynamic Prompt Engineering using the LangChain framework. The core objective is to move away from static, hardcoded f-strings and transition toward building reusable, modular, and scalable prompt pipelines.

By decoupling instructions from logic, this "Mini Prompt Engine" can generate structured prompts for various personas, audiences, and styles with a single function call.

🎯 Learning Objectives
PromptTemplate Mastery: Transitioning from f-strings to PromptTemplate and ChatPromptTemplate.

Structured Prompting: Implementing multi-input systems for complex instructions.

Persona Engineering: Using System and User roles to define LLM behavior.

Input Validation: Building a defensive layer to handle invalid user inputs.

Modular Design: Ensuring prompt templates are reusable across different domains.

🛠️ Tech Stack
Language: Python 3.x

Framework: LangChain (langchain-core)

Environment: Jupyter Notebook / Google Colab

🚀 Tasks Breakdown
1. The Death of Hardcoded Prompts
Converted basic string-based functions into LangChain PromptTemplate objects, ensuring the prompt structure is treated as an asset rather than a hardcoded variable.

2. Multi-Input Systems
Built templates that dynamically accept topic, audience, and tone.

Example: "Explain AI for beginners in a friendly tone."

3. Prompt Variations Engine
Created a system that generates three distinct output styles (Teaching, Interview, Storytelling) for any given technical topic.

4. Chat-Based Persona System
Implemented SystemMessagePromptTemplate and HumanMessagePromptTemplate to simulate different AI behaviors:

Teacher: Simplifies complex concepts.

Interviewer: Asks rigorous technical questions.

Motivator: Encourages persistence and growth.

5. Validation & Safety
Developed a logic layer to validate inputs against predefined allowed values (e.g., audience must be beginner, intermediate, or expert), providing defaults for invalid data.

6. The Unified Prompt Generator
A master function that integrates validation, template selection, and formatting to produce a ready-to-use LLM prompt.

📦 Installation & Setup
Clone the repository:

Bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
Install dependencies:

Bash
pip install -U langchain-core
Run the Notebook:
Open Assignment_LangChain.ipynb and execute the cells to see the dynamic prompt generation in action.

🧪 Expected Output Samples
The engine produces structured outputs such as:

Educational: "Explain Neural Networks clearly step by step."

Persona-based: [SystemMessage(content='You are a patient teacher...'), HumanMessage(content='Topic: Neural Networks')]

Story-driven: "Explain Quantum Computing for a beginner in a fun storytelling style."

🤝 Let's Connect!
This project is part of my journey into Generative AI and LLM Orchestration.

LinkedIn: [Your Name / Profile Link]

GitHub: [Your GitHub Link]
