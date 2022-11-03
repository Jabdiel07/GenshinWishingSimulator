# GenshinWishingSimulator
Small version of the Wishing System in Genshin Impact

#PRIMOGEMS WON'T BE TAKEN INTO CONSIDERATION, JUST RANDOM WISHING WITH NO LIMITS

#Only thing I couldn't implement was the guaranteed 5 star and 4 star for the 10 wish, but it's almost impossible to get to high pity when everything has a high probability for being pulled 

Some stuff I took into consideration for this:

#Create a List that contains the characters/weapons in the current banner *

#Create separate list with just 5 stars *

#Create a variable for the pity after every wish *

#while true statement to start wishing; when the player wants to stop, then it'll turn false *

#Ask the player if they want to either do 1 wish or 10 wish; should be an int *

#if statement for both 1 wish and 10 wish *

#if statement pity < 90, then do normal wishing; if pity == 90, then normal wishing and a guaranteed 5 star from the 5 star list we did *

#for loop to go through the list to pick what you get from a 1 wish or 10 wish; using in range * (did not use in range)

#After every wish session done, the pity count will be updated with the respected amount of wishes that were done *

#Have to do a pity reset after getting a five star, have to figure out how to do that; Guess this would be done by using the 5 star character list we have with an if statement? This would be at the end before doing another wish, this way the pity resets before we start wishing again *

#50/50 still not planned, might do that after I've succesfully gotten the code to work with normal wishing

#Need to have a variable to store what I got and display it on screen; this is what we use to reset the pity as well. We can have an if statement that checks if the variable contains a character from the 5 star list and if it does, then pity = 0 *

