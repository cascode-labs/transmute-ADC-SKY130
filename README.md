# Transmute 10 bit ADC 

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

Transmute is a 10 bit open source hardware (OSH) analog-to-digital converter (ADC) system.  It will initially target the SKY130 process and the Google Efabless MPW progrm..

## Block diagram

The design will consist of a 10 bit SAR ADC which streams it's output data through the Caravel SPI interface.  There will also need a voltage regulator and bandgap voltage reference to support the ADC.

| :exclamation: # This project is still early in development |
|------------------------------------------------------------|

## Methodology
The design will be built using a (largely) programmatic design approach and open-source tools.

| :exclamation: # Caravel User Project Notes            |
|-------------------------------------------------------|

## Please fill in your project documentation in this README.md file 

Refer to [README](docs/source/index.rst#section-quickstart) for a quickstart of how to use caravel_user_project

Refer to [README](docs/source/index.rst) for this sample project documentation. 
