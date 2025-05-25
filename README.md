<h1>Cyberbullying Detection in Tweets using Machine Learning Algorithms and Convolutional Neural Network</h1>

<h2>Introduction</h2>
Cyberbullying occurs when a group or individual repeatedly and intentionally does an aggressive and harmful act via electronic means to victims who cannot easily defend
themselves (Ademiluyi et al., 2022). It can happen in multiple online spaces such as social media, instant messaging, and email. The specific forms of cyberbullying (Lowry et al., 2016)
include sending insulting messages to the victim, spreading rumors about them to destroy their reputation, or gathering private information about the victim and threatening to release that
information if the victim does not comply with the perpetrator. People are usually cyberbullied for age, ethnicity, gender, religion, and sexuality (Zalaquett & Chatters, 2014), and less powerful or
influential groups are usually on the receiving end of the bullying. According to Lowry et al. (2016), anonymity plays a big role in cyberbullying. By remaining anonymous, bullies are distant
from those they attack, and bullies think they are less likely to be responsible for their actions. In a certain way, bullying in social media is also more harmful than traditional bullying due to its
potential for spreading on a huge scale. This study aims to extract insights on how word usage is related to type of cyberbullying. It allows social media developers to enact policies so that their
applications become more vigilant on posts that contain these words.  

<h2>Methods and Dataset</h2>
The dataset contains tweets and their classification with regards to bullying, and it is sourced from Kaggle. The bullying may be in the aspect of gender, religion, age, ethnicity, or others.
There are also tweets that are tagged as not_cyberbullying. The team performed data preprocessing techniques in the text data such as lemmatization, removal of stopwords, and other characters
which are deemed unimportant for this use case. Afterwards, we performed Exploratory Data Analysis to provide visualizations on the trend of cleaned tweets for each category. Lastly, a Convolutional
Neural Network with 4 hidden layers were constructed to classify the tweets into their known labels.

<h2>Results</h2>
The CNN Model employed in the project was able to capture a 99.84% accuracy onto the training dataset and 90.20% accuracy onto the testing dataset. This shows how the model can
accurately predict the classification of a given tweet as to whether it is a cyberbullying tweet or not. 

<h2>Discussion</h2>
This project is very useful in addressing the issue of cyberbullying that is rampant in various social media platforms nowadays. Given how millions of new posts are made by
accounts every single day, human detection and intervention for cyberbullying may not be feasible. As such, it is important to rely on models like this for automatic detection and perform
the appropriate action. By analyzing text data, our model can predict whether the text could potentially be offensive and as such, the social media platform utilizing it may automatically
restrict the said text. On top of this, it also detects the category of cyberbullying, which can be used for a more specific and tailored warning towards the user to better ensure its effectiveness
so as for the person to not repeat the same offense again.

<h2>Credits</h2>
This project was created by Rafael Acuna, Aldie Alejandro, and Sted Cheng as their final requirement for the course **MATH 103.1: Predictive Modeling in Text** taken in 
the First Semester of School Year 2023-2024.

<ul>
<h3>Files</h3>
  The attached files in this repository are as follows:
  <li><code>N-grams visualization.ipynb</code>: Python code for Exploratory Data Analysis</li>
  <li><code>Machine Learning and Neural Network.ipynb</code>: Python notebook containing CNN and Machine Learning models used to analyze cyberbullying tweets</li>
</ul>
