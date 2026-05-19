# Coral NPU HDL

This repository contains the Chisel-based hardware design for the [Coral NPU](https://github.com/google-coral/coralnpu).
It has been restructured to be built with `sbt`.

## Project Overview

The Coral NPU is a hardware accelerator designed for machine learning tasks.
This project implements the core architecture using Chisel, a hardware construction language embedded in Scala.

### Current Features

- RISC-V Scalar Core (`SCore`)
- Optional RISC-V Vector extension (`RvvCore`)
- Support for AXI and TL-UL bus protocols
- L1 Instruction and Data Caches
- Tightly Coupled Memory (TCM) support

## Future Plans: GEMM Accelerator

We plan to integrate a GEMM (General Matrix-Matrix Multiplication) accelerator into the Coral NPU.

