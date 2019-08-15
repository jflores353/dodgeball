# dodgeball
--Add People to players- --When clicked the people are added to the Players column and removed from the People list while getting new values of a player added to them.

-- Can add People to Players - When clicked the people are added to the Players column and removed from the People list while getting new values of a player added to them.

--Can add Players to different Teams - When we click on the blue button they Player is added to the blue team and removed from the Player list while also getting the keys color and mascot extended to them when they are moved to a team.

--Uses Class - This is not a hack job. You should use class to add the new properties you need and extend when you need.

--Minimum 3 Unit Tests - Use Mocha and Chai to give us at least 3 unit test that prove a person becomes a player and player becomes a teammate.

1.) take the list of people and make a class that includes them and give them the function of becoming a player (this is done via the button "make a player") 2.) once a player they should:

be able to throw/dodge a ball
paid their dues
is healty
has how many years experience (these are what I can test for and use ALERTS to show if they are not passing via if/else if statements) 3.) the player class should have the function to join either the red or blue team via two differnet buttons in html using "onclick" 4.) once a player is joined to a red or blue team the should gain the team color and mascot and be displayed as such 5.) my 3 tests I am looking to do are: -----1.) if a person is "not healthy or not paid dues" they can't become a player. -----2.) is a player able to joing a team (red or blue) -----3.) once on a team does a team member now have that teams mascot and color

Instructions from Repo given to students--

20pts - Code Plan - Include this in a README.md file in your folder with comment in your code.
20pts - Can add People to Players - When clicked the people are added to the Players column and removed from the People list while getting new values of a player added to them.
20pts - Can add Players to different Teams - When we click on the blue button they Player is added to the blue team and removed from the Player list while also getting the keys color and mascot extended to them when they are moved to a team.
20pts - Uses Class - This is not a hack job. You should use class to add the new properties you need and extend when you need.
20pts - Minimum 3 Unit Tests - Use Mocha and Chai to give us at least 3 unit test that prove a person becomes a player and player becomes a teammate.
Instructions
Once you understand the challenge, whiteboard the logic.
Create a list of steps your app need to do. (Code Plan)
Translate to psuedo code.
Translate to javascript on paper
Make a repo, clone, open and copy/paste the starter code below into two new files: index.html and main.js
Start by working through the existing code to understand it and write comments explaining what each line does.
Put your Code Plan in the README.md file or your repo
Work through the follow challenges:
Use the class keyword to create a template of a dodgeBallPlayer that requires canThrowBall, canDodgeBall, hasPaid, isHealthy, yearsExperience
Push these new dodge ball Player objects into a new array and then display them in the DOM as available players to pick.
Add a button to each new player that will allow each one to be selected for either Blue Team or Read Team and now has mascot and teamColor
Use the this keyword to assign each player to a team with an onclick. Either Blue Team or Red Team.
Display the two teams in a new list in the DOM with appropriate titles.
Create 3 tests for your application.