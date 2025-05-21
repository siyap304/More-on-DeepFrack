                               _____                      _______               _     
                              (____ \                    (_______)             | |    
                               _   \ \ ____ ____ ____     _____ ____ ____  ____| |  _ 
                              | |   | / _  ) _  )  _ \   |  ___) ___) _  |/ ___) | / )
                              | |__/ ( (/ ( (/ /| | | |  | |  | |  ( ( | ( (___| |< ( 
                              |_____/ \____)____) ||_/   |_|  |_|   \_||_|\____)_| \_)
                                                |_|
                                   
# More-on-DeepFrack

[DeepFrack](https://github.com/PechimuthuMithil/DeepFrack/tree/main?tab=readme-ov-file) is a novel framework developed for enhancing energy efficiency and reducing latency in deep learning workloads executed on hardware accelerators. It is a wrapper around [Timeloop](https://timeloop.csail.mit.edu/). 

## Aim

[Aim](https://ieeexplore.ieee.org/document/9251855) was tested on DeepFrack to get a reduction in both energy and latency when compared to Timeloop.

## High Bandwidth Memory

High Bandwidth Memory (HBM) is an advanced type of memory that stacks multiple DRAM dies vertically and connects them using through-silicon vias (TSVs). 

### Why HBM in DeepFrack?
Bandwidth: Creates a shorter physical distance for data to travel between memory and processor. 
Energy: Less power/bit than DRAM.
Latency: Faster data transfer rates between memory and processors.

### Results

1) Significant energy savings were achieved with the Eyeriss accelerator. Similar evaluations with Aim and Simba showed minimal or no improvement.
2) Simba and Eyeriss significantly reduced latency. Aim showed no change.

#### Simba Analysis

a) On-chip data reuse via distributed SRAM buffers.
b) Minimizing DRAM access frequency.

#### Aim Analysis

a) AIMBus interconnects 
b) No local DRAM bandwidth 





