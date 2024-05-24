# ONR-ISR
Office of Naval Research Intelligence, Surveillance, and Reconnaissance Simulator.
Intended to help simulate interaction, cooperation, and potential issues with human/computer collaboration for control of an aircraft on an intelligence mission.

This is not the original repository, and it is not the full project (many things have been removed or commented out in order to have this work as a standalone page). This is a demonstration of only a part of the webpage aspect of the project, and does not show things like Matlab vector control and Microsoft Flight Simulator integration. The main work that I did on this portion of the project was on overall game logic, boat control and placement, and user interaction with the plane's path (what happens when you click the screen). 

## Running the simulator

Open `/templates/index.html` in a web browser.

You can include the following URL parameters, which will prevent the user from changing them:

```
userId=(string)
gameplayColor=(white, yellow, red)
targetsIteration=(A, B, C, D, E)
motionIteration=(F, G, H, I, J, K)
searchPattern=(ladder, hold, square)
```

For example:

`.../index.html?userId=12321&gameplayColor=yellow&targetsIteration=D&motionIteration=J&searchPattern=hold`

 
You can add `live=true` which will disable the parameters box

`.../index.html?userId=12321&gameplayColor=yellow&targetsIteration=D&motionIteration=J&searchPattern=hold&live=true`
