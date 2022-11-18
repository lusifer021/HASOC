# HASOC

In this project of Hate Speech Offensive Content Identification in English and Indo-Aryan Languages, tweets were classified into classes.
There were four types of languages german, hindi, english and hinglish.
The dataset was in jason format, so at first the tweets were exctracted from the jason files.
Task 1: ICHCL HINGLISH and GERMAN Codemix Binary Classification
- (NOT) Non Hate-Offensive - This post does not contain any Hate speech, profane, offensive content.
- (HOF) Hate and Offensive - This post contains Hate, offensive, and profane content.

Task 2: Identification of Conversational Hate-Speech in Code-Mixed Languages (ICHCL) - Multiclass Classification.
- SHOF) Standalone Hate - This tweet, comment, or reply contains Hate, offensive, and profane content in itself.
- (CHOF) Contextual Hate - Comment or reply is supporting the hate, offense and profanity expressed in its parent. This includes affirming the hate with positive sentiment and having apparent hate.
- (NONE) Non-Hate - This tweet, comment, or reply does not contains Hate, offensive, and profane content in itself.

Task 3: Offensive Language Identification in Marathi
A task focused on hate speech and offensive language identification is offered for Marathi which follows OLID texonomy that contains collection of annoted tweets that encompasses following three levels.

Subtask-3A: Offensive Language Detection
- OFF - Posts containing any form of non-acceptable language (profanity) or a targeted offence, which can be veiled or direct.
- NOT - Posts that do not contain offence or profanity.

Subtask-3B: Categorisation of Offensive Language
- Targeted Insult (TIN) - Posts containing an insult/threat to an individual, group, or others.
- Untargeted (UNT) - Posts containing nontargeted profanity and swearing.


Subtask-3C: Offense Target Identification
- Individual (IND): - Posts targeting an individual.
- Group (GRP) - The target of these offensive posts is a group of people considered as a unity due to the same ethnicity, gender or sexual orientation, political affiliation, religious belief, or other common characteristics.
- Other (OTH) - The target of these offensive posts does not belong to any of the previous two categories.

The datasets for these task can be got [here](https://hasocfire.github.io/hasoc/2022/dataset.html)

Every task is solved in the notebooks:

- Task 1 is a binary classification and Logistic Regression performed best and gave a macro f1 score of 80%.

- Task 2 is a three class classification and Support Vector Classifier performed best and gave a macro f1 score of 56%.

- Task 3A is a binary class classifiction and in this task Logistic Regression gave a macro f1 score of 76%

- Task 3B is a three classification and Logistic Regression gave a macro f1 score of 62%

- Task 3C is a four class classification and SVM performed best and gave macro f1 score of 52%

