## Additional - 1 - Continuous Learning: 

Additional-1 requirements are a set of requirements that must be met <b>in addition to baseline if an AI/ML application is continuously learning from a dynamic data source or feedback loops. </b>

There are 6 questions in total that should be filled out by the development team/ML engineer for the application. 

Questions highlighted in <b>bold</b> are those which require minor testing before answering the question.

| Category      | Description |
| ----------- | ----------- |
| **Data**  |   <b>Have you tested for data drift?</b> <br> _Data drift occurs when new data causes a change in distribution and results in inaccurate predictions. Data drift can be of two types: feature drift (when the input data changes) or label drift (when the labels change causing prediction shifts)._     |
|    | Are there measures in place to prevent real-time data collection channels from failing? <br> _Data collection channels could be APIs and links that connect to an updating training source or it could also be the feedback loop._       |
|    | When datasets from external sources are updated, is there a system in place to process the new data on time?      |
|    | Can the updated training data be randomized, sliced, or modified in any way that could distort the model's inference? If the model uses randomness, is the randomness generator recorded and protected?  |
|    | Can you provide an example of real input data that is not present in your training data? Do you have a way for the model to handle this data?        |
||
| **Model**   | <b> Have you tested for concept drift? </b> <br> _Concept drift happens when the relationship between the feature set and the predicted outcome changes. For example, let's consider income was a predictor of home purchasing power. However, due to concept drift, income no longer significantly determines home purchasing power._      |
||
