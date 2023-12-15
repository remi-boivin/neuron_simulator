# Neuron Simulator - Leaky Integrate-and-Fire Model

This repository contains a Python-based neuron simulator implementing the Leaky Integrate-and-Fire (LIF) model. It's designed to explore various behaviors of a neuron in response to different input currents.

## Overview

The LIF model is a simple yet powerful tool for understanding the basic principles of neuronal dynamics. This simulator allows for the visualization and analysis of different neuronal responses under varying conditions.

## Features

- [ ] Simulation of resting state of neurons.
- [ ] Observation of subthreshold fluctuations in membrane potential.
- [ ] Threshold triggering and action potential generation.
- [ ] Regular spiking behavior under constant input current.
- [ ] Oscillatory behavior with sinusoidal input currents.
- [ ] Response to random noise, simulating realistic synaptic inputs.
- [ ] Analysis of neuron response to short pulses of current.

## Getting Started

To get started with this simulator:

1. Clone the repository: `git clone https://github.com/remi-boivin/neuron_simulator.git`
2. Navigate to the repository folder: `cd neuron-simulator`
3. Install required dependencies: `pip install -r requirements.txt`
4. Run the simulation: `python lif_neuron_simulator.py`

## Usage

Modify the input parameters in `lif_neuron_simulator.py` to simulate different neuronal behaviors:

- For resting state, set `I = 0`.
- For subthreshold fluctuations, use a small value of `I`.
- Increase `I` above a certain threshold to observe regular spiking.
- Apply a sinusoidal input for oscillatory behavior.
- Use random values for `I` to simulate random synaptic inputs.

## Contributing

Contributions to improve the simulator or add new features are welcome. Please feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Special thanks to [Contributor's Name] for [specific contribution].
- Inspired by foundational work in computational neuroscience and neuronal modeling.
