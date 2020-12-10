***Project Members***

-Nicholas Calkins

-Khoa Le

-Matthew Levitt

-Alex Liu

***Report***

-Report name: Reddit_Science_Post_Classification_Calkins_Le_Levitt_Liu.pdf

***Code***

**Reddit Dataset Generation: https://colab.research.google.com/drive/1oiWioQ2p0d43CMu4N4ieO2YpbNljs-Pf

-Code that shows the generation of datasets for use in this project. Describes the logic of collating and curating data from Reddit.

-Dependencies: psaw, pandas, copy

**RoBERTa for Reddit Science Post Classification: https://colab.research.google.com/drive/1qYN50460xmTs8t3N3oHUtt4DuXnd7hjL?usp=sharing

-Code that uses Huggingface's Transformer RoBERTa for the purpose of classifying Reddit Science posts according to topic

-Dependencies: pytorch-transformers, transformers, numpy, pandas, os, nltk, torch, requests, sklearn

**Multinomial Naive Bayes for Reddit Science Post Classification: https://colab.research.google.com/drive/1qi5Zt9ARIpypBwJhwPLI9rGiLUjbZEj5

-Code that uses Scikit Learn utilities, including Multinomial Naive Bayes, for the purpose of classifying Reddit Science posts according to topic

-Dependencies: pytorch-transformers, transformers, numpy, pandas, os, nltk, torch, requests, sklearn

***Data

-All datasets generated: https://github.com/NTCalkins/content_predictor/

-Main dataset: reddit_science_posts_quality250_categories12.csv
