# Setup

Run the following commands in your commandline (Windows based)

```
python -m venv .venv
/.venv/Scripts/activate
pip install jupyterlab
```

and then you should be able to run all blocks, with automatic dependency installation

# PDF Data
Data should be placed in a folder called "data" in PDF Files for the reranking usecase

# Cross Encoder Models to remember
https://huggingface.co/deepset/gbert-base-germandpr-reranking
https://huggingface.co/svalabs/cross-electra-ms-marco-german-uncased (This one works the best for now, the above has a positive and negative score in results so prefere this)
