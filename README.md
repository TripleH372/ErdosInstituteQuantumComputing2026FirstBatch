# ErdosInstituteQuantumComputing2026FirstBatch
## First Batch Mini Project: Multi Controlled U Gate

Here, we write a Qiskit function that takes two inputs: a positive integer $n$ and a matrix $U \in U(2)$ and outputs a quantum circuit on $n+1$ qubits, possibly with further ancillas, that implements a multi controlled $U$ gate, $C^nU$, that is:
\[C^nU|x\rangle_n|y\rangle_1=\begin{cases}\;|x\rangle_nU|y\rangle_1\,, & \text{if } x=(1, 1, \ldots, 1)\\ \;|x\rangle_n|y\rangle_1\,, & \text{otherwise}\end{cases}\]
