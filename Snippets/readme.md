# ${Code \space Snippets}$

This folder contains the ***Code Snippets*** for the ***Quantum Entanglement and Superposition***. The Codes provide the glimpse of the Quantum Computation.

## ${Quantum \space Superposition}$

```java
circuit.h(Qreg[0])       // Creating a Hadamard gate for the first Qbit...
circuit.draw('mpl')
```

The Hadamard Gate is used for performing superposition on a Qbit. Since Hadamard gate is unary gate it works on only one Qbit.


## ${Quantum \space Entanglement}$

```java
circuit.cx(Qreg[0], Qreg[1])      // Creating a Control Negation gate...
circuit.draw('mpl')
```

The Control Negation Gate or CNOT Gate is used for Entangling two Qbits such that the state on one Qbit can be determined by observing other Qbit.

## ${Contributed \space By}$
***Vishu Kalier***
