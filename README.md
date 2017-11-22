# December CIJUG Connect Four Code Off
[Meetup RSVP](https://www.meetup.com/central-iowa-java-users-group/events/245203632/)
## Notes
* Any JVM language can be used
* Application Code must be submitted by 11:59PM on December 7, 2017
 * Drop a note to the CIJUG organizers on Meetup and provide a link to your solution
 * Github or bitbucket repo is preferred
 * Make sure to include a readme with any instructions on how to run your solution
* Three submissions will get a chance to discuss their solution at the Dec 14 meeting
* One winner will receive a $50 Amazon gift card

## Application Requirements
1. Connect Four
Given a playfield
And two players
When the players load the playfield
Then the players see a playfield that is a grid with 6 rows and 7 columns
And the players see a prompt to play a new game

1. Given a prompt to play a new game
And two players
When the players select to play a new game
Then the players are prompted to enter player 1’s name

1. Given a prompt to enter player 1’s name
When a player enters a name
And the player presses enter
Then the players are prompted to enter player 2’s name

1. Given a prompt to enter player 2’s name
When a player enters a name
And the player presses enter
Then the players see a playfield that is a grid with 6 rows and 7 columns
And player 1 is assigned to the red color
And player 2 is assigned to the black color
And player 1 is in control of the playfield

1. Given player 1 is in control of the playfield
When player 1 selects a cell of the grid
Then that cell is filled with the red color
And player 2 is in control of the playfield

1. Given player 2 is in control of the playfield
When player 2 selects a cell of the grid
Then that cell is filled with the black color
And player 1 is in control of the playfield

1. Given player 1 is in control of the playfield
When there are 4 red colored cells horizontally adjacent to each other
Then player 2 is not in control of the playfield
And the players see a prompt that the game is over
And the players see in the prompt that player 1 has won
And the players see in the prompt an option to play another game

1. Given player 1 is in control of the playfield
When there are 4 red colored cells vertically adjacent to each other
Then player 2 is not in control of the playfield
And the players see a prompt that the game is over
And the players see in the prompt that player 1 has won
And the players see in the prompt an option to play another game

1. Given player 1 is in control of the playfield
When there are 4 red colored cells diagonally adjacent to each other
Then player 2 is not in control of the playfield
And the players see a prompt that the game is over
And the players see in the prompt that player 1 has won
And the players see in the prompt an option to play another game

1. Given player 2 is in control of the playfield
When there are 4 black colored cells horizontally adjacent to each other
Then player 1 is not in control of the playfield
And the players see a prompt that the game is over
And the players see in the prompt that player 2 has won
And the players see in the prompt an option to play another game

1. Given player 2 is in control of the playfield
When there are 4 black colored cells vertically adjacent to each other
Then player 1 is not in control of the playfield
And the players see a prompt that the game is over
And the players see in the prompt that player 2 has won
And the players see in the prompt an option to play another game

1. Given player 2 is in control of the playfield
When there are 4 black colored cells diagonally adjacent to each other
Then player 1 is not in control of the playfield
And the players see a prompt that the game is over
And the players see in the prompt that player 2 has won
And the players see in the prompt an option to play another game

1. Given the players see a prompt with an option to play another game
When the players select yes
Then the players see a playfield that is a grid with 6 rows and 7 columns
And player 1 is assigned to the red color
And player 2 is assigned to the black color
And player 1 is in control of the playfield

1. Given the players see a prompt with an option to play another game
When the players select no
Then the program exits
