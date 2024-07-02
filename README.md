# Neural Architecture Search Tool 

Developed using Rust and Python with JAX integration.

## Project Structure

- `src/`: Contains Rust source code for NAS algorithms and main application.
  - `main.rs`: Entry point for Rust application, integrates with Python for NAS operations.
  - `utils.rs`: Utility functions for advanced data processing and NAS algorithms.
- `python/`: Directory for Python scripts and virtual environment.
  - `jax-env/`: Python virtual environment.
  - `src/`: Python source code for NAS algorithms and main execution.
    - `main.py`: Coordinates NAS experiments and interacts with Rust components.
    - `utils.py`: Utility functions for data preprocessing and other tasks.
    - `nas_algorithms/`: Directory for NAS algorithms using JAX.
- `Cargo.toml`: Rust package manager file specifying dependencies.
- `README.md`: Project documentation.

## Getting Started

1. **Set up Rust Environment**:
   - Install Rust and Cargo.
   - Navigate to the `nas-tool` directory.

2. **Activate Python Virtual Environment**:
   ```bash
   source python/jax-env/Scripts/activate  # For Windows

3. **Build and Run the Rust Application**:
    ```bash
    cargo run

4. **Explore NAS Algorithms**:

Dependencies
Rust: Ensure you have Rust installed.
Python: Dependencies listed in `python/requirements.txt`
JAX: Python library for implementing NAS algorithms
Ndarray: Rust crate for advanced data processing