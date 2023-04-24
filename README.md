# Identify-Genre-Song-Machine-Learning
 
Project: Music Genre Prediction from Audio, Metadata and Text Features!

Overview:
The goal of this project is to build and critically analyse some supervised Machine Learning algorithms, to automatically identify the genre of a song on the basis of its audio, metadata and textual features. That is, given a list of songs, my job is to implement one or more Machine Learning model(s), train them using the training dataset, and evaluate using the test validation and test dataset.
This project aims to reinforce the largely theoretical Machine Learning concepts around models, data, and eval- uation covered in the lectures, by applying them to an open-ended problem. I will also have an opportunity to practice my general problem-solving skills, written communication skills, and creativity.

Deliverables:
(a) (1) One or more programs, written in Python, which implement Machine Learning models, make predictions, and evaluate and (2) a README file that briefly details my implementation.
(b) report, of 1800±10% words

Dataset:
Each song (instance) is represented through a large set of features (described in detail in the README), and listed in the features.csv files. Each song is labelled with a single genre tag, which is provided in the labels.csv files.
The data files are available via the LMS. I will be provided with a set of training, validation and test instances. The files are provided in csv format, which stands for comma-separated values.
• train features.csv: Contains features of 7678 training instances.
• train labels.csv: Contains a single genre label for each training instance
• valid features.csv: Contains features of 450 validation instances.
• valid labels.csv: Contains a single genre label for each validation instance. • test features.csv: Contains features of 428 test instances.
Each song in the data set is indexed with a unique trackID. We provide three different types of features. Details are provided in the README file, as well as the references listed under Terms of Use:
• Metadata features: For each song, we provide its title, loudness, tempo, key, mode, duration, and time_signature .
• Text features: For each song, we provide a list of tags representing the words that appeared in the lyrics of the song and are human annotated (such as ‘dance’, ‘love’, or ‘never).
• Audio features: We provide 148 pre-computed audio features that were pre-extracted from the 30 or 60 second snippets of each track, and capture timbre, chroma, and ‘Mel Frequency Cepstral Coef- ficients’ (MFCC) aspects of the audio. Each feature is continuous and the values are not interpretable.
Each song is labelled with its genre, i.e., with a single label from one of 8 possible genre labels:
‘Soul and Reggae’, ‘Pop’, ’Punk’, ‘ Jazz and Blues’, ‘Dance and Electronica’, ‘Folk’, ‘Classic Pop and Rock’, ‘Metal’

Task:
I will develop Machine Learning models which predict the music genre based on a diverse set of features, capturing audio features of the track, as well as song metadata such as its title, key, duration, and textual tags representing the words in the song lyrics. I will implement and analyze different Machine Learning models in their performance; and explore the utility of the different types of features for music genre prediction.

I will use a hold-out strategy to evaluate the trained model using a validation, and a test set:

1. The training phase: This will involve training my classifier(s) and parameter tuning where required. I will use the train features and train lyrics files.

2. The validation phase: This is where I observe the performance of the classifier(s). The validation data is labelled: I  run the classifier that I built in the training phase on this data to calculate one or more evaluation metrics to discuss in my report. This phase will help me to find the best model that can be used for the testing phase.

3. The testing phase: The test data is unlabeled; I use my preferred model to produce a prediction for each test instance.

Report:
The report is 1800±10% words in length and provide a basic description of:
1. The task, and a short summary of some related literature
2. What you have done, including any learners that you have used, or features that you have engineered
3. Evaluation of your classifier(s) over the validation dataset
4. Contextualises the behaviour of the method(s), in terms of the theoretical properties
5. Attempt some error analysis of the method(s)
6. A bibliography, which includes Bertin-Mahieux et al. (2011), as well as A. Schindler and A. Rauber (2012), and other related work