# GPT-3.5-Turbo-Diversity-Investigation
We analyzed to what extent GPT-3.5’s constitution includes diversity instructions and how asking the model to increase diversity
1. was interpreted by the model, and
2. to what extent changed the results.

To accomplish this, 3 prompts were run 100 times each (asynchronously with [a third-party API](https://github.com/GrowthEngineAI/async-openai)), asking the model to generate 100 “United States Characters” for a fictional novel, firstly with no specific instruction for diversity, secondly with added language requesting accuracy with respect to United States’ demographics, and finally with added language to request diversity. Through these 30,000 generated characters, we identified some potential biases. In each case, the ethnicities of the groups varied, the number of males and females stayed equal with some variance in the non-binary population, and the age proved to be surprisingly consistent and relatively firmly bound between the ages of 15 to 55. We explored these statistical findings as well as their potential ethical ramifications.
