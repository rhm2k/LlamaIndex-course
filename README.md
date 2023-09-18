# LlamaIndex course for beginners

Welcome to the LlamaIndex Beginners Course repository! This course is designed to help you get started with LlamaIndex, a powerful open-source framework for developing applications to train ChatGPT over your private data.

My prior experience, I have built 12 AI apps in 12 weeks hosted on https://thesamur.ai and have onboarded million visitors a month.

## Course Structure

![LlamaIndex](https://pbs.twimg.com/media/FxzWLvpWcAAaXJt?format=jpg&name=medium)

### Getting Started

Videos coming soon https://www.youtube.com/@AnilChandraNaiduMatcha & https://www.youtube.com/@ankursingh9507
.Subscribe to the channel to get latest content

Follow [Anil Chandra Naidu Matcha](https://twitter.com/matchaman11) & [Ankur Singh](https://twitter.com/ankur_maker) on twitter for updates

Join our discord server for support https://discord.gg/FBpafqbbYF

### Prerequisites

This course assumes you have a basic understanding of Python as LlamaIndex is written in it. Familiarity with machine learning concepts and language models is beneficial but not required.

### Contributions

Contributions to this course are welcome! If you have suggestions for improvements, please open an issue or create a pull request.

### Also check

[Langchain Course](https://github.com/SamurAIGPT/langchain-course)

### Notes (RHM) 2023-09-18 
- decided to try it using Colab (as it was designed)

### Notes (RHM) 2023-08-30 
1. created conda env to run locally: llamaindex
2. installed python = 3.11
3. installed llama_index `pip install llama_index`
4. installed ipykernel in order to create an associated kernel `conda install ipykernel`
5. created ipykernel with display name: "Llamaindex"
6. after failure, installed nltk `conda install nltk`

In Introduction:
1. Did not recognize `wget`. Used curl to download the SOTU file

```
#!wget https://raw.githubusercontent.com/hwchase17/chat-your-data/master/state_of_the_union.txt
!curl -o state_of_the_union.txt https://raw.githubusercontent.com/hwchase17/chat-your-data/master/state_of_the_union.txt
```

In Fundamentals:
1. keep getting error re use of SimpleNodeParser(text_splitter) which SHOULD be 'none', but is not accepted.
