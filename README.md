# Elevate CLI

> An elevator simulation command-line interface based on the `elevate-lib` Rust package.

![elevate-cli display](doc/assets/elevate-cli.gif)

## About

The elevate CLI uses the elevate-lib package to model people arriving and leaving to and from the building, and to measure the elevator's energy usage, as well as the average wait time among the people throughout the building.  It offers utilities for visualizing how certain elevator control logic performs under varying conditions.

## Usage

```
Usage: elevate-cli.exe [OPTIONS]

Options:
      --floors <FLOORS>
          Number of floors in the building

      --elevators <ELEVATORS>
          Number of elevators in the building

      --expected-arrivals <ARRIVALS>
          Expected number of arrivals per time step

  -h, --help
          Print help (see a summary with '-h')

  -V, --version
          Print version
```