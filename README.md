# NMPC

in NMPC/src:

g++ NMPC.cpp AuxiliaryController.cpp -L/Users/maggiewang/Workspace/QuadcoptersWorkspace/NMPC/src -lf2c -lm -lblas -lqpopt -lgfortran -larmadillo

NMPC.cpp contains the main function that calls ComputeAuxilliaryController(...).
