# How to Analyze Sound by Quantum Fourier Transformation and turn it into a Music-Fractal-Film

**Introduction**
<br/>
Here previous [Quantum Fourier Transformation](https://github.com/TMuehge/Quantum-Fourier-Transformation) work is supplemented by translating each bar into fractals following the steps: 

  1.	A 3-qubit QFT quantum circuit is created. The eight complex amplitudes of the 3-qubit statevector are captured with the statevector simulator. 
  2.	Measurement gates are added and the circuit is executed on a noisy quantum simulator (qasm simulator with a noise model). This results in counts and probabilities of each of the eight basis states. 
  3.	Two types of 3-qubit fractals based on Julia set mating are leveraged utilizing the eight complex amplitudes. Four fractal images are created based on these two types of fractals both with (adjusting for the counts) and without noise.


**Instructions**
<br />
See [Getting started](https://github.com/wmazin/Visualizing-Quantum-Computing-using-fractals) 

**License - fractals**
<br />
Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
