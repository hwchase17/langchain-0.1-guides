# langchain-0.1-guides

These notebooks show off different functionality associated with `langchain` 0.1.


## Setup

To setup, please install requirements:

```shell
pip install -r requirements.txt
```

Then set required environment variables. 
We will use [OpenAI](https://platform.openai.com/docs/introduction) for our language model, and [Tavily](https://app.tavily.com/sign-in) for our search provider.

```shell
export OPENAI_API_KEY=...
export TAVILY_API_KEY=...
```

We will also use [LangSmith](https://docs.smith.langchain.com/) for observability:

```shell
export LANGCHAIN_TRACING_V2="true"
export LANGCHAIN_API_KEY=...
```

After that, we can start the Jupyter notebook server and follow along from there:

```shell
jupyter notebook
```

## Notebooks

The following notebooks are provided:

- [Observability](observability.ipynb)
- [Composition](composability.ipynb)
- [Streaming](streaming.ipynb)
- [Output Parsing](output_parsers.ipynb)
- [Retrieval](retrieval.ipynb)
- [Agents](agents.ipynb)