[![Snap Status](https://build.snapcraft.io/badge/kz6fittycent/mprime.svg)](https://build.snapcraft.io/user/kz6fittycent/mprime)

# mprime
A snap for mprime

## About
Prime95 has been a popular choice for stress / torture testing a CPU since its introduction, especially with overclockers and system builders. Since the software makes heavy use of the processor's integer and floating point instructions, it feeds the processor a consistent and verifiable workload to test the stability of the CPU and the L1/L2/L3 processor cache. Additionally, it uses all of the cores of a multi-CPU / multi-core system to ensure a high-load stress test environment.

## How to install the snap

```
sudo snap install --edge mprime --devmode
```

## To run the snap

From your terminal, type: `mprime`

## NOTE
This snap does NOT ship with mprime, you MUST have an internet connection in order to download it for the first time. Once downloaded, the snap will initiate the binary. If you remove the snap, you remove the binary (it's stored in the snap's directory). 
