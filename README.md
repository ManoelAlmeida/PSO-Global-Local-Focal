# PSO-Global-Local-Focal
It's a simple implementation of PSO with Global, Local and Focal topology.

The topologies setup are as follow:

Topology:
	 1 - Gbest;
	 2 - lbest;
	 3 - Focal /When it's chosen FOCAL_BEST_PARTICLE's value is 1.  
	  
Problem:
	 1 - Sphere;
	 2 - Rotated Rastrigin;
	 3 - Rosenbrock.

Problems it is related to objective functions. It's been already developed Sphere, Rotated Rastrigin and Rosenbrock objective functions. 
It's worth to metion that when you choose to use Focal topology, you have to set FOCAL_BEST_PARTICLE equals 1, because in Focal topology one of the particle from the swarm is used to be the responsible to share the better position found in search process.
