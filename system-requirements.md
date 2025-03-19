# Hardware Requirements 

Official Docs: https://docs.inference.supply/hardware

**Minimum System Requirements**

- A GPU in the list below with **at least 8GB of VRAM**
- 8GB RAM
- 30GB free disk space
- Reliable 100Mbps+ network bandwidth. Test it here: [Fast.com](https://fast.com/)

## Supported Apple Silicon Chips

Kuzco supports a range of Apple Silicon chips, provided they meet the following minimum system requirements:

- **8GB RAM**
- **30GB free disk space**
- **Reliable 100Mbps+ network bandwidth**

| Chip Series | Variants                   | Notes                                                                 |
|-------------|---------------------------|-----------------------------------------------------------------------|
| M1          | M1, M1 Pro, M1 Max, M1 Ultra | Fully supported                                                       |
| M2          | M2, M2 Pro, M2 Max, M2 Ultra | Fully supported                                                       |
| M3          | M3, M3 Pro, M3 Max          | Fully supported (latest generation as of 2025)                        |
| M4          | M4, M4 Pro, M4 Max          | Fully supported (latest generation released in 2024)                  |

<Callout emoji="💡">
  For Mac users, we recommend launching your worker through the terminal using the CLI commands.  
  Detailed instructions can be found here: [Kuzco CLI Documentation](https://docs.kuzco.xyz/kuzco-cli).  
  Navigate to the "CLI" tab in the "Launch Worker" section of the [Kuzco Dashboard](https://kuzco.xyz/dashboard) for specific steps.
</Callout>


## Supported GPUs


| GPU Model | VRAM | Manufacturer |
|-----------|------|--------------|
| RTX 4090 | 24GB GDDR6X | NVIDIA |
| RTX 4080 | 16GB GDDR6X | NVIDIA |
| RTX 4000 | 8GB GDDR6 | NVIDIA |
| RTX 3090 Ti | 8GB GDDR6X | NVIDIA |
| RTX 3090 | 8GB GDDR6X | NVIDIA |
| A10 | 24GB GDDR6 | NVIDIA |
| A100 | 40GB/80GB HBM2e | NVIDIA |
| A30 | 24GB HBM2 | NVIDIA |
| A40 | 48GB GDDR6 | NVIDIA |
| A4000 | 16GB GDDR6 | NVIDIA |
| A5000 | 24GB GDDR6 | NVIDIA |
| A6000 | 48GB GDDR6 | NVIDIA |
| M60 | 16GB GDDR5 | NVIDIA |
| P100 | 16GB HBM2 | NVIDIA |
| P40 | 24GB GDDR5X | NVIDIA |
| Quadro GP100 | 16GB HBM2 | NVIDIA |
| Quadro GV100 | 32GB HBM2 | NVIDIA |
| Quadro M6000 24GB | 24GB GDDR5 | NVIDIA |
| Quadro P5000 | 16GB GDDR5X | NVIDIA |
| Quadro P5200 | 16GB GDDR5 | NVIDIA |
| Quadro P6000 | 24GB GDDR5X | NVIDIA |
| RTX 5000 | 24GB GDDR6 | NVIDIA |
| RTX 6000 | 48GB GDDR6 | NVIDIA |
| RTX 8000 | 48GB GDDR6 | NVIDIA |
| T4 | 16GB GDDR6 | NVIDIA |
| TITAN RTX | 24GB GDDR6 | NVIDIA |
| MI100 | 32GB HBM2 | AMD |
| MI200 | 64GB HBM2e | AMD |
| MI210 | 64GB HBM2e | AMD |
| MI250 | 128GB HBM2e | AMD |
| MI250X | 128GB HBM2e | AMD |
| MI300 | 128GB HBM3 | AMD |
| MI300A | 128GB HBM3 | AMD |
| MI300X | 192GB HBM3 | AMD |
| MI60 | 32GB HBM2 | AMD |
| SSG | 16GB HBM2 | AMD |
| V340 | 32GB HBM2 | AMD |
| Vega II | 32GB HBM2 | AMD |
| Vega II Duo | 2x32GB HBM2 | AMD |
| VII | 16GB HBM2 | AMD |
| W6800 | 32GB GDDR6 | AMD |
| W6800X | 32GB GDDR6 | AMD |
| W6800X Duo | 2x32GB GDDR6 | AMD |
| W6900X | 32GB GDDR6 | AMD |
| W7700 | 16GB GDDR6 | AMD |
| W7800 | 32GB GDDR6 | AMD |
| W7900 | 48GB GDDR6 | AMD |
| 6800 | 16GB GDDR6 | AMD |
| 6800 XT | 16GB GDDR6 | AMD |
| 6900 XT | 16GB GDDR6 | AMD |
| 6900 XTX | 16GB GDDR6 | AMD |
| 6950 XT | 16GB GDDR6 | AMD |
| 7600 XT | 16GB GDDR6 | AMD |
| 7800 XT | 16GB GDDR6 | AMD |
| 7900 GRE | 16GB GDDR6 | AMD |
| 7900 XT | 20GB GDDR6 | AMD |
| 7900 XTX | 24GB GDDR6 | AMD |


# Software Requirements

## Software Requirements for PC Users

1. For Windows Install WSL - https://learn.microsoft.com/en-us/windows/wsl/install#install-wsl-command

2. For Windows Install Ubuntu after Installing WSL - https://apps.microsoft.com/detail/9PDXGNCFSCZV?hl=en-us&gl=IN&ocid=pdpshare

3. For macOS If you have Installed Homebrew (https://brew.sh/) to manage packages on OS X,
run this command to install Git.
```
brew install git
```
