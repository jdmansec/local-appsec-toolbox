# local-appsec-toolbox

A local-only, multi-scanner AppSec command-line tool for security engineering practice and safe local scanning workflows.

## Overview

**local-appsec-toolbox** is a production-grade CLI wrapper that orchestrates multiple open-source security tools using Podman for isolation. The tool supports scanning codebases in different modes (SAST, IaC, Container, Dependency, DAST, All) and is implemented with strict adherence to best practices across Python, security engineering, containerization, and DevOps.

## Features

- **Multiple Scan Modes**: SAST, IaC, Container, Dependency, DAST, and All
- **Containerized Execution**: All scanners run in isolated Podman containers
- **Security Hardening**: Rootless containers, read-only mounts, capability dropping
- **Unified Interface**: Single CLI for multiple security tools
- **Local-Only**: No cloud dependencies, runs entirely on your local machine

## Supported Tools

- **Semgrep**: Static application security testing (SAST)
- **Checkov**: Infrastructure as Code (IaC) security scanning
- **Gitleaks**: Secret detection
- **Trivy**: Container vulnerability scanning
- **Syft**: Software Bill of Materials (SBOM) generation
- **OWASP ZAP**: Dynamic application security testing (DAST)

## Prerequisites

- Python 3.9+
- Poetry (Python package manager)
- Podman (container runtime)
- Git

## Installation

Coming soon - binary releases and Poetry-based installation instructions.

## Usage

Coming soon - CLI usage examples and configuration guide.

## Development

This project follows professional software engineering practices with comprehensive testing, linting, and documentation.

For development setup and contribution guidelines, see the sections below.

## License

TBD

## Project Status

🚧 **Under Active Development** 🚧

This project is currently being built following a spec-driven development methodology with comprehensive requirements, design, and implementation planning.
