# Caravel User Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

This project is an attempt to implement the [NEORV32](https://github.com/stnolting/neorv32) project onto the google caravel project using skywater 130.

This NEORV32 has its wishbone interface hooked up to the caravels wishbone interface. It also has a UART exposed on GPIO 5 (RX) and 6 (TX). This version of the chip runs at 5 MHz and has a IRAM of 1K and DRAM of 2K.
