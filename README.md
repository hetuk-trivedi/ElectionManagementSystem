# ElectionManagementSystem
A council would like to try new way of elections in a city and adopt it to other cities if it is successful. Building a E-Board for managing elections with capabilities below:

Citizens can nominate themselves for the elections as contenders.
Contender can post their manifesto on the board. Each manifesto may contain a maximum of 3 ideas.
Citizens should be able to see the list of contenders and their respective manifesto.
Citizen can rate the ideas on the scale of 0 (bad) to 10 (excellent).
Board should allow a citizen to delete his/her rating.
If the rating is more than 5, then citizen is added as a follower of the contender. 
Anytime a contender posts an idea, an email should be sent out (just do a console.log and not the real mail integration) to his/her followers and even to the followers of recipient (if any).
A contender is removed from the election if he/she has at least 1 idea which is rated less than 5 by more than 3 voters. 
A contender who has maximum sum of avg.ratings / idea is decided as the winner. 
Average Rating Per Idea = Sum of all ratings / No of voters.
Final rating = AvgRating of Idea 1 + Avg Rating of Idea 2 + Avg Rating of Idea 3. 
Build this system considering space and time efficiency along with OOP principles. [User interface is not mandatory. Running program in a terminal is sufficient]
