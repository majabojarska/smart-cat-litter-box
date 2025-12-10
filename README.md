# smart-cat-litter-box

[![Status](https://github.com/majabojarska/smart-cat-litter-box/actions/workflows/status.yaml/badge.svg)](https://github.com/majabojarska/smart-cat-litter-box/actions/workflows/status.yaml)

Cat litter box platform with weight analysis ⚖️🐈

This project is basically a glorified smart weight scale, geared towards cat health analysis.

## Bill of Materials

- Electronics:
  - 4x 50kg load cell (or less).
  - HX711 load cell amplifier module.
  - ESP8266, ESP32, or other [ESPHome-supported board](https://esphome.io/components/#supported-microcontrollers)
  - Misc. electronics:
    - Universal PCB.
    - 2.54mm pin headers and sockets, DuPont connectors.
    - Some jumper wires to route connections.
  - 4x [load cell holder](https://www.printables.com/model/157473-load-cell-holder) – 3D printed.
- Platform – feel free to improvise here.
  - Appropriately sized piece of flat and stiff material, like a wooden plank, old shelves, etc. Needs to be big enough to accomodate our cat's litter box on top.
  - Wooden slats to raise the platform slightly above ground, in order to make room for housing the electronics underneath.

Alternatively, instead of using sockets and connectors, this project can be just soldered together and glued to the platform's underside. The choice of final effect and durability is up to you.

## Credits & License

The ESPHome sources of this project and wiring diagrams are based on [markusressel/ESPHome-Smart-Scale (rev a5c398b](https://github.com/markusressel/ESPHome-Smart-Scale/blob/a5c398be2e12997aeb6e18378eb6f32f34531625/). That revision was published under the [CC0-1.0 license](https://github.com/markusressel/ESPHome-Smart-Scale/blob/a5c398be2e12997aeb6e18378eb6f32f34531625/LICENSE).

Given that the CC0-1.0 license:

- wasn't really designed for software, nor is it recognized by the [Open Source Initiative](https://opensource.org/)
- it effectively placed the original work under the public domain;

I'm releasing this derivative work under the [MIT license](https://opensource.org/license/mit).
