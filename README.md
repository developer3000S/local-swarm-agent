Step by step guide to install and run this yourself! 
Prerequisites: Python and Git (easy to Google and install in a minute) 
1. Install Ollama (link below) 
2. Pull the models you want to use with the "ollama pull [model ID]" command (link to tool models below) 
3. Clone the repo:
git clone https://github.com/developer3000S/local-swarm-agent.git
4. 
cd local-swarm-agent 
5. 
python3 -m venv venv 
6. 
source venv/bin/activate # on Mac/Linux Activate virtual environment (on Windows: .\venv\Scripts\activate) 
7. 
pip install -r requirements.txt
8. 
cp .env.example .env # and set your default Ollama model 
9. 
python3 load_sql_data.py # (loads the test data, covered in previous video) 
10. 
python3 run.py
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 

Link to the code for the SQL agent swarm: https://github.com/coleam00/ai-agents-masterclass/tree/main/local-swarm-agent
Install Ollama: https://ollama.com/ 
List of Ollama models that support function calling: https://ollama.com/search?c=tools 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 
