# Memory Visualizer

Memory Visualizer is a comprehensive educational tool that implements and visualizes key memory management algorithms used in Operating Systems. This project demonstrates both **Memory Allocation Algorithms** and **Page Replacement Algorithms** with an interactive visualization interface.

## Algorithms Implemented

### Memory Allocation Algorithms

#### 1. **First Fit**
The **First Fit** algorithm searches for the first available memory block that is large enough to accommodate the process. It allocates the process to the first free partition that is large enough.

#### 2. **Next Fit**
The **Next Fit** algorithm is similar to First Fit, but instead of starting the search for free memory blocks from the beginning each time, it continues searching from where it left off after the last allocation.

#### 3. **Worst Fit**
The **Worst Fit** algorithm allocates the process to the largest available memory block. This method tries to keep large gaps of free memory that can be utilized for future allocations.

#### 4. **Best Fit**
The **Best Fit** algorithm allocates the process to the smallest available memory block that is large enough to fit the process. This method tries to minimize the unused space in the memory blocks.

### Partitioning Types

#### 1. **Fixed Size Partitions**
In **Fixed Size Partitions**, memory is divided into partitions of fixed size. The OS will allocate each process to one of these partitions, with the process size being smaller than or equal to the partition size.

#### 2. **Variable Size Partitions**
In **Variable Size Partitions**, memory partitions can be of any size, and the process will be allocated to a partition that is just large enough for its size, minimizing waste.

### Page Replacement Algorithms

#### 1. **First In First Out (FIFO)**
FIFO is the simplest page replacement algorithm. It works on the principle of **"first come, first served"** — the oldest page in memory is replaced when a new page needs to be loaded.

#### 2. **Least Recently Used (LRU)**
LRU replaces the page that has not been used for the longest period of time. The algorithm keeps track of the order in which pages were last accessed and replaces the least recently used one when a new page is needed.

#### 3. **Optimal Page Replacement**
Optimal page replacement is an ideal algorithm that replaces the page that will not be used for the longest period of time in the future. This algorithm is theoretical and not feasible in real systems but is useful for comparison purposes.

## Features

- Interactive visualization of memory allocation and page replacement processes
- Support for both **Fixed Size Partitions** and **Variable Size Partitions**
- Calculation of **internal fragmentation** and **external fragmentation** for memory allocation algorithms
- Calculation of **Page Faults** for page replacement algorithms
- User-friendly interface to compare the performance of different algorithms

## Technologies Used

- **Programming Languages**: HTML, CSS, JavaScript
- **Memory Allocation Algorithms**: First Fit, Next Fit, Worst Fit, Best Fit
- **Page Replacement Algorithms**: FIFO, LRU, Optimal
- **Concepts**: Memory Management, Fragmentation, Page Faults

## Getting Started

### Prerequisites

Before running this project, make sure you have the following installed:

- A modern web browser (Chrome, Firefox, Edge, etc.)

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/bytexplorerr/Memory-Visualizer.git
   cd Memory-Visualizer
