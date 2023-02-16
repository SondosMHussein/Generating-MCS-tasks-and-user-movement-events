# Generating MCS tasks and user movement events. 

# Description
## Step one: Generating tasks
We need to create 2,000 legitimate tasks for 15,000 users with task properties 

• Days: Distribution consistent in [1, 2, 3].

• Hours: 50% (9:00 AM-11:00 AM), 25% (12:00 PM-5:00 PM), 25% (6:00 PM-8:00 AM) 

• Minutes: 50% in [20, 40, 60], 30% in [30, 50, 70], 20% in [10, 80, 100].

• Task value: Uniformly distributed in [1,10].


## Step two: Obtain user movement

We generated user movement events using a stochastic algorithm througth using Dirichlet 
distribution to select a stochastic path rather than the longest path.




   
# Output of uniform mobility model (Main ) :

Editing the setup.txt file by using number of users = 15,000.
Days= 3 

We entered CityName= morlupo
