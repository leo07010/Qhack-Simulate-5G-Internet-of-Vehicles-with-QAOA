# Qhack-QAOA Optimized Maxcut Problem Used in Device Tracking — Examples in Vehicle Connection and 5G Area
Introduction slides are in the repo too! Please download it to obtain futhuer information.
[![Build Status](https://i.ibb.co/sCpw28h/Screen-Shot-2020-09-10-at-1-38-50-AM.png)](https://i.ibb.co/sCpw28h/Screen-Shot-2020-09-10-at-1-38-50-AM.png)
## Usage
1. Please install prerequirements: python 3.X
2. Create a new working environment (optional)
3. type following commands to setup the simulation:
```
git clone https://github.com/leo07010/Qhack-Simulate-5G-Internet-of-Vehicles-with-QAOA
cd Application-of-quantum-optimization
pip install -r requirements.txt
python vis.py
```
## Description
Our task is composed of 3 small tasks: sensor allocation, vehicle positioning and data synchronization.

1.	Sensor distribution: Use MAXCUT to allocate sensors, and achieve an approximate solution to the MAXCUT problem through the quantum approximate optimization algorithm (QAOA).
2.	Vehicle location: Use the sensors that have been allocated (subtask 1) to locate the vehicle. This method is equivalent to the minimization of the quadratic function.
3.	Data synchronization: Define the route from the server to many locations and back to the server. We use the QAOQ algorithm to obtain its Ising Hamiltonian eigenstates.

##Video Link
https://drive.google.com/drive/u/0/folders/1NbkzeKB5iUIsAeYxUSPQJf8GZsLx1eOJ
