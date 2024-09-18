# Benchmarking Model Predictive Control and Reinforcement Learning Based Control for Legged Robot Locomotion

This repository consists of the data and plots used in the submitted paper to Frontiers in Robotics and AI.

![RL Simulation](Other-Docs/RL.mp4)

## Task and Data Files

| Task                                   | Data Files          |
|----------------------------------------|---------------------|
| Standardization                        | [rl data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/1.%20Standardization%20and%20Perturbation/1.Standardization/RL_standardization.csv), [mpc data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/1.%20Standardization%20and%20Perturbation/1.Standardization/MPC_standardization1.csv) |
| Perturb in positive x axis             | [rl data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/1.%20Standardization%20and%20Perturbation/2.%20Perturb%20in%20positive%20x%20axis/rl%20data.csv), [mpc data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/1.%20Standardization%20and%20Perturbation/2.%20Perturb%20in%20positive%20x%20axis/mpc%20data.csv) |
| Perturb in negative x axis             | [rl data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/1.%20Standardization%20and%20Perturbation/3.%20Perturb%20in%20negative%20x%20axis/rl%20data.csv), [mpc data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/1.%20Standardization%20and%20Perturbation/3.%20Perturb%20in%20negative%20x%20axis/mpc%20data.csv) |
| Perturb in negative y axis             | [rl data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/1.%20Standardization%20and%20Perturbation/4.%20Perturb%20in%20negative%20y%20axis/rl%20data.csv), [mpc data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/1.%20Standardization%20and%20Perturbation/4.%20Perturb%20in%20negative%20y%20axis/mpc%20data.csv) |
| Generalization for slippery terrain    | [rl data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/2.%20Generalization/slippery%20terrain/slippery_terrain_data.csv) |
| Generalization for uneven terrain      | [rl data](https://github.com/RoLACLab/mpc-and-rl-benchmark/blob/06af2fd530b7c5fd58f7b27535bce1186b592310/2.%20Generalization/uneven%20terrain/uneven_terrain_data.csv) |

Data specification: [time, x, y, z, vx, vy, vz, ctrl1, ctrl2, ctrl3, external force]
where, 
- x, y and z stands for Center of mass position in x, y and z axis
- vx, vy and vz stands for Center of mass velocity in x, y and z axis
- ctrl1, ctrl2, ctrl3 stands for control in hip abduction, hip flexion and knee flexion

## Plots
### Standardization and Perturbation
<h1>
  <a href="#"><img src="1. Standardization and Perturbation/Standardization and Perturbation.jpg" width="80%"></a>
</h1>

### Generalization
<h1>
  <a href="#"><img src="2. Generalization/Generalization_combo.jpg" width="80%"></a>
</h1>

Here are some figures to provide some additional information.
### Standardization
<h1>
  <a href="#"><img src="1. Standardization and Perturbation/1.Standardization/std.png" width="50%"></a>
</h1>

### Perturb in positive x axis
<h1>
  <a href="#"><img src="1. Standardization and Perturbation/2. Perturb in positive x axis/perturbation in pocitive x axis.png" width="50%"></a>
</h1>

### Perturb in negative x axis
<h1>
  <a href="#"><img src="1. Standardization and Perturbation/3. Perturb in negative x axis/perturbation in negative x axis.png" width="50%"></a>
</h1>

### Perturb in negative y axis
<h1>
  <a href="#"><img src="1. Standardization and Perturbation/4. Perturb in negative y axis/perturbation in negative y axis.png" width="50%"></a>
</h1>

### RL Generalization for slippery terrain
<h1>
  <a href="#"><img src="2. Generalization/slippery terrain/slippery terrain.png" width="50%"></a>
</h1>

### RL Generalization for uneven terrain
<h1>
  <a href="#"><img src="2. Generalization/uneven terrain/uneven terrain.png" width="50%"></a>
</h1>
