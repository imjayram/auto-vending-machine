This is an automatic vending machine project.
This machine gives an ouput(item) when 15 rupees is given in input and anything excess is returned as change.
This machine operates in three states s0,s1,s2.s0 state indicates 0 rupees,s1 indicates 5 rupees,s2 indicates 10 rupees.
If the current state is s0 and we give 5 rupees in input then it will go to next state s1 ans give change 0 rupees.If we stay at s1 for long then it will revert back to s0 state and give
change 5 rupees.
