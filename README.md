# Data Generation Using Large Language Models for Text Classification

This is my analysis and study on the research paper: Data Generation Using Large Language Models for Text Classification


**Research Paper:** https://arxiv.org/pdf/2407.12813 

**Medium Article:** https://medium.com/@soumyabharathi.vetukuri/data-augmentation-for-text-classification-using-large-language-models-dcc083eb66ce  

**Presentation:** https://www.slideshare.net/secret/gltkLkNShqShCQ  

**Youtube Link:** https://youtu.be/Uf_hKSXpDMI  


[![Short Story PPT](https://img.youtube.com/vi/Uf_hKSXpDMI/0.jpg)](https://www.youtube.com/watch?v=Uf_hKSXpDMI) 

# Key Learnings:

**Data Augmentation:** Method that utilizes existing data to generate additional training data without collecting more data.

![data augmentation](https://github.com/user-attachments/assets/3df4566b-0cc1-49dc-af6a-e8d03f3e8c4e)

* Generating Topics and Prompts for the LLMs like Chat-GPT for Data Generation using Zero-Shot, One-Shot, Few-Shot and Zero-Shot Topic In-Context Methods.
* **Tasks:** SST-2 (sentiment analysis), Twitter Emotional Classification(EMO), New York Times News Classification(NYT), Review(Amazon Review Classification), Recognizing Textual Entailment(RTE) and BoolQ (binary question answering)
* **Metrics:** Accuracy, F1 and Macro F1 Scores
* **Model:** ROBERTa

# Key Findings:

* Raw Data Mixed with Synthetic Data helps better data generation.
* Difference in data generation when including Trivial Questions in the prompts.
* Synthetic Data works best in low-resource setting.
* Diversity in the data matters.
* Though large amount of data is used, there is no gaurantee it generates related data.

