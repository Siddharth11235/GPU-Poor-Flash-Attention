# Flash Attention for the GPU Poor

This module is designed to develop Flash-Attention 3 which is optimized for big GPUs such as the H100, for smaller GPUs. The following strategies are currently beign considered.

* Aggressive tiling strategies optimized for smaller VRAM sizes
* Dynamic block size adjustment based on available memory
* Selective sparsity patterns that maintain quality while reducing memory footprint


