## Introduction
This project provides basic Docker configurations compatible with the libraries developed at LabSonar/LPS.
All docker are available at [docker hub](https://hub.docker.com/u/labsonar)

## Authors
- **Developer**: [Fábio Oliveira](https://github.com/obs-fabio)
- **Advisor**: [Natanael Junior](https://github.com/natmourajr/natmourajr)

## Usage
This repository includes the following Docker configurations:

- **processing**: Python/CUDA environment configured for simple libraries
- **pytorch**: processing Docker + PyTorch configuration for machine learning libraries
- **synthesis**: PyTorch Docker + OASES configuration for acoustical environment modeling

```bash
./run {processing | pytorch | synthesis | all} [local_dir:docker_dir] [port]
```

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA) license. You are free to use, modify, and distribute the code for non-commercial purposes, with the condition that you provide attribution to the authors and distribute any derivative works under the same license. For more details, please refer to the license file (LICENSE.md) included in this repository.
