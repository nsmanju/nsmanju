### Quantitative Infrastructure Consultant

**Hong Kong Permanent Resident | C++20 Low-Latency Market Data Fabric | SFC Auditable Systems**

**Flagship Project — hkex-omdc-fabric:**
- HKEX OMD-C Binary Market Data Parser
- SPSC 8192 Lock-Free Ring Buffer (32B Tick, 64B cache-line padded)
- L2 OrderBook Depth 10 reconstruction <1us
- AF_XDP Kernel Bypass + UDP Multicast fallback
- Live performance: 126,804 ticks zero drops, 2M ticks/sec, p50 0.17us p99 0.40us
- Ubuntu 24.04 CLI, measured with rdtsc + lfence, taskset
- Public market data only, deterministic and reproducible for audit

**Current Public Repositories:**
- hkex-omdc-fabric — Low-latency market data fabric
- low-latency-trading-system — Low-latency system using Yahoo Finance data
- memory-allocation-performance — Comparison of direct OS heap vs preallocated chunk allocator
- portfolio-optimization — Portfolio management using function pointers in C++
- cpp-hft-straddle — C++ HFT straddle implementation
- tesla-options-straddle — Tesla options straddle strategy
- football-simulation-cpp — Football match simulation in C++ using vectors and random number generation

**Private Repositories:**
- Previous research repositories related to cryptocurrency have been made private to focus on SFC-auditable infrastructure for licensed financial institutions.

**Technology:** C++20/23, par_unseq, SPSC, AVX2, AF_XDP, CMake, perf, Ubuntu 24.04

**Availability:** Day-rate consulting, greenfield builds, immediate availability, Hong Kong PR

**Scope:** IT Consulting and Software Development for licensed financial institutions only. No virtual asset service provider activity. No client funds. Public data only.

36.9M operations per second suite — 514K screening, 1.4M vol arb, 35M funding arb simulations
