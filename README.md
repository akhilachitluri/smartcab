# smartcab
n this project, you will work towards constructing an optimized Q-Learning driving agent that will navigate a Smartcab through its 
environment towards a goal. Since the Smartcab is expected to drive passengers from one location to another, the driving agent will be 
evaluated on two very important metrics: Safety and Reliability. A driving agent that gets the Smartcab to its destination while running
red lights or narrowly avoiding accidents would be considered unsafe. Similarly, a driving agent that frequently fails to reach the 
destination in time would be considered unreliable. Maximizing the driving agent's safety and reliability would ensure that Smartcabs 
have a permanent place in the transportation industry.
Safety and Reliability are measured using a letter-grade system as follows:
Grade
Safety
Reliability
A+
Agent commits no traffic violations,
and always chooses the correct action.
Agent reaches the destination in time
for 100% of trips.
A
Agent commits few minor traffic violations,
such as failing to move on a green light.
Agent reaches the destination on time
for at least 90% of trips.
B
Agent commits frequent minor traffic violations,
such as failing to move on a green light.
Agent reaches the destination on time
for at least 80% of trips.
C
Agent commits at least one major traffic violation,
such as driving through a red light.
Agent reaches the destination on time
for at least 70% of trips.
D
Agent causes at least one minor accident,
such as turning left on green with oncoming traffic.
Agent reaches the destination on time
for at least 60% of trips.
F
Agent causes at least one major accident,
such as driving through a red light with cross-traffic.
Agent fails to reach the destination on time
for at least 60% of trips.
To assist evaluating these important metrics, you will need to load visualization code that will be used later on in the project. 
Run the code cell below to import this code which is required for your analysis.
