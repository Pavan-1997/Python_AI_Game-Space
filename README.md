# Python_AI_Game-Space

Python-based AI Space Simulator Game! This interactive text-based adventure allows players to guide a space traveler named Nova on a quest to find the legendary Star Crystal. The game dynamically adapts to players' decisions, creating a branching narrative with various outcomes.


## Architectural Diagram 

![architecture-diagram](https://github.com/piyushsachdeva/Python-AI-Space-Exploration-Game/assets/40286378/41d13d17-6253-4f23-9f93-acb6153dbd07)

## Prerequisites

Before getting started, ensure we have the following:

- Python 3.7 or higher
- OpenAI API Key
- DataStax Astra Database (Cassandra DB)

## Installation

### 1. Install dependencies

```bash
pip3 install cassandra-driver openai langchain cassio
```

### 2. Replace variables

Replace the following variables in `tutorial.py` with your values:

- `OPENAI_API_KEY` with your OpenAI API Key.
- `ASTRA_DB_KEYSPACE` with your Astra DB Keyspace.
- `secure-connect-file.zip` with the zip file name you downloaded from Astra DB.
- `connect-token.json` with the JSON file name you downloaded from Astra DB.
   
### 3. Run the program

```bash
python3 script.py
```

## Implementation

![Screenshot 2024-01-06 194838](https://github.com/Pavan-1997/Python_AI_Game-Space/assets/32020205/888c16f8-400b-4f87-b94a-74412d73634c)
