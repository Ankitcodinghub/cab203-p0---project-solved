# cab203-p0---project-solved
**TO GET THIS SOLUTION VISIT:** [CAB203 P0 – Project Solved](https://www.ankitcodinghub.com/product/cab203-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124332&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CAB203 P0 - Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1 Introduction

In this project will demonstrate your knowledge and skill with the material in the unit by developing a solution to a real world problem by translating it to mathematical language, relating the problem to well known problems on mathematical structures, and implementing software to solve the problem.

Your submission will consist of two parts: a report detailing the mathematical descriptions of the problem and solutions, and a Python file containing your implementation of the solution.

This assignment is worth 40% of your final grade.

2 Scenario

All tasks are intended to make significant use of graph theoretic tools and problems.

1. The tournament structure needs to be set; that is to say, who plays who. For this tournament a structure is used where all games are set at the beginning. Another committee member will propose the tournament structure and your job is to determine whether it has the required properties. The committee has determined that the following properties are sufficient:

• For every pair of distinct players, either they play against each other, or there are at least two other players that they both play against.

• All players have the same number of games.

So for example, if Alice and Bob don’t play against each other then it’s still OK as long as they both play against two players in common, say, Charlie and Denise.

Your job is to find a method that, given a tournament structure, determines whether the above properties hold.

Implement your method in a Python function like so:

def gamesOK(games): where games is a set of proposed games to play, given as pairs of players, like so: games = { (“Alice”, “Bob”), (“Charlie”, “Bob”) }

Your function should return True if the required property holds for the games given, otherwise False.

2. All Bonkers games must have a referee, but the referee for each game cannot have any conflicts of interest for the game. In particular, the referee cannot be a player in the game, and the referee must also declare any other conflicts of interest (eg. cannot be a player’s relative, friend, boss, etc..). In order to minimise the burden on any individual referee, the policy is to assign each referee at most one game.

Your task is to determine a method for assigning referees to games, given the games, referees, and conflicts of interest for each referee. You must assign at most one game to each referee, and exactly one referee to each game, or determine that it is impossible to do so.

Implement your solution as a Python function of the form def referees(games, refereecsvfilename):

games is structured the same as in the previous question.Assignment Project Exam Helprefereecsvfilename is the name for a CSV

file which you should read to obtain the list of referees and their declared conflicts of interest. Below is a sample CSV file showing the structure.

Alice,Bob,Dave,Eve

Bob,Dave,Eve,Fiona,Jamal Fiona

# dictionary of all (player1, player2) : referee

{ (‘Ashley’, ‘Bob’): ‘Rene’ }

or None if it is not possible.

3. The games now need to be scheduled, which will happen in two steps. Your first task is to group together games that can be played simultaneously into game groups. The requirements for the game groups are:

• People are not double-booked: each person is involved in at most one game in any game group., either as a player or referee

• Games are played once: each game is in exactly one game group

Each game group will be played in a single time slot, so the committee wants the smallest number of game groups possible.

Implement your solution as a Python function of the form def gameGroups(assignedReferees):

# list of timeslots

# each timeslot is a set of games

# each game is a pair (player1, player2)

[

{ (“Ashley”, “Bob”), (“Charlie”, “Dave”) },

{ (“Bob”, “Charlie”), (“Rene”, “Elaine”) }

]

4. The previous question only dealt with which games can be played at the same time, but not on the order of the game groups. The preference is that if a player is also a referee then they play all of their games before refereeing. Your task is to determine if it is possible to order the game groups so that this is true.

Implement your solution as a Python function of the form def gameSchedule(assignedReferees, gameGroups):

where assignedReferees is as in the previous question, and gameGroups is of the form of the return value in the previous question. Your function should return the game groups in the required order, in the same format as the return value in the previous question, or None if there is no such order.

5. Once all games are played, it is necessary to find the tournament winners. For this, Bonkers uses a points based system. The system is a little technical, so we first provide some intuition for it.

Since not all players play against each other in Bonkers, a points based system based on the numberAssignment Project Exam Help

plays Bob, but another player (say, Fred) who doesn’t play Bob wouldn’t have access to those points, even if he is as skilled as Bob. If Fred only plays against weak players then he is at a disadvantage. For this reason we limit the number of points that Alice can claim for Bob’s wins. Finally, suppose that Alice defeats Bob who defeats Charlie, and Alice also defeats Dave who defeats Charlie. Charlie is apparently not very skilled, so it isn’t fair for Alice to gain points for both Bob defeating Charlie and Dave defeating Charlie. So Alice gets the same amount of points from Charlie as if only Bob defeated Charlie. Put differently, Alice gets points once for second-hand defeating Charlie, not for each way that the second-hand defeats him. But, because there is the limit on points that Alice gets through Bob, she can get some of the points for Charlie through Bob and the rest through Dave.

Traditionally, each player’s points are calculated through a scoring game, which works as follows.

(1) The player writes out the names of all the players that they defeated (called primary wins) out on a big piece of paper. Above them the player writes all the names of all the players that the primary wins defeated (called secondary wins). They also draw a line from each primary win to each secondary win that the primary win defeated.

(2) A referee places p tokens on the paper on name of each primary win.

(3) The referee places s tokens on the paper on name of each secondary win.

(4) The player now moves tokens one at a time along lines from secondary wins to primary wins.

They can choose which lines to follow with each token.

(6) The player collects tokens on the primary wins counts them to determine their score.

Here is an example to illustrate the above rules based on a partial set of wins. We set p = 4,s = 3,c = 5:

• Alice defeats Bob, which is a primary win for Alice.

• Bob defeats Charlie, which is a secondary win for Alice against Charlie via Bob (Bob is the intermediate player.)

• Similarly, Alice defeats Dave (primary win), and Dave defeats Charlie (a secondary win for Alice.)

• Bob defeats Dave. This is not a secondary win for Alice because Dave is already a primary win.

Alice plays the scoring game as follows:

(a) Alice writes “Bob” and “Dave” on the paper for primary wins, and “Charlie” for secondary wins.

(b) Alice draws lines from “Charlie” to “Bob” and to “Dave”.

(c) The referee puts 4 tokens on “Bob”, 4 tokens on “Dave” and 3 tokens on “Charlie”.

(d) Alice moves 1 token from “Charlie” to “Bob”. “Bob” now has 5 tokens, so there is no space for more.

(e) Alice moves 1 token from “Charlie” to “Dave”. “Dave” now has 5 tokens, so there is no space forAssignment Project Exam Help

more.

(f) Alice decides not to reset.

where games is a data structures similar to:

# each pair is a game (winner, loser) games = { (“Ashley”, “Bob”), (“Bob”, “Charlie”) }

Your function should return a dictionary mapping players to points like so:

{ “Ashley”: 5, “Bob”: 4, “Charlie”: 4 }

3 Report

1. Use mathematical language, concepts and notation from the unit to describe the problem. You should make use of mathematical tools and problems discussed in the unit, for example quantified predicates or finding a shortest path in a graph. Describe the information given in mathematical terms and using mathematical notation (e.g. the games are given a set of pairs of players like {(a,b),(c,d)}).

2. Describe, using mathematical terms and notation, how to find a solution for a given instance of the problem. If applicable, describe how the information given relates to other mathematical objects that are needed. For example, how are the vertices and edges of a graph related to the given games. Describe how the solution to the mathematical problem relates to the solution to the original problem.

Overall, report should be understandable by another student in CAB203 who knows the material but hasn’t thought about the tasks. It is not necessary to define terms already used in the unit, but you should point out the significance of particular details about the problem and the choices that you make in modelling and solving it.

Your report will be a single file, in PDF format.Assignment Project Exam HelpThere is no minimum or maximum page length, but

a concise, easy to understand report is better than a long wordy report. Five pages is about right, not including diagrams if you have any.

The problems are all solvable using the Python concepts and syntax used in the unit. You can use additional syntax if you like as long as it is compatible with Python 3.10. One exception is that using loops incurs a penalty (see the marking criteria below.) The purpose of penalising loops is to encourage you to think in terms of mathematical style declarative structures rather than procedures. All tasks are solvable in the intended way without using loops.

You are allowed to use or modify any functions defined throughout the lectures, tutorials, and assignment solutions. Many of these functions and more are collected in Python files graphs.py and digraphs.py. We prefer that you import these files rather than copying from them; the questions are designed so that you can use the functions directly without modifying them. You can assume that these files are available; there is no need to include them in your submission. Additionally, you are allowed to use the csv Python module. Before using other modules, please contact the unit coordinator.

A submission template file is available from the Canvas Assessments module. If your solution includes modified code from the unit, say so in a comment explaining where you obtained it and what modifications you made. One line is enough detail.

The test file is structured using unittest, which is part of the Python standard library. It can be run directly to test your solutions:

python test_project.py

The tasks are all chosen so that they can be solved with a relatively short function (Matt’s solution is 57 lines, excluding comments and blank lines). There is no limit on the length of your program. However, the marking system will impose a time limit of about 5 seconds to avoid problems with infinite loops. This should be plenty of time to solve the tasks given.

Your code submission will be a single Python file.

4 Marking criteria

Your mark is made of two parts. The report is graded out of 30 and the Python code is graded out of 10, for a total of 40. Each mark counts 1% towards your final grade.

4.1 ReportAssignment Project Exam Help

The marking rubric is available on Canvas under Assignments &gt; Graph Project Report.

The marking system will use Python 3.10, so if you are using a later version be sure not to use any syntax newer than 3.10.

5 Submission

Submission process: You will need to make two submissions through two separate links in Canvas:

• Your report, in PDF format (extension .pdf).

• Your Python code, as a Python file (extension .py).

You can find the submission pages on Canvas on the Assignments page.

Citing your sources: You are welcome to source information and code from the internet or other sources. However, to avoid committing academic misconduct, you must cite any sources that you use. See https://www.citewrite.qut.edu.au/cite/ for guidelines on citing sources and how to properly format and acknowledge quoted material.

For code, please include your citation as a comment within the code. For example

# modified from CAB203 graphs.py

Policy on collaboration:Assignment Project Exam HelpWe encourage you to learn from your peers. However, for assessment you need
