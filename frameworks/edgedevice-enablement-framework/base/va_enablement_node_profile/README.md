# VA Enablement Node Profile

## Overview

The `va_enablement_node_profile.sh` script provides node profiling capabilities for the VA (Video Analytics) enablement framework. This script is designed to Install the required drivers, tools and libraries for edge devices to develop and run VA workloads.

## Usage

```bash
./va_enablement_node_profile.sh [OPTIONS]
```

## Features

- Installs GPU, NPU drivers
- Observability stack with xpu-smi, grafana and proemetheus
- VA library installation on baremetal - Intel's openvino, opencv, dlstreamer and ffmpeg
- Hardware capability assessment

## Requirements

- Ubuntu-based edge device (Currently supports Ubuntu 24.04.3)
- Bash shell environment
- Appropriate system permissions for hardware monitoring

## Configuration

The script can be configured through environment variables or command-line parameters. Refer to the script's help output for detailed configuration options.

## Output

The profiling logs are typically saved in output.log file for further analysis and integration with the VA enablement framework.

## Support

For issues and questions related to this profiling tool, please refer to the main project documentation or contact the development team.