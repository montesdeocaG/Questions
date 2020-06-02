
Designing Data Intensive Applications 


1. What are the three components that systems must contain?
A software system must be reliable, it must perform at our desired level even during stress tests. It must be scalable for it to deal with the grow as they system requierments increase such as data or traffic volume increases. It also should be maintainable well documented and work towards productivity since many different people will work on the same project. 

2. How does twitter scale its systems?
A new tweet will insert the tweet into a collection of global tweets, it will look up the id's of people you follow and merge them. They also mantain a cache for each user, reducing computing costs. Celebrity tweets are fetched separately. 


3. What does netflix's chaos monkey consist of? 
Chaos monkey will randomly terminate VM instances and containers that are running inside of your production environment, this exposes engineers to failures more frequently, incentivicing them to build more resilent systems.

4. What is the key difference between average and p50?
The fact that if you consider your response time statistics as percentiles instead of just average values, you will be able to assess that 50% of users might take longer than that time and 50% of users might take a lower value.

5. What are good maintenance practices for software?
Your software must be easy for the operations teams in or der to keep the system smooth and running, it should be as simple as it can get and reduce the complexity to save man hours and finally it amust be able to evolve so that engineers are able to make changes and modifications as its requierments change over time. 

6. Explain the difference between latency and response time
Response time is what the client sees, its the service time plus the network and queue delay. Latency instead is the duration that a request waits to e handled (awaiting service)


