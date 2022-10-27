# twitter_sentiment_analysis
Dataset containing Twitter IDs from accounts related to TeleCommunications, Healthcare, and e-Commerce, and the respective binary and multi-class sentiment classifications.

The annotation was performed manually and achieved moderate agreement between the annotators. The multi-class labels range from Very Negative (-2) to Positive (1), and have an average of 0.48+-0.13 using the Fleiss metric, and an average of 0.66+-0.16 using the Krippendorff. The binary labels represent Negative and Non-Negative sentiment and have an average of 0.67+-0.16 in both metrics.

This dataset includes the identification of each speaker as an USER or a SERVICE, and the identification of each dialogue as a group of tweets that share the same DIALOG_ID.

Besides the median of the grouped annotations for each sentence (in binary and multiclass scenarios), we include the independent labels from each annotator ("Annot_1_M" identifies annotator number 1 in the multiclass scenario, "Annot_2_B" identifies annotator number 2 in the binary scenario).
