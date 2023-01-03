# How to Analyze Sound by Quantum Fourier Transformation and turn it into a Music-Fractal-Film

**Introduction**
<br/>
Here previous [Quantum Fourier Transformation](https://github.com/TMuehge/Quantum-Fourier-Transformation) work is supplemented by translating each bar into fractals following the steps: 

  1.	A 3-qubit QFT quantum circuit is created. The eight complex amplitudes of the 3-qubit statevector are captured with the statevector simulator. 
  2.	Measurement gates are added and the circuit is executed on a noisy quantum simulator (qasm simulator with a noise model). This results in counts and probabilities of each of the eight basis states. 
  3.	Two types of 3-qubit fractals based on Julia set mating are leveraged utilizing the eight complex amplitudes. Four fractal images are created based on these two types of fractals both with (adjusting for the counts) and without noise.

