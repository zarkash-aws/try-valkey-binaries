# Try-Valkey Binary Image Repository

This repository contains the binary files necessary for the Try-Valkey project. The repository is organized by Valkey versions, with each version stored in its own directory.

## Repository Structure 

Each version of the project has its own directory, named according to its version tag. Within each version directory, you will find the following subdirectories:

1. **bin**
Contains the binary files required for the specific version. This includes the necessary executables for running the emulator and the Valkey server. Inside the bin directory, you will also find:
    - **fs:** Stores the binary files for the filesystem, generated during the build process. These files include the configurations, resources, and boot information required to load the system.
    - **state:** Contains compressed binary files representing a booted state of the system. These files capture the state of the system after it has been booted and customized.
2. **vos**
Contains the files necessary for running the image directly in the browser, including emulator files and other dependencies required for browser-based execution.
3. **example**
A working example demonstrating how to use Try-Valkey with this version. 
