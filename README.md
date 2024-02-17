This is a code of algorithm genetic for travel salesman problem and written in python language.
I use TSPLIB benchmark as my data to evaluate the algorithm. you can check here http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/ to get another data of TSP such as in TSP Simetris or Asimetris.
Here I only use Data TSP Simetris with the name file "att48.tsp"

📝File "Code_1.ipynb" using genetic algorithm where:
- Initial population generation: random initialization method
- Selection: Roulette Wheel Selection
- Crossover: Two Point Crossover
- Mutation: Swap Mutation
- Elitism

📝File "Code_2.ipynb" is using genetic algorithm and also use selection, crossover and mutation operator like as "Code_1.ipynd", but here, I use GPM (Greedy Permuting Method) to initial population generation. And the result is better than when i use random initialization method. You can read a paper discussing GPM here https://ieeexplore.ieee.org/document/8473531/citations?tabFilter=papers#citations


What I use✏️✏️✏️✏️✏️
- Python 3.9.13
- anaconda 2022.10
