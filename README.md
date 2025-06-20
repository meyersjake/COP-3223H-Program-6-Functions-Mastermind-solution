# COP-3223H-Program-6-Functions-Mastermind-solution

Download Here: [COP 3223H Program #6: Functions – Mastermind solution](https://jarviscodinghub.com/assignment/program-6-functions-mastermind-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem: Mastermind
In the popular game Mastermind, one player creates a secret code of four pegs, each of which
can be chosen from one of six colors. (The number of pegs and colors may be different than this
in different versions, but your implementation will use these values, but be extendible, very
easily, to other values. Also, a color can be reused, thus there really are six choices for each of
the four pegs.) The other player then has to guess the color of each peg, with the order mattering.
The player who made the secret code then has to give feed back to the player guessing. This
feedback is in the form of white and black pegs. A black peg means that the guesser has chosen
the correct color in the correct slot. These are first “calculated” and awarded. Once these are
counted, these pegs are ignored. Then the white pegs are awarded. These are for pegs that are the
correct color but are in the incorrect slot. There is no “double dipping” of pegs in the response,
so the sum total of white and black pegs the guesser can receive is four, and no one peg in the
guesser’s answer may earn them more than one black or one white peg.
Here is a picture of a Mastermind board:
A framework has been written for you to fill in. The main has been completed and nine functions
have been specified for you to fill in. Each function comes with a pre-condition and postcondition.
A function pre-condition is the set of specifications that must be satisfied in order to call the
function. If these conditions aren’t met, then the behavior of the function is unpredictable.
However, if the conditions are met, then the function must uphold the listed post-conditions. (For
example, if the sqrt function is given a positive real number, then it is required to return the
square root of that positive real number.) The post-condition explains what you must do in the
function while the pre-condition explains what you can assume without checking.
The most difficult function in the program is the numWrongPlaceMatches function. In this
function, comments have been left to discuss the various steps involved in solving the given task.
For the rest of the functions you must simply use the pre-conditions and post-conditions given to
write the function.
Input Specification
The user will always enter valid combinations, meaning they will always enter exactly four
integers in between 0 and 5, inclusive, separated by spaces.
Output Specification
A greeting will be printed in the beginning, exactly like the one printed in each of the samples.
From that point the program will respond to each guess with a statement of the following form:
You have X perfect matches and Y imperfect matches.
where X is the number of perfect matches (right color, right spot) and Y is the number of
imperfect matches (right color, wrong spot with no double counting).
At the end of the game, if the user wins, the number of guesses they needed as well as the
amount of time they took will be printed in the following format:
You have won the game in X turns and M:SS!!!
where X is the number of turns taken and M:SS is the amount of time in minutes and seconds.
Here is how you can print out a number (num, in this example) so that a zero precedes it if it’s
one digit long instead of two:
printf(“%02d”, num);
If the user loses, then a message stating so along with a printout of the correct game board will
be given using the following format:
Sorry, you have exceeded the maximum number of turns. You lose.
Here is the winning board: A B C D
where A, B, C and D are the numbers (in order) of the secret pegs.
Sample Run #1 (User Input in Bold)
Welcome to MasterMind!!!
At each turn, you will enter your guess for the playing board.
A valid guess ahs 4 values in between 0 and 5.
Each guess will have each number within the guess separated by a
space.
When you are ready, enter your first guess.
From that point on, you will be told how many perfect and
imperfect matches you have.
After this message, you should guess again. You have 10 chances,
good luck!
0 1 2 3
You have 1 perfect matches and 0 imperfect matches.
4 4 4 4
You have 0 perfect matches and 0 imperfect matches.
5 5 5 3
You have 4 perfect matches and 0 imperfect matches.
You have won the game in 3 turns and 0:16!!!
Sample Run #2 (User Input in Bold)
Welcome to MasterMind!!!
At each turn, you will enter your guess for the playing board.
A valid guess ahs 4 values in between 0 and 5.
Each guess will have each number within the guess separated by a
space.
When you are ready, enter your first guess.
From that point on, you will be told how many perfect and
imperfect matches you have.
After this message, you should guess again. You have 10 chances,
good luck!
0 1 2 3
You have 1 perfect matches and 0 imperfect matches.
4 5 2 1
You have 0 perfect matches and 3 imperfect matches.
5 2 1 3
You have 1 perfect matches and 1 imperfect matches.
5 4 2 3
You have 1 perfect matches and 1 imperfect matches.
2 3 4 5
You have 2 perfect matches and 0 imperfect matches.
2 3 1 1
You have 0 perfect matches and 1 imperfect matches.
2 4 5 0
You have 0 perfect matches and 2 imperfect matches.
1 2 5 3
You have 0 perfect matches and 2 imperfect matches.
1 4 3 1
You have 0 perfect matches and 2 imperfect matches.
1 4 2 3
You have 0 perfect matches and 2 imperfect matches.
Sorry, you have exceeded the maximum number of turns. You lose.
Here is the winning board: 5 1 4 5
Deliverables
You must submit a single file, mastermind.c, over WebCourses:
Restrictions
Although you may use other compilers and coding environments, your programs must run in
Code::Blocks. Your program should include a header comment with the following information:
your name, course number, section number, assignment title, and date.
Grading Details
Your program will be graded upon the following criteria:
1) Your correctness
2) Adhering to the given function prototypes
3) Your programming style and use of white space. (Even if you have a plan and your program
works perfectly, if your programming style is poor or your use of white space is poor you could
get 10% or 15% deducted from your grade.)
4) Compatibility to Code::Blocks. (If your program does not compile in either of these
environments, you will get a sizable deduction from your grade, likely to be over 50%)

