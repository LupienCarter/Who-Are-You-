# Who Are You?
>Have you ever wondered which house you would be sorted into at Hogwarts or which demigod you would be in Percy Jackson this short personality quiz could answer those questions for you.

## Overview
>This program's focus is to have the user take a personality test through either a Hogwarts House Quiz or a Percy Jackson Demigod Quiz. 
>The user answers five questions for the quiz they choose.
>Each answer is used in conditional statements to add points to different houses or demigod parents. 
>At the end, the program compares the points and gives the user a final result based on their answers.

## Sample Questions and Responses
>Hogwarts House Quiz
>Question 1: Which quality is most important to you?

>Courage
>Intelligence
>Loyalty
>Ambition

>Question 2: You see someone being treated unfairly. What do you do?

>Stand up for them
>Think of the smartest way to solve the problem
>Stay with them and offer support
>Find a way to make sure you come out ahead

>Question 3: Which activity sounds the most interesting?

>Going on an exciting adventure
>Learning something new
>Helping your friends
>Working toward a big goal

>Question 4: Your friend needs help. What do you do?

>Jump into the situation immediately
>Come up with a plan
>Stay by their side
>Find the most effective solution

>Question 5: How would your friends describe you?

>Brave
>Smart
>Dependable
>Determined

>Percy Jackson Demigod Quiz

>Question 1: Which ability would you want most?

>Control over water
>Incredible intelligence
>Great strength
>Musical and healing abilities
>Incredible speed

>Question 2: Which activity would you rather do?

>Swimming or exploring the ocean
>Solving a difficult puzzle
>Training for battle
>Playing music
>Going on an adventure

>Question 3: What would be your greatest strength?

>Adaptability
>Wisdom
>Fearlessness
>Creativity
>Quick thinking

>Question 4: What would you do if your friend was in danger?

>Protect them no matter what
>Create a plan to rescue them
>Fight whoever is threatening them
>Try to heal or encourage them
>Find a quick way to get them out

>Question 5: Which environment would you choose?

>The beach
>A library
>A training arena
>A concert
>A busy city


## Variables

<quiz_choice (str): stores whether the user chooses the Hogwarts House Quiz or the Percy Jackson 

Demigod Quiz. A string is used because the user's input is received as text.|

answer (str): stores the user's answer to each question. 
The answer is compared with different options in the conditional statements.

gryffindor, ravenclaw, hufflepuff, slytherin (int): store the points for each Hogwarts House. 
Separate variables are needed because each house needs its own score.

poseidon, athena, ares, apollo, hermes} (int): store the points for each Percy Jackson demigod parent. 
Separate variables are needed so the program can compare the scores.

<house (str): stores the final Hogwarts House result.

parent (str): stores the final Percy Jackson demigod parent result.

description (str): stores a description of the user's final personality result.

>## Conditional Logic Outline
>Conditional statement 1 — Choosing the quiz
>if the user enters 1: the Hogwarts House Quiz starts.
>elif the user enters 2: the Percy Jackson Demigod Quiz starts.
>else if the user enters anything other than 1 or 2: display a message saying the choice is invalid.

>Hogwarts House Conditional Statements
>Conditional statement 2 — Hogwarts Question 1
>if the response is 1: add 1 point to Gryffindor.
>elif the response is 2: add 1 point to Ravenclaw.
>elif the response is 3: add 1 point to Hufflepuff.
>elif the response is 4: add 1 point to Slytherin.
>else: display that the answer is not valid.

>Conditional statement 3 — Hogwarts Question 2
>if the response is 1: add 1 point to Gryffindor.
>elif the response is 2: add 1 point to Ravenclaw.
>elif the response is 3: add 1 point to Hufflepuff.
>elif the response is 4: add 1 point to Slytherin.
>else: display that the answer is not valid.

>Conditional statement 4 — Hogwarts Question 3
>if the response is 1: add 1 point to Gryffindor.
>elif the response is 2: add 1 point to Ravenclaw.
>elif the response is 3: add 1 point to Hufflepuff.
>elif the response is 4: add 1 point to Slytherin.
>else: display that the answer is not valid.

>Conditional statement 5 — Hogwarts Question 4
>if the response is 1: add 1 point to Gryffindor.
>elif the response is 2: add 1 point to Ravenclaw.
>elif the response is 3: add 1 point to Hufflepuff.
>elif the response is 4: add 1 point to Slytherin.
>else: display that the answer is not valid.

>Conditional statement 6 — Hogwarts Question 5
>if the response is 1: add 1 point to Gryffindor.
>elif the response is 2: add 1 point to Ravenclaw.
>elif the response is 3: add 1 point to Hufflepuff.
>elif the response is 4: add 1 point to Slytherin.
>else: display that the answer is not valid.

>Conditional statement 7 — Hogwarts final result
>if Gryffindor has at least as many points as the other three houses: the result is Gryffindor.
>elif Ravenclaw has at least as many points as the other three houses: the result is Ravenclaw.
>elif Hufflepuff has at least as many points as the other three houses: the result is Hufflepuff.
>else: the result is Slytherin.
>The program then displays the house and its description.

>Percy Jackson Conditional Statements

>Conditional statement 8 — Percy Jackson Question 1
>if the response is 1: add 1 point to Poseidon.
>elif the response is 2: add 1 point to Athena.
>elif the response is 3: add 1 point to Ares.
>elif the response is 4: add 1 point to Apollo.
>elif the response is 5: add 1 point to Hermes.
>else: display that the answer is not valid.

>Conditional statement 9 — Percy Jackson Question 2
>if the response is 1: add 1 point to Poseidon.
>elif the response is 2: add 1 point to Athena.
>elif the response is 3: add 1 point to Ares.
>elif the response is 4: add 1 point to Apollo.
>elif the response is 5: add 1 point to Hermes.
>else: display that the answer is not valid.

>Conditional statement 10 — Percy Jackson Question 3
>if the response is 1: add 1 point to Poseidon.
>elif the response is 2: add 1 point to Athena.
>elif the response is 3: add 1 point to Ares.
>elif the response is 4: add 1 point to Apollo.
>elif the response is 5: add 1 point to Hermes.
>else: display that the answer is not valid.

>Conditional statement 11 — Percy Jackson Question 4
>if the response is 1: add 1 point to Poseidon.
>elif the response is 2: add 1 point to Athena.
>elif the response is 3: add 1 point to Ares.
>elif the response is 4: add 1 point to Apollo.
>elif the response is 5: add 1 point to Hermes.
>else: display that the answer is not valid.

>Conditional statement 12 — Percy Jackson Question 5
>if the response is 1: add 1 point to Poseidon.
>elif the response is 2: add 1 point to Athena.
>elif the response is 3: add 1 point to Ares.
>elif the response is 4: add 1 point to Apollo.
>elif the response is 5: add 1 point to Hermes.
>else: display that the answer is not valid.

>Conditional statement 13 — Percy Jackson final result
>if Poseidon has at least as many points as the other four choices: the result is Poseidon.
>elif Athena has at least as many points as the other four choices: the result is Athena.
>elif Ares has at least as many points as the other four choices: the result is Ares.
>elif Apollo has at least as many points as the other four choices: the result is Apollo.
>else: the result is Hermes.
>The program then displays the demigod parent and its description.

## Demo Video
[DELETE AND REPLACE ME: link to your 5-minute explanation video]
