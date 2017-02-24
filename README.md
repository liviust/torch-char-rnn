# Torch Character-Level RNN

This repo contains code based on Andrej Karpathy's [char-rnn](https://github.com/karpathy/char-rnn) with applications to some homemade datasets.


### Data:

- Trump: A collection of Trump speeches and tweets

- Ruby: A bunch of ruby (programming language) source code collected together as raw text

- Rap: A collection of rap lyrics from a variety of artists cleaned and aggregated as raw text


### Usage:

See Andrej Karpathy's repo for more details, but basically to train you use `th train.lua` and to sample you use `th sample.lua cv/your_checkpoint.t7`.


### Collecting more data:

Within the `data` directory, I've included a few notebooks demonstrating how to collect more training data. Warning: much profanity included in `rap` dataset & notebooks. 
