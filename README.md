# Q-DDCA: Decentralized Dynamic Congestion  Avoid Routing in Large-Scale Quantum Networks

This is the minized prototype codes for implementing the Q-DDCA protocol. This code requires the [SimQN](https://github.com/ertuil/simqn) Platform.

## How to Run

1. ``python3 exp1.py``
2. ``python3 exp2.py``
3. ``python3 exp3.py``

NOTE: They will create files to log the results.

## Details

run *exp1.py*, *exp2.py* or *exp3.py* for simulation, and modify the parameters to collect the complete set of results

- *exp1.py*

  Simulate the network's throughput, drop rate, and coefficient of variation in both single-request and multiple-request scenarios under different sending window sizes and specific maximum retry attempts.

- *exp2.py*

  Simulate the network's throughput and drop rate in a single-request scenario across different maximum retry attempts and multiple specific sending window sizes.

- *exp3.py*

  Simulate the memory occupancy of req1 and req2 at node u3 over time, under the given network topology.

## Note and Citation

Please cite:

```
L. Chen et al., "Q-DDCA: Decentralized Dynamic Congestion Avoid Routing in Large-Scale Quantum Networks," in IEEE/ACM Transactions on Networking, doi: 10.1109/TNET.2023.3285093.
```

Copyright: Lutong Chen, Kaiping Xue, and Jian Li, University of Science and Technology of China, 230027, China.

This repo is under MIT licence, see `LICENSE`.
