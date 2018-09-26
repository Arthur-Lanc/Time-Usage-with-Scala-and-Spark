# Time-Usage-with-Scala-and-Spark
observe how do people allocate their time between three kinds of activities.

The dataset is provided by Kaggle and is documented here:

https://www.kaggle.com/bls/american-time-use-survey

Our goal is to identify three groups of activities:

* primary needs (sleeping and eating),
* work,
* other (leisure).

|     working |    sex |    age | primaryNeeds | work | other |
| ----------- | ------ | ------ | ------------ | ---- | ----- |
| not working | female | active |         12.4 |  0.5 |  10.8 |
| not working | female |  elder |         10.9 |  0.4 |  12.4 |
| not working | female |  young |         12.5 |  0.2 |  11.1 |
| not working |   male | active |         11.4 |  0.9 |  11.4 |
| not working |   male |  elder |         10.7 |  0.7 |  12.3 |
| not working |   male |  young |         11.6 |  0.2 |  11.9 |
|     working | female | active |         11.5 |  4.2 |   8.1 |
|     working | female |  elder |         10.6 |  3.9 |   9.3 |
|     working | female |  young |         11.6 |  3.3 |   8.9 |
|     working |   male | active |         10.8 |  5.2 |   7.8 |
|     working |   male |  elder |         10.4 |  4.8 |   8.6 |
|     working |   male |  young |         10.9 |  3.7 |   9.2 |

Score | School level | Notes
------------ | ------------- | -------------
100.00-90.00 |	5th grade |	Very easy to read. Easily understood by an average 11-year-old student.
90.0–80.0 |	6th grade |	Easy to read. Conversational English for consumers.
80.0–70.0 |	7th grade |	Fairly easy to read.
70.0–60.0 |	8th & 9th | grade	Plain English. Easily understood by 13- to 15-year-old students.
60.0–50.0 |	10th to 12th grade |	Fairly difficult to read.
50.0–30.0 |	College |	Difficult to read.
30.0–0.0 |	College graduate |	Very difficult to read. Best understood by university graduates.
