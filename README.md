# KnowledgeEngineeringProject
The project is designed to demonstrate some practical skills acquired at the end of the course exam "Knowledge Engineering". 
[Documentation](https://github.com/RayCatcherS/KnowledgeEngineeringProject/blob/main/NotebookSource.ipynb)

## Description
In this project, I simulated the problem of an online service with the goal of optimizing user allocation to available resources (multiplayer matches). To maximize system efficiency, I developed a model based on CSP (Constraint Satisfaction Problem), where the optimal assignment of users to matches is guided by an objective function to be minimized.

This function penalizes suboptimal assignments, favoring:
- matching players with similar skill levels,
- prioritizing players who have been waiting the longest,
- selecting users with a low quitting rate,
- distributing matches in a way that reflects the pool of available players.
  
The adopted approach ensures an effective balance and utilization of resources while also improving the overall gaming experience.
