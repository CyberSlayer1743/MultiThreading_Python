# MultiThreading using Python
In this repository, we delve into multithreading using Python's threading library.
Experiment conducted on: AMD Ryzen 5600 H Hexa-Core CPU [12 Logical units (thanks to hyperthreading)].

1. We commence by importing various libraries, including Python's threading library for creating multiple threads.
2. An array stores the number of threads for each iteration.
3. Two functions are defined: one for generating 1000 random 1kx1k matrices, and the other for multiplying them with a constant matrix of size 1kx1k.
4. Utilizing the threading library, multiple threads are spawned, with the process visualized through a table and a graph.
5. The results indicate that the minimum time is achieved when the number of threads equals the number of CPUs, which is 12 in this instance.
