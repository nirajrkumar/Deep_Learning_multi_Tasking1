EmoInt-2017 Dataset main page: https://competitions.codalab.org/competitions/16380#learn_the_details-datasets
EmoBank Dataset main page: https://github.com/JULIELab/EmoBank


Dataset details: We evaluate our proposed model on the benchmark datasets of WASSA-2017 shared task on
emotion intensity (EmoInt-2017) (Mohammad
and Bravo-Marquez, 2017), EmoBank (Buechel
and Hahn, 2017) and Facebook posts (Preot¸iucPietro et al., 2016) for the coarse-grained emotion analysis, fine-grained emotion analysis and
fine-grained sentiment analysis, respectively. The
dataset of EmoInt-2017 (Mohammad and BravoMarquez, 2017) contains generic tweets representing four emotions i.e. anger, fear, joy and sadness and their respective intensity scores. It contains 3613, 347 & 3142 generic tweets for training,
validation and testing, respectively. The EmoBank
dataset (Buechel and Hahn, 2017) comprises of
10,062 tweets across multiple domains (e.g. blogs,
new headlines, fiction etc.). Each tweet has three
scores representing valence, arousal and dominance of emotion w.r.t. the writer’s and reader’s
perspective. Each score has continuous range of
1 to 5. For experiments, we adopt 70-10-20 split
for training, validation and testing, respectively.
The Facebook posts dataset (Preot¸iuc-Pietro et al.,
2016) has 2895 social media posts. Posts are annotated on a nine-point scale with valence and
arousal score for sentiment analysis by two psychologically trained annotators. We perform 10-
fold cross-validation for the evaluation.
Few example scenarios for the problems of
emotion analysis (coarse-grained & fine-grained)
and sentiment analysis (fine-grained) are depicted
in Table 1. In the first example shown in Table 1a,
emotion ‘joy’ is derived from the phrase ‘died from
laughter’ which is intense. However, the emotion
associated with the second example which contains similar phrase ‘died from cancer’ is ‘sadness’. The third example expresses ‘fear’ with
mild intensity, whereas, the fourth example conveys ‘anger’ emotion with relatively lesser intensity.
Examples of fine-grained emotion analysis are
listed in Table 1b. Each text is associated with psychologically motivated VAD (Valence, Arousal &
Dominance) scores. Valence is defined by pleasantness (positive) or unpleasantness (negative) of
the situations. Arousal reflects the degree of emotion, whereas, Dominance suggests the degree of control over a particular situation. Similarly, Table
1c depicts the example scenarios for fine-grained
sentiment analysis.