# Project02

# Project Brief

# Project01

### Project Back Log

| User Story  | Description                  | Points | Due Date | Mo | Tu | We | Th | Fr |
|-------------|------------------------------|--------|----------|----|----|----|----|----|
| 1           | See number representation    | 2      | July     |    |    |    |    |    |
| 2           | get allocated virtual amount | 3      | July     |    |    |    |    |    |
| 3           | get given card  (value)      | 5      | July     |    |    |    |    |    |
| 4           | input higher or lower        | 4      | July     |    |    |    |    |    |
| 5           | get feedback (Feedback)      | 2      | July     |    |    |    |    |    |
| 6           | see allocated number change  | 3      | July     |    |    |    |    |    |
| Total Points| 19                           |





<img src="Project02/FlowChartP2.jpg" alt="Project2"
     title="Project2" />

### High Level Description 
A Higher or lower card game based around playing cards being the aesthetic, allowing a user to be given a card or value then guessing whether the next value will be higher or lower in conjunction or comparision to the initial value. If the user is correct in their assumption they are to be visual awarded somehow or notified whether they were right or wrong.

### Algorithm - (Flowchart)

### Process of implementation Algorithm

The program was initially broken down into segments, the first proccess consistng of getting a random number, using said random number as a representation of the first or initial card intended to be given to the user. The random number function or generator once implemented was intended to be used for multiple uses thus two variables were created to store both the initial and final number.
Though before the second number was printed a user input question linked to cin (console input) was applied, furthermore multiple conditional statements checking as to whether the input is corresponding to the pre-set inputs (higher or lower), else re-loop, which extends onto the next implementation or proccess a loop using while, for and do loops to continue to loop the game until predetermined or acceptable input is retrieved.The second variable then came into play setting the basics into fruition as once input is given another random number seperate to the previous one is displayed.If one of the conditions is met either the program re-loops for more input or states that the user has either won or lost. Thereafter the game loops no matter the outcome the next line of printed words were set to be printed 15 lines down to stop the console from getting cluttered and create the illusion of the game updating (refreshing). Once the higher or lower game structure was formed an end setting or end condition (event) was incorparted in the form of virtual money and two bars in which to aspire to get too or not, one leading to the user winning the game, the other seeing the user lose. The win condition in this instance consists of getting a numerical value of 1000 in the money, whilst the lose condition was geting under 0 (Value).



### Description of IDE used and features it provided

The IDE ( Integrated Development Environment) used was repl.it, the features it provided consisted of 
### Debugging process and debugging facilities in your chosen IDE

The IDE or notepad does not have any debugging facilities,but the debugging proccess has to be done manually either scrolling through code to locate and fix the problem or using preset code that is indented into the program and debugs the code, finding the problem for it to be solved (fixed).
