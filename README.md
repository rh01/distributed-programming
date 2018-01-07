distributed-programming in java 
--------------


https://www.coursera.org/learn/distributed-programming-in-java


MPI Installation
---------------------------

If you would like to test your solution on your local machine, you will need to install an MPI implementation.

If you are using Ubuntu, you can install OpenMPI with the following commands:


```bash
$ sudo apt-get update
$ sudo apt-get install -y openmpi-bin libopenmpi-dev
```

If you are using Linux or Mac OS, we recommend downloading the OpenMPI implementation from:

https://www.open-mpi.org/software/ompi/v2.0/

and following the build instructions in the "User Builds" section of the included INSTALL file. Following installation, you must also add the created OpenMPI bin/ folder to your PATH and the created OpenMPI lib/ folder to your LD_LIBRARY_PATH (on Linux) or your DYLD_LIBRARY_PATH (on Mac OS).

If you are on Windows or find the installation instructions for OpenMPI difficult to follow, we recommend using print statements and the Cousera autograder to test your code. The Coursera autograder automatically links in an OpenMPI implementation for you.
