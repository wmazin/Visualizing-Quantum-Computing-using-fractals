# Visualizing Quantum Computing using fractals

**Introduction**
<br />
Quantum computing can be pretty abstract. As a result, it's rather challenging to get the imagination going when dealing with qubits, quantum circuits and quantum states. As people get started using quantum computing, one of the biggest challenges is visualizing the complex mathematics underlying quantum states. Typically, we rely on the [Bloch sphere](https://qiskit.org/textbook/ch-states/representing-qubit-states.html#bloch-sphere) and [Q-sphere](https://quantum-computing.ibm.com/composer/docs/iqx/visualizations#q-sphere-view). However, given the richness of the field of complex numbers, there are plenty of more interesting ways to represent quantum information.<br />

There are two types of notebooks demonstrating how quantum computing can be visualized using fractals: <br />
<b>quantum-fractals-one-complex-number</b> folder: You'll find 1- and 2-qubit notebooks showing how to create fractals based on one complex number, both in the ideal case, mimicking running on a fault-tolerant quantum computer with a simulator and after running on a real quantum computer! <br />
<b>quantum-fractals-multiple-complex-numbers</b> folder: You'll find a 1-qubit notebook showing how to create even more astonishing fractals based on two complex numbers (the statevector's complex amplitudes) with a quantum simulator and after running on a real quantum computer. The second notebook makes it possible to create fractal animations and relate them to rotations on the Bloch sphere.<br /> 

Read more about the project in the<br />
* [Qiskit blog post](https://qisk.it/3NayT1G) (the first blog with fractals based on one complex number)
* [LinkedIn blog post](https://www.linkedin.com/pulse/create-new-fractal-art-animations-wiktor-mazin-phd-mmt/) (the latest blog with fractals based on multiple complex numbers)
  
<br />


**Getting started**
1. Upload the notebooks to the [IBM Quantum Lab](https://quantum-computing.ibm.com/) or install [Qiskit locally](https://qiskit.org/documentation/getting_started.html) 
2. Notebooks in the <b>quantum-fractals-one-complex-number</b> folder: Run the 1- or 2-qubit notebook with the default quantum circuit yielding both the ideal simulated fractal as well as the fractal generated after running on a real quantum computer. <br />
In the current version nice fractals may be achieved when either the 1-qubit quantum circuit statevector isn't on the axes of the Bloch sphere or you generate a 2-qubit quantum circuit involving all four computational basis states. Both can be checked in the notebooks. <br /> <br />
Notebooks in the <b>quantum-fractals-multiple-complex-numbers</b> folder: Run the 1-qubit plots notebook with the default quantum circuit yielding both ideal simulated fractals as well as the fractals generated after running on a real quantum computer.<br />
Run the animation notebook with the default quantum circuit resulting in four animations; RZ rotations on the Bloch sphere, fractal animations generated with one complex number and two variations of Julia set mating.<br /><br />
You may need to experiment with different gates, phases and circuits in order to obtain a circuit that generates beautiful fractals. <br />
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

<br />

**Contact**
<br />
[Wiktor Mazin](https://www.linkedin.com/in/wiktor-mazin-phd-emba-062321/)

