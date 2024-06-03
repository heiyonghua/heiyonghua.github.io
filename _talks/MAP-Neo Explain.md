---
title: "MAP-Neo Explain"
collection: talks
type: "Talk"
permalink: /talks/2012-03-01-talk-1
venue: "UC San Francisco, Department of Testing"
date: 2012-03-01
location: "San Francisco, California"
---
# Tokenizer

* base on [sentencepece](https://github.com/google/sentencepiece) to achieve
* use BPE to train
* the training data contain 50B(5,000,000,000) samples from the pre-training corpus
* the maximum length is 64K
* assign higher sampling weights to code, math and high-quality academic data.
* set vocabulary size to 64000, and the max sentence-piece length was set to 16
* set remove extra whitespaces = False

![dd](_talks/picture/[MAP-Neo]Average Compression Rates by Category.png "data")

