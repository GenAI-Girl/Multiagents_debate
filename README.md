# Multiagents_debate
Multi-Agent Autonomous Debate: Elon Musk vs. Sam Altman Leadership Debate
This project demonstrates an autonomous debate between AI agents, simulating a structured argument on leadership qualities. The agents represent fans of Elon Musk and Sam Altman, with a judge acting as the facilitator to decide the debate winner based on the most compelling arguments.



Project Overview
In this notebook, three AI agents engage in a structured debate:

Elon Musk Fan: An agent that argues in favor of Elon Musk's leadership qualities.
Sam Altman Fan: An agent that defends Sam Altman's leadership approach.
Judge: A facilitator agent who moderates the debate and determines the winner based on the arguments presented.
The debate is designed to showcase autonomous multi-agent interactions where each agent has a distinct perspective and goal, mimicking a real-world structured debate.

Files
Multiagents_Debate.ipynb – Jupyter Notebook with the full code for simulating the debate.
config.yaml – Configuration file (optional) for setting paths and API keys if required by autogen.
Installation
To run this project, ensure you have the following prerequisites:

Python (3.7 or higher)
Required packages:
pyautogen
python-dotenv (for API key management if needed)



How It Works
Agent Setup: Each agent is defined with a distinct personality and goal, guiding their responses during the debate.
Group Chat: Agents interact through GroupChat from autogen, exchanging arguments automatically.
Debate Outcome: The judge uses predefined logic to assess each agent's points and declare a winner, adding realism to the multi-agent interaction.




License
This project is licensed under the MIT License. See the LICENSE file for details.

About the Author
This project is developed by Riitu. Explore more of Riitu's work on GitHub: GenAI-Girl's Repositories.
