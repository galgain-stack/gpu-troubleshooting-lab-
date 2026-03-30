# Lab 2 - GPU Monitoring

## Objective
Monitor real-time GPU performance and resource usage.

## Commands Used

nvidia-smi dmon

## Output

```text
root@ubuntu:~# nvidia-smi dmon
# gpu    pwr  gtemp  mtemp     sm    mem    enc    dec    jpg    ofa   mclk   pclk
# Idx      W      C      C      %      %      %      %      %      %    MHz    MHz
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
    0     31     38      -      0      0      0      0      0      0    405    210
^C    0     31     38      -      0      0      0      0      0      0    405    210
```
## Observations
- Power usage is stable at ~31W under idle conditions
- GPU temperature remains consistent at ~38C
- GPU utilization is 0%, indicating no active workload
- Memory and processor clocks (mclk/pclk) are low, reflecting an idle power state


## Interpretation
The GPU is operating in a stable idle state.  
Low power usage, consistent temperature, and reduced clock speeds indicate that no workload is running and the system is conserving energy efficiently.
