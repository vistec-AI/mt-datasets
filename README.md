# mt-news
Collecting bi-/tri-lingual sources for MT workstream

This repo collects en-th and zh-th parallel corpus as part of the MT workstream. The goal is to have at least 600,000 sentences for each pair from new sources:

| sources | estimated sentences | en-th | zh-th | remarks |
|-----------------------------|---------------------|-------|-------|------------|
| [Indo-Pacific Defense Forum](http://apdf-magazine.com/) | 45,300 | ◯ | ◯ | apdf.ipynb |
| [Ministry of Foreign Affiars](http://mfa.go.th/main/en/news3) | 27,750‬ | ◯ | ✕ | mfa.ipynb |
| [Learning Thai with Post Today](https://www.bangkokpost.com/learning/learning-news/333366/learning-thai-with-post-today-archive) | 485 | ◯ | ✕ |  |
| [NESDB](https://www.nesdb.go.th/main.php?filename=develop_issue) | 12,000 | ◯ | ✕ | 10-12th plans in pdf; others in scans |

## English Datasets
We will also translate English datasets for standard NLP tasks so that they are not only used for machine translation but also other purposes.

| sources | task | sentences | license | remarks |
|--------------------------------------------------------------------------------------------------------------------------------------------|---------------------|-----------|--------------|------------------------------------------------------------------------------------------------------------------|
| [Stanford Question Answering Dataset (SQuAD)](https://rajpurkar.github.io/SQuAD-explorer/) | question_answering | 254,309 | CC BY-SA 4.0 | 123,990 sentences from contexts and 130,319 sentences from questions |
| [Coached Conversational Preference   Elicitation   (CCPE)](https://ai.google/tools/datasets/coached-conversational-preference-elicitation) | conversation | 11,971 | CC BY-SA 4.0 | assuming one sentence per uttrance |
| [Taskmaster-1](https://storage.googleapis.com/dialog-data-corpus/TASKMASTER-1-2019/landing_page.html) | conversation | 301,876 | CC BY-SA 4.0 | 169,469 sentences from self-dialog and 132,407 from Wizard-of-Oz   dialogues; assuming one sentence per uttrance |
| [COCO 2015 Image   Captioning](http://cocodataset.org/#captions-2015) | image_captioning | 414,113 | CC BY-SA 4.0 |  |
| [Microsoft Research Paraphrase   Corpus](https://www.microsoft.com/en-us/download/details.aspx?id=52398) | paraphrasing | 11,600 | [MIT](https://github.com/microsoft/nlp/blob/master/LICENSE) |  |
| [Quora Question Pairs](https://www.quora.com/q/quoradata/First-Quora-Dataset-Release-Question-Pairs) | semantic_similarity | 404,290 | [non-commercial](https://www.quora.com/q/quoradata/First-Quora-Dataset-Release-Question-Pairs) |  |

## Resources
* [OPUS](http://opus.nlpl.eu/)
