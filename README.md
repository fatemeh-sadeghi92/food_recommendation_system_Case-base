# food_recommendation_system_Case-base
Case-based reasoning is a paradigm of artificial intelligence and cognitive science that models the reasoning process based on cases in memory. In fact, the case-based reasoning system solves new problems by retrieving stored cases that describe  previously similar problems  and their solutions and adapt to new needs, solve them 
This argument consists of four steps:
1- Retrive
According to the desired goal, it retrieves the cases related to its solution from the memory. 
One sample includes the problem, the solution, and usually tips on how to extract the solution.
2-Reuse
It relates the solution of the previous examples to the problem in question. Of course, sometimes it requires that the required solution be adapted to the new situation and new case.
3-Revise
After mapping the previous solution to the new case, the new solution in the real world (or
Simulation (test and revise if necessary).
4-Retain
After the solution has been successfully adapted to the target problem, the experience gained
Saves as a new case in memory.
To implement the case-based reasoning system, first a knowledge base of diffrent cases created and saved in Database. Considering that the problem of offering meals to people is based on the different conditions they experience during the day, the sample of the initial cases created as is below
In this repo, features such as eating places, which are divided into three modes: home, workplace and restaurant
 a person's mental state, which is divided into six states of happy, active, sad, bored, and nervous, a special event that is held on that day and the person participates in it, which includes the World Cup, a book exhibition, and a piano performance, an activity that a person take on that day, which includes sports, football, or watching a sports match, the person's nutritional status on the day in question, which includes not eating breakfast, eating brunch, drinking too much coffee, and the person's academic status, which includes having end-of-semester exams, quizzes, and or having an Expert system class on the desired day, it is divided.
 After preparing the library and the examined cases, a similarity comparison method should be defined. the best choise  is Mahalanobis distance becaouse it is an effective measure of multivariate distance that measures the distance between a point and a distribution. This type of distance is a suitable criterion for detecting multivariate anomalies, classifying unbalanced data and classifying one class.
 The advantage of the Mahalanobis distance over the Euclidean distance is that this type of distance also takes into account the relationships between the data.
