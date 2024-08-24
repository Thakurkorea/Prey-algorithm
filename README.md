The objective function is a simple quadratic function where the goal is to maximize the food quality. Higher values represent better food sources.
Each prey is represented by its current position, its resident location (home), and its associated fitness value.
Initialization: The swarm of prey is initialized with random positions and resident locations within the defined bounds.
Disturbance Detection: At each iteration, each prey has a 30% chance to detect a disturbance (simulated by a random probability). 
If a disturbance is detected, the prey moves randomly to simulate "hiding." If no disturbance is detected, the prey moves towards the best-known fooding place (exploiting the best position found).
Returning to Resident: Every 10 iterations, the prey return to their resident locations (home).
Global Best: The best position found by the swarm is continuously updated.
