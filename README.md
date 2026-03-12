# IP_Assignment
Delhi Metro Simulator - README


--> datetime module is used
--> The consecutive average travel time between stations is mostly assumed to be 2 or 3 mins for simplicity.
--> An interchange delay of 4 minutes is assumed.

--> Youtube Tutorials used for debugging and suggestions.
--> Sources : Wikipedia and official DMRC website


--> For bonus , a fare calculator is added in the Ride Journey Planner which calculates fare at Rupees 11 per station , for all cases
--> Breadth First Search is used to find the shortest possible route based on fewest stations , since travel time between stations is almost always 2 or 3 minutes 
    The route with fewer stations is  ALWAYS going to be faster when each step has almost the same weight.
--> Time should be input in 24 hour format in order for the program to function properly

-->  There could be cases where BFS would lead to more time , however since our program only deals with blue and magenta lines , so there is no exceptional case.

--> In journey planner , it shows each station name in between journey in the output.

--> To run the simulation , run the program and simply input 1 ,2 or 3 as per the functionality you wish to utilise.
--> The simulation keeps running in an infinite while loop unless you exit (press 3)
--> Graphs and Queues are used along with BFS  for route planning(shortest hop path)
--> Almost all exceptions are handled carefully , so the program should not be throwing an error in most cases.

# # Program is run from the terminal
