

Design an Elevator Controller for a building with 4 floors. Deduce the required inputs and outputs from the following description of the system.
Use Cases with Activity Diagrams
Use Case 1 : Request Elevator Use Case.
•	Primary Actor(s) : Elevator User, Elevator Logic Controller 
Description : The Elevator User uses the Elevator Request System (ERS) to request an elevator.
Preconditions : An Elevator User is at a floor and desires to use the elevator. 
Flow of Events : The Elevator User arrives at the ERS panel on their floor :
1.	User presses “Up” or “Down” button on ERS panel. 
2.	The ERS sends a signal to the ELC, detailing which floor the user is on.
3.	The request is added to a list of floors to visit.
4.	The ELC determines which direction to move to service the next request.
5.	The doors are closed, if open, and the elevator begins to move towards the requested floor.
6.	The ELC checks whether to stop as the elevator approaches a floor. 
7.	The elevator stops at requested floors that are along the route to the original destination floor.
8.	The ELC opens the elevator door when it comes to a stop.
9.	The elevator arrives to service the request of the user.
Postconditions : The elevator has arrived in response to a request. 
Alternative Flow of Events : None. 
Assumptions : None.
