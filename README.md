# Circuit Bench

A six-instrument calculator panel for electrical engineering fundamentals, built as a single self-contained web page — no build step, no dependencies, no server.

**[Live demo](https://omarterressi.github.io/circuit-bench/)** 

## Instruments

- **Ohm's Law & Power** — solve for voltage, current, or resistance from the other two, with power derived automatically
- **Voltage Divider** — output voltage, branch current, and per-resistor dissipation
- **Resistor Network** — total any list of resistors wired in series or parallel
- **Reactance & Timing** — capacitive/inductive reactance, LC resonant frequency, RC time constant
- **Three-Phase Power** — real, apparent, and reactive power for a balanced load, star or delta
- **Resistor Color Code** — decode 4-band or 5-band resistor markings into a value, tolerance, and range

## Why

Built to consolidate core EE fundamentals (Ohm's law, reactance, three-phase power, resistor coding) into a single practical tool, and as a front-end exercise in unit handling, live calculation, and theming without a framework.

## Tech

Plain HTML, CSS, and JavaScript — no build tools, no npm dependencies. Supports light and dark themes (auto-detects system preference, with a manual override). All calculations run locally in the browser.

## Running it locally

Just open `index.html` in any modern browser. No installation required.

## Author

Omar Terressi

## License

MIT
