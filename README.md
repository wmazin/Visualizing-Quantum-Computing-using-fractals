# Visualizing Quantum Computing using fractals

**Introduction**
<br />
Quantum computing can be pretty abstract. As a result, it's rather challenging to get the imagination going when dealing with qubits, quantum circuits and quantum states. As people get started using quantum computing, one of the biggest challenges is visualizing the complex mathematics underlying quantum states. Typically, we rely on the [Bloch sphere](https://qiskit.org/textbook/ch-states/representing-qubit-states.html#bloch-sphere) and [Q-sphere](https://quantum-computing.ibm.com/composer/docs/iqx/visualizations#q-sphere-view). However, given the richness of the field of complex numbers, there are plenty of more interesting ways to represent quantum information.
<br />

You'll find two notebooks demonstrating how quantum computing can be visualized using fractals. <br />
The 1-qubit notebook demonstrates this with one qubit in the ideal case, mimicking running on a fault-tolerant quantum computer with a simulator. Try it yourself, either go with the default quantum circuit or create your own 1-qubit quantum circuit and also see how the fractal looks after running on a real quantum computer! <br />
The 2-qubit notebook makes it possible to create fractals that can be used to visualize two-qubit quantum circuits, showing how, e.g., quantum entanglement may look like a fractal. Of course, you may also use a real quantum computer to generate the fractal and compare with the simulated.

Read more about the project in the [blog](https://qisk.it/3NayT1G){:target="_blank" rel="noopener"}.
  
<br />

**Getting started**
1. Upload the notebooks to the [IBM Quantum Lab](https://quantum-computing.ibm.com/) or install [Qiskit locally](https://qiskit.org/documentation/getting_started.html)
2. Run the 1- or 2-qubit notebook with the default quantum circuit yielding both the ideal simulated fractal as well as the fractal generated after running on a real quantum computer. <br />
In the current version nice fractals may be achieved when either the 1-qubit quantum circuit statevector isn't on the axes of the Bloch sphere or you generate a 2-qubit quantum circuit involving all four computational basis states. Both can be checked in the notebooks. <br />
You may need to experiment with different gates, phases and circuits in order to obtain a circuit that generates a beautiful fractal.
3. Get familiar with the [tutorial](https://quantum-computing.ibm.com/composer/docs/iqx/) for the IBM Quantum Composer. 
4. You can also choose to write the qiskit code and not use the Composer.

<br />

**Acknowledgments**
<br />
This project is in honor of my late professor, [Erik Mosekilde](https://www.researchgate.net/profile/Erik-Mosekilde), who inspired me with his persona and his teachings and works on chaos theory, bifurcations, fractals and Turing patterns.

<br />

**License**
<br />
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

**Contact**
<br />
[Wiktor Mazin](https://www.linkedin.com/in/wiktor-mazin-phd-mmt-062321/)
