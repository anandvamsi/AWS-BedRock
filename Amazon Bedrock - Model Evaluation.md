# Amazon Bedrock - Model Evaluation

## Method 1 : Using JUdge mode
Feed the Benchmark questions to the model  and compare the the actual benchmark answers with generated answers
There will another model called ```judge model``` which will compare the results and provides model score(BERT Score and FI)

## Method 2: Using Human Evaludation
Employees esp the SME of your company ,SME
Defined metrics and how to evaluation like yes/no..etc

### Automated Metric to Evaluate an FM
#### ROUGE :- Recall Oriented Understudy for Gisting Evaluation
ROUGE-N - Measure the number of matching n grams between reference and generated text
ROUGE-L longest common subsquent between reference and generated text.

### BLEU: Bilingual Evaluation Undestudy
Evaluate the quality of generated text,espeically for translations

### BERT Score
Semantic similarity between generated text.

### Perplexity
how well the model predicts the next token.


## Business Metrics to evaluate a model on
1. User Satisfaction
2. Average Revenue per User
3. Cross Domain Performance
4. Effiency


