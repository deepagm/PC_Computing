To run the shared memory code:

/usr/local/cuda-7.0/bin/nvcc -arch compute_35 -code sm_35 heat.cu
./a.out


To run the code of texture memory:

/usr/local/cuda-7.0/bin/nvcc heat.cu -lGL -lglut -lGLU
./a.out



