# Extended dataset moved to new a repository:
https://github.com/NLP-CISUC/TwitterDialogueSAPT

# Twitter Dialogues for Sentiment Analysis
The Twitter Dialogues for Sentiment Analysis corpus contains Twitter IDs from dialogues, to be used in the evaluation of Sentiment in dialogue systems.

The Twitter accounts used are related to TeleCommunications, Healthcare, and e-Commerce.

The annotation was performed manually and achieved moderate agreement between the annotators. 
The multi-class labels range from Very Negative (-2) to Positive (1), and have an average of 0.48+/-0.13 using the Fleiss metric, and an average of 0.66+/-0.16 using the Krippendorff. 
The binary labels represent Negative and Non-Negative sentiment and have an average of 0.67+/-0.16 in both metrics.

They are represented in an .xlsx file containing the following eleven headers:

- Tweet_ID: ID of each Tweet
- Dialog_ID: ID representing the Tweets belonging to the same dialogue
- Median_Multiclass: Median of the 3 annotations for the multi-class scenario
- Median_Binary: Median of the 3 annotations for the binary scenario
- Annot_1_M: Annotation of annotator 1 for the multi-class scenario
- Annot_2_M: Annotation of annotator 2 for the multi-class scenario
- Annot_3_M: Annotation of annotator 3 for the multi-class scenario
- Annot_1_B: Annotation of annotator 1 for the binary scenario
- Annot_2_B: Annotation of annotator 2 for the binary scenario
- Annot_3_B: Annotation of annotator 3 for the binary scenario
- Speaker: Identification of the author of the tweet as USER or SERVICE

# Versions

twitter_ids_sentiment (october 2022): First version of the corpus, comprising 381 dialogues and 954 utterances, involving accounts related to TeleCommunications, Healthcare, and e-Commerce.

# How to Cite

A paper on the creation of the first version of this corpus and some experiments with this corpus was published in the Proceedings of [IberSPEECH 2022](http://iberspeech2022.ugr.es/). See BibTex:

```latex
@inproceedings{carvalho22_iberspeech,
  author={Isabel Carvalho and Hugo Gonçalo Oliveira and Catarina Silva},
  title={{Sentiment Analysis in Portuguese Dialogues }},
  year=2022,
  booktitle={Proc. IberSPEECH 2022},
  pages={176--180},
  doi={10.21437/IberSPEECH.2022-36}
}
```
