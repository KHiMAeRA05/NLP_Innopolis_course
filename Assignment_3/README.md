# NLP Course Assignment 3: Russian Nested Named Entities

The task involves extracting nested named entities. In the training set, most of 
the named entity types occur quite often, and some number of specially
selected types occur only a few times. In the test set, all entity types are
equally represented.

Thus, I had to develop extraction models for nested named entities.

## Content
Report:
-  `report.pdf` - composed report with detailed description of each solution
Datasets:
- `train.jsonl` - training data
- `dev.jsonl` - test data to predict for DEV phase
- `test.jsonl` - test data to predict for TEST phase

Solutions:
- `spancat_sol.ipynb` - 1st solution with using SpanCat library and pretrained model "ru_core_news_lg"

| Solution    | Mention F1  | Mention recall | Mention precision | **Macro F1**|
| ----------- | ----------- | -----------    | -----------       | ----------- |
| spancat_sol | 0.03%       | 0.02%          | 0.03%             | **0.01%**   |
