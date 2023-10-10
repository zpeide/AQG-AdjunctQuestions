# AQG-AdjunctQuestions

This is the repository of data and analysis code for the paper submission "On the Effects of Automatically Generated Adjunct Questions for
Search as Learning".

---
## Data

Under the [data](data/) folder, you will find the following files:

- [`trec-car.qa.jsonl`](data/trec-car.qa.jsonl): All documents and generated questions used in the experiment.
- [`vocab.json`](data/vocab.json): Vocabulary file with the terms used for the VKS pre-, post- and delay-tests.
- [`sampled_qa_items.jsonl`](data/sampled_qa_items.jsonl): Sampled questions, as well as SQuad questions used for quality evaluation.
- [`prolific_user_study_data.json`](data/prolific_user_study_data.json.tar.gz): User study data collected during the experiments on Prolific.

---

The code for reproducing the results reported in the submission can be found at [this analysis notebook](Analysis.ipynb)
