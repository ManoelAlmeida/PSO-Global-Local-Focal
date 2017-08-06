# PSO-Global-Local-Focal
It's a simple implementation of PSO with Global, Local and Focal topology.

The topologies setup are as follow:

Topology: <br />
	 1 - Gbest; <br />
	 2 - lbest; <br />
	 3 - Focal /When it's chosen FOCAL_BEST_PARTICLE's value is 1.<br />  
	 <br />
Problem:<br />
	 1 - Sphere;<br />
	 2 - Rotated Rastrigin;<br />
	 3 - Rosenbrock.<br />
	<br />
Problems it is related to objective functions. It's been already developed Sphere, Rotated Rastrigin and Rosenbrock objective functions. <br /><br />
It's worth to metion that when you choose to use Focal topology, you have to set FOCAL_BEST_PARTICLE equals 1, because in Focal topology one of the particle from the swarm is used to be the responsible to share the better position found in search process.
