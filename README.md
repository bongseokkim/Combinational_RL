# Combinational_RL
Study of Combinational Problem using Reinforcement learning

# Relevent Paper 
+ Attention, Learn to Solve Routing Problems![https://arxiv.org/abs/1803.08475]
+ Combining Reinforcement Learning and Constraint Programming for Combinatorial Optimization[https://arxiv.org/abs/2006.01610]
+ Applying reinforcement learning to plan manufacturing material handling[https://link.springer.com/article/10.1007/s44163-021-00003-3]
+ Constrained Combinatorial Optimization with Reinforcement Learning[https://arxiv.org/pdf/2006.11984]
+ Reinforcement Learning in Manufacturing Control: Baselines, challenges and ways forward [https://www.sciencedirect.com/science/article/pii/S0952197622001130]
+ Deep Reinforcement Learning For Sequence to Sequence Models[https://arxiv.org/abs/1805.09461]
+ Decision Transformer: Reinforcement Learning via Sequence Modeling[https://arxiv.org/abs/2106.01345]
+ Pointer Networks[https://arxiv.org/abs/1506.03134]
+ Combinatorial Optimization by Graph Pointer Networks and Hierarchical Reinforcement Learning[https://arxiv.org/abs/1911.04936]
+ 

# Idea of research 
+ combining RL with constraint programming will be good / making rl selecting some hueristic rules or cp
+ anaolgy of problem: TSP/Constrained Sequential Decision-Making Problem/Constrained Shortest Path Problem/Permutation Learning Problem/Constrained Sequence Generation Problem
+ For thousands of rules, consider hybrid approaches (e.g., RL-CP) to ensure feasibility.
+ 
# Toy Experiment 
1. build Pr-network with RL / TSP
2. make vaild mapping on state,action transiton or action masking

ie., 
Start with cities [0, 1, 2, 3] and coordinates [(0,0), (1,1), (2,0), (3,2)].
State: [], Action Space: [0, 1, 2, 3], Agent picks 2.
State: [2], Action Space: [0, 1, 3], Agent picks 1.
State: [2, 1], Action Space: [0, 3], and so on.


