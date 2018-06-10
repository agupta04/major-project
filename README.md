# major-project

Identity Linkage
-------------------------------
1. Identity-Linkage.ipynb: Converts emails from github "users" table to MD5 hashes and finds the common emails across SO and GH using intersection.
   
Feature Computation
-------------------------------

2. Feature Computation - posts typo+spell check.ipynb: computes the "Ability" features i.e. Clarity in Respose - finding typos and spelling mistakes scores for all SO posts. 

3. Feature Computation - SO Comments typo+spell check.ipynb: computes the "Ability" features i.e. Clarity in Respose - finding typos and spelling mistakes scores for all SO comments. 

4. Feature Computation - Working with timestamp data.ipynb: computes the "Motivation" features i.e. Frequency of Contributions - finding average time elapsed between two answers of a user on SO.

5. Feature Computation - #ques, #ans, Commitment Towards Community - #comments, #post edits.ipynb: computes the "Motivation" features i.e. Quantity of Contributions - number of questions ans answers; and Commitment Towards Community - number of comments and post edits of a user on SO.

6. Feature Computation - posts sentiment, GH follower-followee ratio.ipynb: computes the sentiment scores on SO posts along with GH F-ratio.

7. Feature Computation - Clarity in response, Answer Quality, Question Clarity, politeness.ipynb: computes "Motivation" features such as Clarity in response, Answer Quality, Question Clarity and politeness by averaging the sentiment scores of SO user\`s posts and comments text.

8. Feature Computation - GH Motivation - projects.ipynb: computes the "Motivation" features using GH "projects" and "project_members" table, finding the number of projects owned by a user and number of projects in which he has membership.

9. Feature Computation - Motivation_SO.ipynb: computes "Motivation" features for SO users.

Modelling
------------------------------
10. Feature Consolidation.ipynb: Merges all features for linked users into one csv named, "FINAL_FEATURES.csv"

11. PCA.ipynb: PCA results for modelling - note that PCA was not used for modelling.

12. Modelling-Kmeans.ipynb: using "FINAL_FEATURES.csv" it performs "Dimensionality Reduction", Finding optimum value of k, Kmeans for k=2 and k=4, plotting the results.


To Do
-----
1. Upload data files
2. Upload Result files
3. Upload plots generated 
4. Try to put a more clear version of the notebooks by mentioning input and output files
