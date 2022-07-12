# Covid infection simulation
**Purpose**: A simple simulation of Covid infection that shows how many people get infected per day until all are infected.<br><br>

**Example**:<br>10 person in a room, one gets sick, given the parameter of how likely one is to pass it along to another person, how many days until they are all infected.<br><br> 

**Input**:<br>
sizeOfSample = 10 #total number of people in sample<br>
infectionRate = 0.3 #probability of infecting one person a day, value range is [0,1)<br>
timesOfSimulation = 10 #how many times of the pandemic simulation<br>

**Output**: <br>Run the simulation over and over again to see average results and create a histogram of # days until pandemic ends.<br><br>
![Infections per day](Covid_infection_simulation.jpg)
![Average infection days](Average_infection_days.jpg)

**Precondition**:<br>The simulation is based on a constant infection rate no matter how many peole get infected.
But in reality, the more infected people, the more likely other people get infected.

**Solution**: &nbsp; python + jupyterlab + numpy + matplotlib
