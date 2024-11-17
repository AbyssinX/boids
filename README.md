# Boids
This is our implementation of the Boids algorithm in Haskell.
Craig Reynolds invented the Boids algorithm in 1986 to simulate group motion of birds, fish, flies, etc.
He noticed that the flocking behavior is governed by three main rules:
* Separation—the tendency to avoid crowding.
* Alignment—the tendency to steer towards the average heading of local flockmates.
* Cohesion—the tendency to move towards the average position of local flockmates.

The parameters that amplify or suppress rules described above were chosen to appropriately simulate the flock of birds. However, those are tunable and can encode other animals' group motion. The color marks the speed of boids, ranging from yellow to red: the redder the color, the faster a boid moves.

