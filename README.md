# Cache Simulation Project for Matrix Multiplication Efficiency

## Project Overview
This project enhances matrix multiplication efficiency through a detailed cache simulation. Key contributions were made in [`YOURCODEHERE.c`](Project_files/YOURCODEHERE.c) within a larger framework simulating cache operations. This project focuses on understanding and optimizing cache hierarchy impacts on computational efficiency.

## Getting Started
### Prerequisites
- GCC compiler
- Access to a system with a Linux kernel

### Installation
1. Clone or download the repository to your machine.
2. Extract and navigate to the project directory.

### Usage
1. Core modifications are in [`YOURCODEHERE.c`](Project_files/YOURCODEHERE.c), which contains the main cache simulation logic.
2. Compile the project using the provided [`Makefile`](Project_files/Makefile): Run `make` to build the executable.
3. Test the implementation with `make test`.

## Implementation Details
Modifications in [`YOURCODEHERE.c`](Project_files/YOURCODEHERE.c) include:
- Implementing cache access and manipulation functions.
- Optimizing data movement between cache layers.

The project includes other files forming the simulation framework:

- [`csim.c`](Project_files/csim.c) & [`csim.h`](Project_files/csim.h): Define cache structure and initialization functions.
- [`NMM-cachesim.c`](Project_files/NMM-cachesim.c) & [`NMM.h`](Project_files/NMM.h): Handle matrix multiplication and cache simulation integration.
- [`utils.c`](Project_files/utils.c) & [`utils.h`](Project_files/utils.h): Provide utility functions for the simulation.
- [`Makefile`](Project_files/Makefile): Contains commands for compiling and testing the project.

## Testing
- Use `make test` to run predefined test cases.
- The file [`NMM-csim.WORKING.testout`](Project_files/NMM-csim.WORKING.testout) contains correct output for debugging and verification.

## File Descriptions
- [`csim.c`](Project_files/csim.c): Source file for cache operations.
- [`csim.h`](Project_files/csim.h): Header file defining cache structures.
- [`Makefile`](Project_files/Makefile): Compilation and cleaning instructions.
- [`NMM.h`](Project_files/NMM.h): Definitions for matrix multiplication parameters.
- [`NMM-cachesim.c`](Project_files/NMM-cachesim.c): Integration of cache simulation with matrix multiplication.
- [`NMM-csim.WORKING.testout`](Project_files/NMM-csim.WORKING.testout): Correct output for test cases, useful for debugging.
- [`utils.c`](Project_files/utils.c): Utility functions for the simulation.
- [`utils.h`](Project_files/utils.h): Header file for utility functions.
- [`YOURCODEHERE.c`](Project_files/YOURCODEHERE.c): Core file containing implemented cache functionalities.
- [`YOURCODEHERE.h`](Project_files/YOURCODEHERE.h): Header file for functions defined in [`YOURCODEHERE.c`](Project_files/YOURCODEHERE.c).

## Contributions
This project is part of an educational assignment. External contributions are not applicable, but discussions and insights are welcome.

## Author
- Vyomakesh Puduru

## Acknowledgments
- Thanks to the course instructor Professor 	
[`Jack Sampson`](https://www.eecs.psu.edu/departments/directory-detail-g.aspx?q=jms1257) and peers for foundational support.
- Acknowledges the provided framework as integral to the project.
