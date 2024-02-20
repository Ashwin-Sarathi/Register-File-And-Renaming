# Register-File-and-Renaming
Implementation of the register file and register renaming mechanism for a modern superscalar microarchitecture. The module is implemented as a C++ class. This is a project as a part of ECE 721 (Advanced Microarchitecture) of the Computer Engineering course at North Carolina State University under professor Eric Rotenburg.

This project produced the rename class to implement an out of order dynamic scheduler. Using a fully comprehensive active list, free list and branch checkpoints, this simulator enables the roll back of the simulator state in case of a branch misprediction and also allows a full squash and recovery of the pipeline in case of a load violation. 

Unfortunately, this simulator cannot be fully run without the entire executable and the sample trace information. However you can build the executable using the command "make".

The main functions of the class are explained in detail in the renamer.h file, and it's implementation can be found in the renamer.cc file
