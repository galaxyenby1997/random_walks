# random_walks
Visualizing Polar Random Walks in the 2D plane

In this jupyter notebook I'm visualizing polar random walks in the 2D plane, and coparing them to expected statistics. What I mean by "polar random walk" is basically, a random walk of unit vectors, all independent, and each one has a unique angle, θ which is a random variable, and identically distributed across the random unit vectors. 

I am visualizing the movement of the random walk according to different θ distributions, for example a uniform(-pi, pi) or Normal(0, pi/2) distribution of the angles. And then I'm calculating the "translation distance" (the actual Pythagoras distance the walk has traveled), looking at a distribution adn comparing it to the theoretical expected.
