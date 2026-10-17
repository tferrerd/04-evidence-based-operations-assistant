# Committed dataset

**Source dataset:** Stanford SQuAD 2.0

**Selection:** Complete public train and development releases, normalized into context and question/answer CSV tables. The hidden test set is not included.

**Data license:** [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). This applies to the data, independently of the project code.

## Sources

- https://rajpurkar.github.io/SQuAD-explorer/
- https://rajpurkar.github.io/SQuAD-explorer/dataset/train-v2.0.json
- https://rajpurkar.github.io/SQuAD-explorer/dataset/dev-v2.0.json

## CSV files

| File | Rows | Bytes |
|---|---:|---:|
| [squad_contexts.csv](raw/squad_contexts.csv) | 20,239 | 15,756,598 |
| [squad_questions.csv](raw/squad_questions.csv) | 142,192 | 21,862,129 |

Attribution: Pranav Rajpurkar, Robin Jia, Percy Liang and the SQuAD/Wikipedia contributors. Replaces Doc2Dial to use an explicitly redistributable source. Paragraph IDs are derived keys; all question, passage and answer text and source split assignments are retained. answers_json preserves multiple answer spans. Impossible means unanswerable from its supplied paragraph, not necessarily unanswerable from the entire corpus. This is general document QA rather than a company policy corpus.

The CSV files contain published observations or their documented format conversion; no training records were invented. Source formats and raw CSV exports are distinguished by the manifest. File checksums and schemas are recorded in [csv-manifest.json](csv-manifest.json).
