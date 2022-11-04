# Simple CUDA matrix multiplication test

## Prerequisites

```bash
$ nvcc -V
Cuda compilation tools, release 10.1, V10.1.243

$ nvidia-smi
Fri Nov  4 12:55:01 2022       
+-----------------------------------------------------------------------------+
| NVIDIA-SMI 510.39.01    Driver Version: 510.39.01    CUDA Version: 11.6     |
|-------------------------------+----------------------+----------------------+
```

## Quick-start

```bash
$ nvcc matrix_Multiplication.cu  -o mult

$ ./mult
CudaDevice found! Device count: 8
Enter m n n k :
256 256 256 256
GPU time= 0.039680 ms
CPU time= 75.018000 ms
Results are equal!
```

If everything is setup properly, your GPU should show a faster time then your CPU.


