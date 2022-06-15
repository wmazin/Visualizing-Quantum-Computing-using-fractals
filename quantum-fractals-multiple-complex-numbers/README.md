# Visualizing Quantum Computing using fractals - based on multiple complex numbers

**Introduction**
<br />
Here, two ideas are explored:
  1. In order to get closer to mimicking the quantum information in a quantum circuit, all the complex amplitudes are leveraged in the fractal art generation. Instead of just utilizing one complex number as described in the previous [blog](https://qisk.it/3NayT1G), a rational function is leveraged, allowing both complex amplitudes of the statevector to be included in the 1-qubit case.
  2. Animations provide not only an artistic expression, but also a lens into how fractals change with rotations - as in the Bloch sphere. 

You'll find two notebooks demonstrating how quantum computing can be visualized using fractals based on two complex numbers. <br />
The notebook "QuantumFractals1qubit1CN_2CN_plots" demonstrates this letting you create three fractals at the same time based on a 1-qubit circuit, with two variations of [Julia set mating](https://mathr.co.uk/blog/2020-01-16_slow_mating_of_quadratic_julia_sets.html) leveraging both complex amplitudes of the statevector and with one complex number for comparison with the original [approach](link to other github). Try it yourself and either go with the default quantum circuit or create your own 1-qubit quantum circuit. You have the option of both using a simulator to mimich running on a fault-tolerant quantum computer and also see how the fractals look after running on a real quantum computer! <br />
With the "QuantumFractals1qubit_sphere_fractals_animation" notebook you can create fractal animations covering (RZ) rotations on the [Bloch sphere](https://qiskit.org/textbook/ch-states/representing-qubit-states.html#bloch-sphere), fractal animations generated with one complex number and two variations of Julia set mating.


Read more about the this part in the [blog](link to LinkedIn article).
<br />
Main [project](https://github.com/wmazin/Visualizing-Quantum-Computing-using-fractals)

<br />

**Instructions**
<br />
See [Getting started](https://github.com/wmazin/Visualizing-Quantum-Computing-using-fractals) 

<br />

**License**
<br />
Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
