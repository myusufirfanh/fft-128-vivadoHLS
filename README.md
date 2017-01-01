# fft-128-vivadoHLS
The purpose of this is to synthesis an IP module using Vivado HLS for a program to compute a 128 point FFT using the given inputs with as little resource utilization as possible by using precomputed twiddle factors in an array

testbench.c is for the testbench in Vivado HLS and it will call fft_hls.c (the main program). You can run C synthesis and then RTL synthesis, after that you can export IP module
