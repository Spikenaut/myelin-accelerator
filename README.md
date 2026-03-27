# 🧠 Myelin-Accelerator (Tier 1)

**CUDA Spiking-Network Kernels & Safe Rust FFI Wrappers**

`myelin-accelerator` provides the raw computational power for neuromorphic inference on Blackwell-class GPUs (RTX 5080). It contains highly optimized CUDA kernels for parallel WalkSAT dynamics and spike-train processing.

## Features
- **Parallel WalkSAT**: GPU-accelerated SAT solving for neuromorphic logic.
- **Custom CUDA Kernels**: Built for sub-50µs tick latency.
- **Safe FFI**: High-level Rust abstractions over `cust` and raw PTX.
- **PTX Compatibility**: Includes patches for PTX ISA versioning compatibility across driver versions.

## Historical Lineage (v2.1)
Formerly `neuro-spike-kernels`. Derived from the `dynexsolve.cu` research for neuromorphic SAT solving.

## Usage
Add to your `Cargo.toml`:
```toml
[dependencies]
myelin-accelerator = "0.9.2"
```

## License
GPL-3.0 — See [LICENSE](LICENSE) for details.
