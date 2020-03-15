# hanoi-problem
The tower of Hanoi is a mathematical puzzle that consists of three rods and a number of disks of different sizes which can slide onto any rod. The puzzle starts with the disks in a neat stack in ascending order of size on one rod, the smallest at the top, thus making a conical shape.
The objective of the puzzle is to move the entire stack to another rod, obeying the following simple rules:

* Only one disk can be moved at a time.
* Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or on an empty rod.
* No larger disk may be placed on top of a smaller disk.

The minimal number of moves required to solve a Tower of Hanoi puzzle is 2n − 1, where n is the number of disks. With 3 disks, the puzzle can be solved in 7 moves for instance.

In this notebook we solve the puzzle with 5 disks which of course can be changed to any number n. In a first section a simple algortihm is used in order to print out the moves that has to be made in order to solve the puzzle. In a second stage the moves are visulatized by making use of Sagemath software.

In order to solve the puzzle you have to make use of recursion.

## Getting started and prerequisites
The examples given in this project are made with the Jupyter-Notebook of the Anaconda Distribution using the Sagemath Kernel 9.0.0. In order to solve the mathematical problems this project uses [Sagemath](https://www.sagemath.org/) open source software.

### Installation of Anaconda
Visit the [Anaconda website](https://www.anaconda.com/distribution/) and download the Anaconda distribution for your system (this project is based on Python 3.7)

### Installation of Sagemath
Visit the [Sagemath website](https://www.sagemath.org/download.html) and download the distribution for your system.

## Author
* j-stalder(https://github.com/j-stalder)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
