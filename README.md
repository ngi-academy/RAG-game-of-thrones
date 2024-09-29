RAG Techiques on Game Of Thrones Dataset

## Data
[source](https://www.kaggle.com/datasets/dasbootstrapping/game-of-thrones-episode-data)

## Out-of-box taste of RAG Implementation

### Game of Thrones Data Exploration with LangChain & Pandas 🐉

[This Jupyter notebook](01_simple_rag.ipynb) used to explore Game of Thrones episodes data using natural language queries, powered by LangChain, Pandas, and OpenAI's LLMs. By using the `create_pandas_dataframe_agent`, users can ask plain English questions and get meaningful insights from the GoT dataset without manually writing complex queries.

#### What's inside?

**LangChain setup:** Seamless integration of OpenAI models for query handling.
**Pandas dataframe analysis:** Automatic query generation and execution for GoT episode data.
**End-user queries:** Handling varying levels of query complexity, from episode details to reasoning-based questions.
**Limitations & Hallucinations:** Observations on when and why the LLM might provide unexpected results, especially when working with large datasets.

#### Key Observations:

**Natural Language Queries:** LLM interprets user requests and generates corresponding Pandas queries.
**Misspelling Handling:** The LLM can correct and understand common misspellings.
**Limitations:** Larger datasets can lead to hallucinations or missing clarifications in complex queries.
**Token Usage & Costs:** Overall token consumption with a total cost of `$0.02` for `28` OpenAI requests.

For a detailed explanation of the experiment, observations, and conclusions, check out the full blog here: [Exploring Game of Thrones Data with LangChain & Pandas]().

Feel free to clone, run, and experiment with the notebook! 🚀
