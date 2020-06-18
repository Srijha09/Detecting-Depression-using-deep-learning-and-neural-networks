# Detecting-Depression-using-deep-learning-and-neural-networks
The objective of this project is to provide a comparison study detect depression from the transcripts of clinical interviews between the patients and an animated
virtual interview and accordingly classify them based on the level of depression using various natural language processing and deep learning techniques.

Depression is a disorder that plagues, knowingly or unknowingly, millions of individuals worldwide and it has become a major distress for mankind. A quick and
successful automated diagnosis of depression could be of great help. However, this is an extremely difficult task since a variety of complicated symptoms are reported.
Depression causes cognitive and motor changes that affect speech production: reduction in verbal activity productivity, prosodic speech irregularities and monotonous
speech have all been shown to be symptomatic of depression. Research advancement has been mostly derived from multi-modal fusion and deep learning methods using
the audio, video, and textual information provided in the database. Multimodal fusion refers to combining various modalities or types of information for improving
performance that seems intuitively an appealing task. Research that builds models to detect distressed users has usually used conventional machine learning approaches
such as supporting vector machines, regression, and random forests, with manual extraction and selection features and time-consuming data preparation. However,
traditional machine learning techniques have not been able to capture the context of the words and the sentiments of the textual information to detect distress. There-
fore, deep learning techniques have been known to successfully perform in a number of domains. In this paper, our scope is restricted to using transcripts of the clinical
interviews to detect the depression levels in the patients. We have incorporated transfer learning language models including BERT, ULMFiT, and Elmo.

### Dataset Overview

We are using the DAIC-WOZ dataset, a private dataset for the Depression Detection. It includes text, audio, and video information of 189 interviews designed
to enable the treatment of anxiety, depression, and post-traumatic psychological distress. These interviews were collected as part of a broader initiative to create
a machine agent that evaluates people and recognizes mental illness verbal and nonverbal signs. The interviews were carried out in another room by an animated
virtual interviewer who was controlled by a human. Also, each interview includes the accompanying conversation transcript. In this project, we will be focusing on the
transcript of the interviews. To be able to identify depression and stress, the verbal quality of what a person is saying is vital. There is a lot of textual data flooded to
social media because of increase of social media usage that has given researchers the opportunity to try to examine the emotions from the text. These data may aid in
the analysis of feelings and provide valuable insight into sudden discrepancy in the user’s personality traits as reflected in one’s posts. The participants were also asked
to do a written Patient Health Questionnaire (PHQ8) test to identify depression levels. Each question was scored out of 3 and the total score was for 24. Based on
previous research and experiments, a PHQ score greater than 10 depicted that the person suffered from depression.
