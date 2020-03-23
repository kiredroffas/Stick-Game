This BASH shell script accepts the following input: 1. stick #                                                                                                                                                      
                                                    2. stick _                                                                                                                                                       
                                                       #                                                                                                                                                             

This program plays a stick game where you choose a number of sticks to play with and take turns taking 1,2,or 3 sticks.                                                                                   
The person who takes the last stick wins. It starts by reading in the number of sticks to play with either from the command line,                                                                         
or if nothing is given will promt the player for the number of sticks.If player fails to enter number of sticks the program exits.                                                                        
Once number of sticks has been decided, that number of sticks along with the number are printed. The computer goes first, and                                                                             
determines its move through the (n mod 4) command. This takes the number of sticks, divides it by 4, and gives the remainder.                                                                             
That remainder is then passed to a while loop that runs until the number of sticks equals 0. The computer then has two choices:                                                                           
if (n mod 4) == 0 then it will take one stick, if (n mod 4) != 0 it will take n mod 4 (the remainder) stick(s). After taking                                                                              
stick(s) and printing the remaining sticks to the screen, it promts the user how many sticks they would like to take. If the                                                                              
user enters a number besides 1,2, or 3, a warning will be given and the promt will happen again. If another invalid number is                                                                             
given the program exits. If a valid number is given it subtracts that number of sticks from the total number of sticks, and                                                                               
then prints out the new number of sticks. The game continues until the number of sticks left equals 0, at which point the                                                                                 
computer announces who won.  