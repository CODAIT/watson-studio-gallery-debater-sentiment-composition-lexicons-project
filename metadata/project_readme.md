This project includes IBM Debater® Sentiment Composition Lexicons Dataset from the Data Asset Exchange and supporting notebooks. The notebooks teach the user how to read, clean and visualize the data, how to save the cleaned dataset into watson studio project, and how to develop model on sentiment composition lexicons dataset. This sample project contains two notebooks and four related data files. Please run the notebooks in sequential order of their part numbers using a Python 3.7 runtime.

## Resources:

- Dataset homepage: https://developer.ibm.com/exchanges/data/all/sentiment-composition-lexicons/
- Dataset download link: https://dax-cdn.cdn.appdomain.cloud/dax-sentiment-composition-lexicons/1.0.2/sentiment-composition-lexicons.tar.gz

## Data assets 

- `LEXICON_UG.txt`: This data asset contains a list of 66,058 unigrams and their predicted sentiment score.
- `LEXICON_BG.txt`: This data asset contains a list of 262,555 selected bigrams, related pos tags and their predicted sentiment score.
- `SEMANTIC_CLASSES.xlsx:`: This file contains the lists of the semantic classes words for each type.
- `ADJECTIVES.xlsx`: This file contains the lists of the semantic classes words for the gradable adjective pairs.

## Notebooks

Open the **Assets** tab to access and run the following notebooks in order:

- `Part 1 - Data Exploration & Visualization`: This notebook loads, clean, explore and visualize the data files in the project.
- `Part 2 - Model Development`:  This notebook takes text and captures sentiment on the entire text as well as for each sentence in the text.

You can review the completed notebooks [here](https://dataplatform.cloud.ibm.com/projects/f50cd9d7-15ac-4ff4-8ca0-66ac443fd868/assets?context=cpdaas)

## Licenses

- Dataset: [[CC-BY-SA 3.0]](https://creativecommons.org/licenses/by-sa/3.0/)
- Notebooks:  [MIT](https://opensource.org/licenses/MIT)
