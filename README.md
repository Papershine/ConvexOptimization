#  UBC Mathematics Summer Reading Program 2024
## Convex Optimization

This project investigates the optimal placement of a server or multiple servers within a city of multiple users, in order to
minimize the latency between each user and the server. In this project, I used Jupyter, Python, and NumPy as the general tools
to find the solutions to the optimal placement.

The placement of one server can be formalized into a convex optimization problem, which was solved using both a `cvxpy` solver 
and a manually implemented gradient descent algorithm. The code used can be viewed in the `OneServer.ipynb` file.

The placement of more servers is known to be a NP-hard non-convex integer program problem, which was approximated using a `k-medians`
approximation algorithm in the `pyclustering` package. The code used can be viewed in the `FiveServers.ipybb` file.

The theoretical mathematical background, methodology and other relevant information can be viewed in the report writeup at [srp.pdf](srp.pdf).