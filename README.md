# sipeed-lichee-rv-gadget-snap

Gadget snap for running Ubuntu Core 20 on a Sipeed Lichee RV.

## Build Instructions

Building this requires Ubuntu 20.04 and the snapcraft snap.

Cross-compile:

    snapcraft --destructive-mode --target-arch=riscv64 --enable-experimental-target-arch
  
Native build:

    snapcraft --destructive-mode
    
