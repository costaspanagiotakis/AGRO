# AGRO
AGRO is a substantial evolution of the original Gold Rush Optimizer (GRO) [2].  AGRO introduces fundamental modifications to the search equations,  eliminating the inherent attraction towards the zero coordinates,  while explicitly incorporating objective function values to guide prospectors towards promising regions. 
#
Furthermore, unlike the standard GRO, which relies on fixed probabilities in the strategy selection process, AGRO utilizes a novel adaptive mechanism that prioritizes strategies improving solution quality. This adaptive component, that can be applied to any optimization algorithm with fixed probabilities in the strategy selection,  adjusts the probabilities of the three core search strategies of GRO (Migration, Collaboration, and Panning), in real-time, rewarding those that successfully improve solution quality. 
You can find more details in [1]  
Files: 
   AGRO.m: implementation of the AGRO algorithm 
   runOptimizer.m: running the AGRO algorithm 
[1] C. Panagiotakis, AGRO: An Adaptive Gold Rush Optimizer with Dynamic Strategy Selection,  Algorithms,  19(3), 192, 2026.
[2] Zolfi, K. Gold rush optimizer: A new population-based metaheuristic algorithm. Operations Research and Decisions 2023, 33, 113–150. 
