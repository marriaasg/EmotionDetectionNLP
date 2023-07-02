# EmotionDetectionNLP

How do you feel, my dear 

Recently, emotion detection in text has received attention in the literature on sentiment analysis. Detecting emotions is important for studying human communication in different domains, including fictional scripts for TV series and movies. The project aims at studying fictional scripts of several movies and TV series under the emotional profile. In particular, the task of the project is threefold:

Create a model to predict emotions in text using available datasets as EmoBank or WASSA-2017 or Emotion Detection from Text as training sets (see below);
Emotions may be represented either as categorical classes or in a continuous space such as Valence-Arousal-Dominance (see for example Warriner, A. B., Kuperman, V., & Brysbaert, M. (2013). Norms of valence, arousal, and dominance for 13,915 English lemmas. Behavior research methods, 45(4), 1191-1207.)
Exploit the model to study an emotional profile of the main characters in one of the movies included in the Cornell Movie--Dialogs Corpus;
Study how this emotional profile changes in time along the evolution of the movie story and how it is affected by the various relations among the different characters.
Dataset
For training and validating the model, see EmoBank and WASSA-2017 and Emotion Detection from Text.

For the movie and TV series dialogues, see the Cornell Movie-Dialogs Corpus. Danescu-Niculescu-Mizil, C., & Lee, L. (2011). Chameleons in imagined conversations: A new approach to understanding coordination of linguistic style in dialogs. arXiv preprint arXiv:1106.3077.

Evaluation strategy
Cross-validation using the training set

References
Binali, H., Wu, C., & Potdar, V. (2010, April). Computational approaches for emotion detection in text. In 4th IEEE International Conference on Digital Ecosystems and Technologies (pp. 172-177). IEEE. link
Sven Buechel and Udo Hahn. 2017. EmoBank: Studying the Impact of  Annotation Perspective and Representation Format on Dimensional Emotion  Analysis. In EACL 2017 - Proceedings of the 15th Conference of the  European Chapter of the Association for Computational Linguistics.  Valencia, Spain, April 3-7, 2017. Volume 2, Short Papers, pages 578-585. Available: http://aclweb.org/anthology/E17-2092
The WASSA-2017 Shared Task on Emotion Intensity webpage provides a dataset of Tweets annotated with emotions (i.e., anger, fear, joy, sadness) and a measure of intensity of the emotion. 


Usefull links:
Link Text: Cornell Movie--Dialogs Corpus
Link URL: https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html

Link Text: EmoBank
Link URL: https://github.com/JULIELab/EmoBank

Link Text: WASSA-2017
Link URL: http://saifmohammad.com/WebPages/EmotionIntensity-SharedTask.html

Link Text: Emotion Detection from Text
Link URL: https://www.kaggle.com/pashupatigupta/emotion-detection-from-text

Link Text: Cornell Movie-Dialogs Corpus
Link URL: https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html

Link Text: link
Link URL: https://ieeexplore.ieee.org/abstract/document/5610650

Link Text: http://aclweb.org/anthology/E17-2092
Link URL: http://aclweb.org/anthology/E17-2092

Link Text: webpage
Link URL: http://saifmohammad.com/WebPages/EmotionIntensity-SharedTask.html




I used Google Colab. So if you want to run the code, you need to import the datasets into Google Drive and then change the directory in the code based on your directory.
