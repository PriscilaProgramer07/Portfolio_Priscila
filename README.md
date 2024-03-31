# High Performance Python Computing

This project explores various aspects of high-performance computing in Python, focusing on the Julia Set as a case study for CPU-bound problems. It encompasses a broad range of techniques from benchmarking and profiling to optimization with Cython, alongside a detailed investigation into Python data structures, broadcasting with arrays, and the efficient manipulation of dictionaries and sets.

## Part 1: Benchmarking and Profiling

We begin with an exploration of the Julia Set, implementing functions to calculate it and visualizing the results in grayscale. We introduce a custom `timefn` decorator for performance measurement and utilize the `timeit` and `cProfile` modules for a comprehensive performance analysis.

### Key Topics

- Calculation and visualization of the Julia Set.
- The `timefn` decorator for profiling.
- Coarse and detailed measurement of execution speed and function call costs.
- High-level analysis with `snakeviz` and line-by-line profiling to identify bottlenecks.

## Part 2: List and Tuples

A detailed examination of list and tuple operations, focusing on their performance implications. Operations include insertion, deletion, and append actions, with timing measurements presented in comparative tables.

## Part 3: Dictionaries and Sets

Utilizing the "Marco Geoestadístico" from INEGI, we analyze the evolution of "Áreas Geoestadísticas Básicas" (AGEBs) in Mérida, Yucatán, between 2010 and 2020, showcasing the power of sets in Python for data analysis.

## Part 4: Matrix and Vector Computations

Exploration of array broadcasting and rewriting a particle simulator with NumPy, demonstrating the performance benefits of leveraging NumPy for numerical computations.

## Part 5: Compiling to C with Cython

An in-depth look at optimizing Python code with Cython, including various strategies for enhancing the performance of the lattice update function in the Conway’s Game of Life simulation. We conclude with a performance comparison chart showcasing the runtime improvements across different implementations.

## Getting Started

This project requires Python 3.x, along with Jupyter Notebook for exploring the `.ipynb` files. Install dependencies as follows:

```bash
pip install -r requirements.txt
```

For Cython modules, ensure Cython is installed and compile them as described in the provided setup instructions.

## Usage

Run Jupyter Notebook to explore the `.ipynb` files:

```bash
jupyter notebook
```

For performance profiling and benchmarking, refer to the individual sections in the notebooks corresponding to each part of the project.

## Contributing

Contributions to improve the implementations or extend the comparison are welcome. Please follow the project's contribution guidelines for submitting issues or pull requests.

## Authors

- Priscila Tzuc Alonzo

## License

Specify the license under which this project is released, allowing others to understand how they can use, modify, and distribute the code.

## Acknowledgments

- Gaston Julia, for the Julia Set.
- Micha Gorelick & Ian Ozsvald, "High Performance Python".
- Jake VanderPlas, "Python Data Science Handbook".
- The Python community for invaluable tools and libraries.
