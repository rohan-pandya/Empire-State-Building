# Empire State Building
 A project with simulates 100 dice roll 500 times to know the probability of person reaching the top of the empire state building (60 steps)
 When the dice is rolled, there are 6 possible outcomes {1,2,3,4,5,6}
 If the outcome is 1 or 2. The person takes the step down.
 If it's 3,4 or 5 the person takes a step up.
 If the person throws a 6 they'll get another throw and the outcome from another throw will be the number of steps they'll climb.
 They'll start from step 0 so they can't go below that and scoring 1,2 will be neglected when the person will be at step 0.
 To spice it up.. we'll add clumsiness of a person where there's 1% chance that they'll fall from whichever step they reached and will have to start form square one (step 0)
 
 We'll iterate this 500 times to get a probability of a person reaching 60th step in 100 dice rolls. 
