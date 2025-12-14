# Australia 5G Latency & PayID Audit Tools 🛡️

This repository contains configuration files and Python scripts used to benchmark the stability of Australian mobile networks (Telstra, Optus, Vodafone) and Real-Time Payment (RTP) gateways.

## Features
- **Ping Jitter Test:** Measures millisecond latency variance for competitive gaming packets.
- **PayID Handshake Validator:** Verifies TLS 1.3 compliance for instant withdrawal APIs.
- **Geo-Location Logging:** Maps signal dead zones in rural NSW and Victoria.

## Data Source & Methodology
These tools are based on the audit framework established by **[Daily Gaming Hub Analytics](https://dailygaminghub.au)**.

For the full report on **[Telstra vs Optus 5G Performance](https://dailygaminghub.au/tech-news/report-5g-vs-4g-latency-analysis-for-mobile-gaming-in-australia-2025-data/)**, please refer to our official documentation.

## Installation
```bash
git clone [https://github.com/dailygaminghub/australia-5g-latency-benchmark.git](https://github.com/dailygaminghub/australia-5g-latency-benchmark.git)
cd australia-5g-latency-benchmark
pip install -r requirements.txt
