# Predusk_ML_Assignment2
##GPT-2 Text Generation using Hugging Face

##  Features

- Generate text using GPT-2 with different temperatures (0.7 and 1.0)
- Save and compare generated outputs
- Calculate perplexity to evaluate model confidence

 ## Install dependencies
 
```bash
pip install transformers torch matplotlib
```

## How to Run
``` bash
python predusk_ml_ass2.py
```
##Output Files

- output_temp_07.txt – GPT-2 output with temp=0.7

- output_temp_10.txt – GPT-2 output with temp=1.0

- predusk_ml_ass2.py – Python script

- Predusk_ML_ass2.ipynb – Jupyter Notebook

## Results

Temperature 0.7: Produced more fluent, logical continuation

Temperature 1.0: Generated text was more surprising but had some oddities or grammar issues

## Perplexity Scores 
Temperature 0.7 ->11.931893348693848 
Temperature 1.0 -> 17.67621612548828

### Lower perplexity indicates higher confidence and generally better fluency.

## Interpretation
Response with temperature 0.7 is good as compared to response with temperature 1.0







