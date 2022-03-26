<center><h1>Team Creators</h1></center>

TEAM: CREATORS

NAME: SARTHAK ARORA (LEADER) 
             HARSH JINDAL
             SARTHAK SHARMA
             DIVYANSH BANSAL

## Problem Statement:
Create a word game that has to include the following features/aspects:
1. It should be based on a boggle board where a user is open to find as many words as possible in a given time.
2. Words can be created by using letters horizontally, vertically or diagonally.
3. Sizes of boggle board should be 4x4
4. A new boggle board should recur after every ‘X’ seconds.
5. Each boggle board should be available to play for up to 5,000 concurrent users.
6. Minimum accepted word size should be 3.

## Checklist for above problem statement:

1	IMPLEMENTED <br>
2	IMPLEMENTED <br>
3	IMPLEMENTED <br>
4	IMPLEMENTED <br>
5	IMPLEMENTED <br>
6	IMPLEMENTED <br>

## Challenges to solve:
1. What words would qualify in the game and on what basis would these words be validated?
Sol:- 
Different libraries and predefined sets along with a dictionary are being used to define whether the words used are correct or not. 

2. Various scoring elements in the game, the more the merrier. Example: Different scores for different alphabets (rarer alphabets meriting higher points), short vs long words, etc.
Sol:-
In the game we used scoring in two methods 1) If the word count is 3 or either more than that 1 score for each correct word will be given. 2) If you are finding predefined words like WENZO, IEEE NSUT will be given one bonus point instead of one you will score 2 points. 

3. Will there be a check for the minimum number of words that can be formed in each boggle board? (A user should not be able to find all the words in 2-3 minutes)
Sol:-
There is a minimum check of condition making it a compulsion of asking and taking input from users above 3 as if otherwise error message / notification will prompt.

4. Matching users to all other users that have played the same boggle board and ranking them based on their scores?
Sol:-
Ranked list based on the direct number of scores. In case of tie 1st person will be ranked-1 who have tie based on submission timings. 

5. How many such boggle boards would be required? Can these boggle boards be created infinitely; can they be auto generated?
Sol:-
According to the count of boggle required currently we have 3 boggles which can be rescheduled infinity times.

## Good to have features (Bonus):
1. Per board challenges to keep the user engaged (theme-based words or finding words with specific alphabets)
Sol: IEEE, COVID

2. The possibility to make the boggle board vernacular (Hindi and English)
Yes 100%.

3. Multiple sizes of the boggle board (4x4 to 6x6).
Sol: Yes you can convert it into: 1 ) 4x4  2) 3x3

## SCREENSHOTS:
    
