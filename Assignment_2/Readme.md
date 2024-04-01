In this report, I have discussed the application of a genetic algorithm (GA) to optimize task assignments in a multi-robot system. I have introduced new approaches added to the GA implementation to improve optimization effectiveness.

Approach: I utilized a GA approach comprising initialization, evaluation, selection, crossover, mutation, and replacement steps. The GA implementation was enhanced with new approaches to address specific optimization challenges.

New Approaches:
(1) Fitness Function Enhancement:
I enhanced the fitness function to consider task priority, workload balance, and robot efficiency.
Task priorities were weighted to prioritize critical tasks effectively.
Workload balance was computed to ensure fair distribution among robots.

(2) Selection Process Improvement:
I implemented tournament selection to select parents for crossover based on fitness scores.
This approach promotes diversity and prevents premature convergence.

(3) Crossover Operation Enhancement:
I employed single-point crossover to create offspring from selected parents.
Offspring generation was controlled by a crossover rate to balance exploration and exploitation.

(4) Mutation Operation Enhancement:
I applied random mutation to introduce diversity in the population.
The mutation rate was adjusted to control the rate of exploration.

Analysis:
The enhanced fitness function effectively captured the influence of robot efficiency and task priority on task assignments.
Improved selection, crossover, and mutation operations contributed to better convergence and diversity in the population.
The GA successfully optimized task assignments, considering various factors such as workload distribution and task priorities.


Challenges Faced: Designing and implementing effective selection, crossover, and mutation operations required careful consideration of parameters and balancing exploration and exploitation.

Conclusion: The enhanced GA implementation effectively optimized task assignments in a multi-robot system, considering robot efficiency and task priority. The new approaches improved convergence and diversity in the population, leading to more effective optimization.



