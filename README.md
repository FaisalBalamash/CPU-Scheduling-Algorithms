# Process Scheduling Simulator

This Java Swing-based application simulates various process scheduling algorithms including FCFS (First-Come, First-Served), Priority, Round Robin, and SJF (Shortest Job First). It provides a graphical user interface for visualizing the execution of these algorithms with simulated processes.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Algorithms](#algorithms)
- [Contributing](#contributing)

## Getting Started

To get started, you'll need to clone this repository and compile the Java source code.

    git clone https://github.com/FaisalBalamash/process-scheduling-simulator.git
    cd process-scheduling-simulator
    javac Main.java
    java Main` 

## Prerequisites

-   Java Development Kit (JDK) 8 or higher.
-   An integrated development environment (IDE) like Eclipse or IntelliJ IDEA is recommended for development.

## Usage

1.  Run the application as mentioned in the "Getting Started" section.
2.  Use the graphical user interface to configure the simulation parameters, such as the number of processes, their arrival times, burst times, and priorities.
3.  Select one of the scheduling algorithms from the dropdown menu (FCFS, Priority, Round Robin, SJF).
4.  Click the "Start Simulation" button to initiate the simulation.
5.  The GUI will display the execution of the selected algorithm, showing the order in which processes are scheduled and their turnaround times.

## Algorithms

### FCFS (First-Come, First-Served)

The FCFS algorithm schedules processes based on their arrival times, and the process that arrives first is executed first.

### Priority

The Priority algorithm schedules processes based on their priority values. The process with the highest priority is executed first.

### Round Robin

The Round Robin algorithm allocates a fixed time quantum to each process. Processes are executed in a cyclic manner, and if a process does not complete within its time quantum, it is moved to the end of the queue.

### SJF (Shortest Job First)

The SJF algorithm schedules processes based on their burst times. The process with the shortest burst time is executed first.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Push your changes to your fork.
5.  Create a pull request to this repository's `main` branch.
