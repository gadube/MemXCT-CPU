# SC20 SCC Reproducibility Challenge Instructions

## Compile

### Make Sure Dependencies are Installed

1. C++ Compiler
2. CUDA Compiler
3. MPI Compiler

### Modify Makefile

## Download Datasets

We provide the challenge datasets over Box. Dimensions (Theta x Rho) and corresponding application memory footprints are given below.

**Test Datasest:**

* ADS1 (360x256): 512 MB
* ADS2 (750x512): 3.6 GB
* ADS3 (1500x1024): 28 GB
* ADS3 (2400x2048): 180 GB

**Challenge Datasets:**
TBA

Each dataset requires a theta file and a sinogram file. Direct download from Box to your cluster. 

```
wget https://uofi.box.com/s/ql76fxfrnec1jdl8dc4f2g4ihwekn9oj -O ADS1_theta.bin
wget https://uofi.box.com/s/zmt3vq5k0jaqgcay4a7yscv2a0viyxlc -O ADS1_sinogram.bin

wget https://uofi.box.com/s/yrsr9brzl6q03bmnunfk65k33ykvfr8o -O ADS2_theta.bin
wget https://uofi.box.com/s/wssrib7ud9na1k5zxxjm3kabd2bcrjwu -O ADS2_sinogram.bin

wget https://uofi.box.com/s/vi1uiecpqqiz7rjtty6fbxxwn1feoib0 -O ADS3_theta.bin
wget https://uofi.box.com/s/icxtknbrndv8i2d83mc87ppjxepty8jz -O ADS3_sinogram.bin

wget https://uofi.box.com/s/tbjk9dksog7qqick66nbcnq4ngais1yd -O ADS4_theta.bin
wget https://uofi.box.com/s/ki7smuurh34cleayvwfxhjfn9mgsnega -O ADS4_sinogram.bin

```

## Run 
Run the application using run.sh

## Inspect

Download [Fiji](https://fiji.sc)

