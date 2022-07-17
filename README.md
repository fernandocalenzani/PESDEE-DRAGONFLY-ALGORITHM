# PESDEE-DRAGONFLY-ALGORITHM
This work proposes a planning methodology of distribution systems formulated as a nonlinear optimization problem, which was solved through the heuristic Dragonfly Optimization Algorithm, which will be developed with the integration between OpenDSS for power flow calculation and Python for collection, modifying the feeder and displaying the results. The Dragonfly Algorithm is responsible for the reconfiguration of the feeder, with the objective function of minimizing the costs of expansion and technical losses. The proposed methodology was tested on the IEEE 123 feeder adapted buses, which is a test network with more than 123 buses, multiple switches, regulators, transformers, etc. Finally, the reconfiguration proposal brought an economy 22% compared to the original expansion plan, simulated with Dragonfly Algorithm, with 30 dragonflies and maximum number of iterations equal to 25, showing the effectiveness of the algorithm when applied to electric power distribution systems.
