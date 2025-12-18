# Tokenization 
Converting raw text into sequence of tokens
- word based tokenization : text is split into individual words
- subword tokenization : some words can be split too

platform.openai.com/tokenizer

```bash
Hey Anand, what are you doing
Tokens :- 8
characters :- 30
```
Each token is having id

## Context Window
- The number of tokens an LLM can consider when generating text, 2.
- The larger the context window more information and coherence
- Large context window require more meomry and processing power
```first factor to look when considering the model```

## Embedding 
Create vectors(array of numerical values) out of text,image and audio
Embedding models can power search applications
