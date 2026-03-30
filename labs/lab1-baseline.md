# Lab 1 - GPU Baseline Validation

## Objective
Verify GPU visibility and driver functionality.

## Commands Used
nvidia-smi

## Output
````text
+-----------------------------------------------------------------------------------------+
| NVIDIA-SMI 575.51.03              Driver Version: 575.51.03      CUDA Version: 12.9     |
|-----------------------------------------+------------------------+----------------------+
| GPU  Name                 Persistence-M | Bus-Id          Disp.A | Volatile Uncorr. ECC |
| Fan  Temp   Perf          Pwr:Usage/Cap |           Memory-Usage | GPU-Util  Compute M. |
|                                         |                        |               MIG M. |
|=========================================+========================+======================|
|   0  NVIDIA GeForce RTX 3080        Off |   00000000:00:07.0 Off |                  N/A |
|  0%   38C    P8             31W /  370W |       1MiB /  10240MiB |      0%      Default |
|                                         |                        |                  N/A |
+-----------------------------------------+------------------------+----------------------+

+-----------------------------------------------------------------------------------------+
| Processes:                                                                              |
|  GPU   GI   CI              PID   Type   Process name                        GPU Memory |
|        ID   ID                                                               Usage      |
|=========================================================================================|
|  No running processes found                                                             |
+-------------- ------------------------------------

        -   
## Observations
- GPU detected: RTX 3080
- Driver version: 575.51.03
- CUDA version: 12.9
- GPU utilization: 0% (idle)

## Interpretation
The GPU is healthy and properly recognized by the system.

## Next Steps
Proceed to monitoring and diagnostics testing.
