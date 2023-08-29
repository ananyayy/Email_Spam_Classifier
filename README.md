# Email_Spam_Classifier 

##  Objective:
The main objective of this Spam Classifier is to classify Spam Emails from Non-Spam [Ham] Emails using Machine Learning techniques

## Overview:
<ul>
<li>This notebook contains code for a Spam Classifier built using the RandomForestClassifier model. The model was trained on the SpamAssassin dataset and can classify Emails with an accuracy of 0.98. </li>
<li>Email and bs4 libraries clean the emails to extract only the content, removing any irregularities such as HTML tags, Subject, To/From, and labeling the emails.</li>
<li>The NLTK library is used to tokenize the content and convert it into a matrix (Bag-of-Words) which indicates how often a word occurs in the entire dataset. </li>
<li>The RandomForestClassifier is trained on this data to be able to classify emails into spam and non-spam categories </li>
</ul>

### Libraries used:
<ul>
  <li>bs4</li>
  <li>Email</li>
  <li>Matplotlib</li>
  <li>NLTK</li>
  <li>Numpy</li>
  <li>Pandas</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
</ul>

