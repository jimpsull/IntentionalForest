# IntentionalForest
I'd like to use randomization for bootstrap aggregating of records but use an intentional feature 
selection algorithm in place of the random subspace method.  The details of the algorithm for intentional 
selection have not been determined yet.  

The principal of randomizing is to get a diversity of responses and avoid overfitting.  However, if you 
divided a room of people (features) into teams with the intention of giving each team a vote, you wouldn't 
put all the experts on the same team.  You also wouldn't put all the people (features) with the same 
ideaology (colliearity) on the same team.

The IntentionalForest algorithm will attempt to keep collinear features on different teams and evenly
divide features with stronger correlation to the target.
