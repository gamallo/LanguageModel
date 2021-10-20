# LanguageModel
N-Gram Language Models

## How to use
###Model of trigrams
`zcat bnc_corpus.txt.gz |sh run_train_trigrams.sh bnc`

###Model of bigrams
`zcat bnc_corpus.txt.gz |sh run_train_bigrams.sh bnc`

## Output
It creates a `st` file called `trigrams_bnc.st`
