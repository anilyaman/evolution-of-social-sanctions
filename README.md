The files contains the code used for the model and experiments in paper entitled as:
Yaman, A., Leibo, J. Z., Iacca, G., & Lee, S. W. (2022). The emergence of division of labor through decentralized social sanctioning. 
(Accepted, Proceedings of the Royal Society B). https://arxiv.org/abs/2208.05568

The code is based on Matlab. We provide implementation of two games we refer as settlement maintenance and common pasture. Main files runs the evolutionary processes for the social sanctioning rules 30 times on these games and generates the results. Below, you can find a short description of *.m files that are included into the software.

In case of settlement maintenance problem, the scripts were structured as follows:
"main_settlement.m" - Launches 30 independent runs for each problem variations and records the results.
"GA_settlement.m" - Executes the cultural evolution process of a single evolutionary run of social norms.
"evalIndGAS.m" - Evaluates a single social norm on the problem.
"game_settlement.m" - Simulates the specified problem.
"plotFitnessTrend.m" - Script for visualization of the results in terms of learning processes on the problem.
"visualizeAgents.m" - Script for visualization of the agent role distributions in a group.
"sanction2string.m" - Script for parsing the results to a string form of social sanctioning rules.
"visualizeFinalSelections.m" - Visualization of the final selection of the agent roles of the best social sanctions (this script selects the best social sanctioning rule, so sanction2string first).

Similar structure is used for the rest of the algorithm variations.
