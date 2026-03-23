# Instances_Cobot_Two_sided_ALBP2
**Version:** 1.1.0  
**Last Updated:** March 23, 2026  

Benchmark instances for two-sided assembly line balancing with collaborative robots to minimize cycle time.

## Overview

This repository contains benchmark instances for the Two-sided Assembly Line Balancing Problem with Collaborative Robots (Cobot-TALBP2). The objective is to minimize cycle time while considering human-robot collaboration in two-sided assembly lines.

## Repository Structure

```
Instances_Cobot_Two_sided_ALBP2/
├── Singletype_Cobot_TALBP2/    # Single worker + single robot type instances
├── README.md                    # This file
└── LICENSE                      # License information
```

## Dataset Details

### Singletype_Cobot_TALBP2
This directory contains instances with a **single worker** and a **single type of collaborative robot**. Each instance file follows the naming convention:

`P{tasks}_{stations}_{instance}.txt`

Where:
- **tasks**: Number of tasks in the assembly line (9, 12, 16, 24, 65, 148, 205)
- **stations**: Number of stations (2-14 depending on problem size)
- **instance**: Instance variant (0-4)

#### Instance Groups:
- **Small-scale**: P9, P12, P16, P24 (2-5 stations, 5 variants each)
- **Medium-scale**: P65 (4-8 stations, 5 variants each)
- **Large-scale**: P148 (4-12 stations, 5 variants each)
- **Very large-scale**: P205 (4-14 stations, 5 variants each)

Total: **165 instance files** covering various problem sizes and configurations.

## File Format

Each instance file contains:
- Task information and processing times
- Precedence constraints
- Direction constraints (left, right, or either side)
- Human-robot collaboration parameters
- Cycle time bounds

## Usage

These instances can be used to:
- Test and validate optimization algorithms for Cobot-TALBP2
- Benchmark different solution approaches
- Compare cycle time minimization strategies
- Evaluate human-robot collaboration efficiency

## Citation

If you use these instances in your research, please cite the relevant publications.

## License

See LICENSE file for terms of use.

## Contact

For questions or contributions, please visit the GitHub repository.
