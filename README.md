# បងទន្សាយ (bong-ton-sai)
Develop Khmer Small Language Model

# Dataset

- opensource data from [paracrawl](https://paracrawl.eu): [https://www.cs.jhu.edu/~phi/paracrawl/en-km.txt.gz](https://www.cs.jhu.edu/~phi/paracrawl/en-km.txt.gz)
- opensource data from cc100: `load_datasets("statmt/cc100", lang='km')`
- opensource data from wikipedia: `load_datasets("wikimedia/wikipedia", "20231101.km")`
- Data from Oscar: `load_dataset("oscar-corpus/OSCAR-2301", "km", streaming=True)`
