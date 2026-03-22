# បងទន្សាយ (bong-ton-sai)
Develop Khmer Small Language Model

# Dataset

- opensource data from [paracrawl](https://paracrawl.eu): [https://www.cs.jhu.edu/~phi/paracrawl/en-km.txt.gz](https://www.cs.jhu.edu/~phi/paracrawl/en-km.txt.gz)
- opensource data from cc100: `load_datasets("statmt/cc100", lang='km')`
- opensource data from wikipedia: `load_datasets("wikimedia/wikipedia", "20231101.km")`
- Data from Oscar: `load_dataset("oscar-corpus/OSCAR-2301", "km", streaming=True)`

# Making small Khmer tokenizer

Experiment notebook: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Kimang18/bong-ton-sai/blob/main/WriteUpTokenizerExperiment.ipynb)

# Research and Info Collection
- conversation with Gemini: https://gemini.google.com/share/a2be8a610c13
