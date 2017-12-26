# Open Universal Systems Manager

![alt text](https://github.com/openusm/openusm/blob/master/images/openusm_logo.png)


A modern approach to Server Management solution integrated with monitoring & logging pipeline using Docker & Microservices.

# Highlights

- USM is bundled as Docker Images which is lightweight, stand-alone, executable package of a piece of software that includes everything needed to run it: code, runtime, system tools, system libraries, settings. Hence, no need of host dependencies packages
- USM is an out-of-band system management solution purely based on Redfish API Interface.
- It is a platform agnostic solution(can be run from laptop, server or cloud) and works on any of Linux or Windows platform with Docker Engine running on top of it.

# Value Proposition

- USM architecture can scale both vertically & horizontally
- USM architecture can be easy integrated and extended with 3rd party open source tools.(example - the choice of InfluxDB instead of Prometheus as monitoring tool, using 3rd Party logging tool instead of ELK stack etc.)
- USM bundle can be built and customized by the customer based on their own needs and holds a plug-and-play components and functionalities.

# Architecture

![alt text](https://github.com/openusm/openusm/blob/master/images/how_openusm_works.png)

# How openUSM works?

![alt text](https://github.com/openusm/openusm/blob/master/images/openusm_architecture.png)


# Getting Started with OpenUSM

OpenUSM is a suite of tools and utilities which configures and manage the lifecycle of system management. OpenUSM has a capability to perform the following functions:

[BIOS Token Change](docs/bios-token.md) <br>
[Firmware Update](docs/firmware.md)<br>
[Pushing iDRAC Logs to ELK Stack(docs/idrac2elk.md)


# Documentation

Check out our guides for documentation, deployment guides and tutorials.

# Roadmap ahead

OpenUSM is written in Python - contributions are welcomed whether that means providing feedback, testing existing and new feature or hacking on the source.

# How do I become a contributor?

We invite new contributors to contribute towards this project repository. We would also ask you to propose any improvements or contributions for future releases.
