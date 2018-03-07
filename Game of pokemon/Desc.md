Question 3:- https://www.hackerrank.com/contests/cqm-5-2/challenges/game-of-pokemon

Each alphabet of the input should be matched with any particular pokemon.

First take one pokemon and then start matching the alphabets in the input one by one. 

If '.' comes then leave and if alphabet comes then check whether it matches with the alphabet present at the same location of the 
pokemon as in input. If it matches then go for another character in the input.
   If there is a mismatch for any alphabet then leave that pokemon and start doing the same for another pokemon until 
 you get a pokemon that contains all those alphabets at the exact same location as in input. Now this pokemon is the answer.
