## Santiago Zubieta
#### 2024, 2025

## 5-Day Gen AI and Agents Intensive Courses
These notebooks are from the [2024 GenAI course](https://www.kaggle.com/discussions/general/545082) and the [2025 Agents course](https://www.kaggle.com/learn-guide/5-day-agents).

All steps on these notebooks were ran locally on my machine, with slight modifications to make them work outside of the Kaggle environment.

First there's some notebooks from the 2024 version: **5-Day Gen AI Intensive Course**
Then there's the notebooks from the 2025 version: **5-Day AI Agents Intensive Course with Google**


### 2024_Day_01
Reading: [“Foundational Large Language Models & Text Generation” whitepaper](https://www.kaggle.com/whitepaper-foundational-llm-and-text-generation)

On the first day the following things are explored:
- Sending simple prompts
- Creating conversations
- Explore parameters like temperature and top_p
- Zero shot, one shot, and few shot prompting
- Chain of thought in models
- Reason and act
- Thinking mode in models
- Prompting to generate or explain code
- Code execution

### 2024_Day_02
Reading: [“Embeddings and Vector Stores/Databases” whitepaper](https://www.kaggle.com/whitepaper-embeddings-and-vector-stores)

On the second day the following things are explored:

#### Document Q&A with RAG
- Storing documents embeddings in ChromaDB
- Querying the vector database
- Simplify response document contents

#### Exploring text similarity with embeddings
- Calculare similarity scores with semantic similarity
- Visualize similarities of all documents in a heatmap
- See the ranking of similarities for a given entry

#### Build a neural classification network with Keras using embeddings
- Finding an appropriate dataset (e.g. 20 newsgroups text dataset)
- Prepare and sample a dataframe with some desired categories using Pandas
- Use tqdm for creating a progress bar when creating a compute intensive dataframe (e.g. creating embeddings)
- Use Keras to create a classifier model to train with the embeddings and the corresponding category mappings
- Predict a certain text category by using its embeddings with the embeddings trained model

### 2024_Day_03
Reading: ["Agents" whitepaper](https://www.kaggle.com/whitepaper-agents)

On the third day the following things are explored:

#### Function calling with Gemini API
- How to create a simple database using SQL lite
- Define functions that can be called on this database e.g. listing tables, describing, executing a query
- Provide a model with these functions/tools
- Prompt a model and observe how these tools are called and how it generates new code e.g. SQL queries to execute

#### Building an agent with LangGraph
- How to define an agent graph with chatbot and user nodes
- Create transitions between nodes in the graph
- Add conditional transitions
- Add function/tool nodes
- Try a loop of user input, model responses, and conditional tool usage!

### 2024_Day_04
Reading: [“Solving Domain-Specific Problems Using LLMs” whitepaper](https://www.kaggle.com/whitepaper-solving-domains-specific-problems-using-llms)

On the fourth day the following things are explored:

#### Google Search grounding with the Gemini API
- Use Google Search as a tool for grounding the model beyond its training cutoff
- Access supporting metadata such as reference links and confidence scores
- Use other tools such as code execution tool to generate code for example to plot data

### 2024_Day_05
Reading:[“MLOps for Generative AI” whitepaper](https://www.kaggle.com/whitepaper-operationalizing-generative-ai-on-vertex-ai-using-mlops).

No labs this day, but a code walkthrough and live demo of [goo.gle/e2e-gen-ai-app-starter-pack](goo.gle/e2e-gen-ai-app-starter-pack)

### 2025_Day_01
On the first day the following things are explored:

#### Introduction to agents
- How to set up a basic agent with ADK (Agent Development Kit)
- Allow the agent to use Google Search as a tool
- Use runners as orchestrators
- Use ADK web interface

#### Multi-agent architecture
- Define a root agent that can use as tool other specialized agents
- Create a sequential pipeline or assembly line for reliable ordered steps
- Create a parallel pipeline for independent tasks
- Create a iterative improvement / loop pipeline

### 2025_Day_02
On the second day the following things are explored:

#### Agent tools
- Creating custom tools
- Generate code in tools to do math (e.g. to overcome LLMs math unreliability)
- Difference between using function and agent tools, and sub agents

#### Agent tools patterns, best practices, and MCP
- Creating an agent that uses tools from an MCP server
- Connect to external MCP servers e.g. Kaggle, Github

### 2025_Day_03
On the third day the following things are explored:

#### Sessions and memory
- How to maintain state in agents using sessions
- Persisting sessions in databases
- Compacting session data to save storage space
- Storing relevant values in session state using tools

### 2025_Day_04

### 2025_Day_05




