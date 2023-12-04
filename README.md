# sms_classifier

This project takes any input of text then classfies it into SPAM / HAM. This project using spam sms dataset from kaggle. Our goal is to perform opterations like:- 
<ul>
  <li>Data Cleaning</li>
  <li>EDA</li>
  <li>Text Preprocessing</li>
  <li>Model Building</li>
  <li>Evaluation</li>
  <li>Improvement</li>
  <li>Website(Streamlit Web App)</li>
  <li>Deploy</li>
</ul>

We have used several ML algorithms to create and evaluate this project some of them are :- 
<br>SVC(kernel='sigmoid', gamma=1.0) <br>
KNeighborsClassifier()<br>
MultinomialNB()<br>
DecisionTreeClassifier(max_depth=5)<br>
LogisticRegression(solver='liblinear', penalty='l1')<br>
RandomForestClassifier(n_estimators=50, random_state=2)<br>
AdaBoostClassifier(n_estimators=50, random_state=2)<br>
BaggingClassifier(n_estimators=50, random_state=2)<br>
ExtraTreesClassifier(n_estimators=50, random_state=2)<br>
GradientBoostingClassifier(n_estimators=50, random_state=2)<br>
XGBClassifier(n_estimators=50, random_state=2)<br>

At the end the project we will be having fully trained ML model with generated NLP vectorizer file which will be used during Web App deployment of this project using Streamlit API
