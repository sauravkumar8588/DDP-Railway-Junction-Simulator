# Siwan Junction Mixed-Traffic Simulation & Visualization Tool

This repository contains code, simulations, and visualizations for modeling Siwan Junction railway operations. The tool serves as a decision support system (DSS) to optimize throughput by simulating mixed-traffic scenarios, analyzing junction capacity, and employing reinforcement learning for enhanced scheduling and layout improvements.

## Contents

- **/simulation/**: Python scripts and configuration files for train schedule and junction layout modeling
- **/visualization/**: Tools and notebooks for interactive train movement charts (Matplotlib, Plotly)
- **/rl_models/**: Reinforcement learning code to analyze schedule/Layout changes (RLlib, Stable Baselines)
- **/data/**: Sample train schedules, traffic mixes (passenger/freight), and simulation logs
- **/reports/**: Project summary, technical documentation, findings from Siwan Junction case study
- **README.md**: Repository overview and usage instructions

## Project Goals

- Formulate capacity metric for Siwan Junction under mixed passenger and freight traffic
- Simulate real-world train movements; visualize flows, dwell times, and conflicts
- Apply reinforcement learning to help alter schedules or tweak junction layouts for boosted throughput
- Deliver actionable insights for railway operators and planners via decision support visualizations

## Usage

1. **Clone the repository:**
    ```
    git clone https://github.com/[your-username]/siwan-junction-dss.git
    cd siwan-junction-dss
    ```
2. **Install dependencies:**
    ```
    pip install -r requirements.txt
    ```
3. **Run baseline simulation:**
    ```
    python simulation/run_siwan.py
    ```
4. **Visualize train movements:**
    - View interactive charts in `/visualization/`
    - Example: `python visualization/plot_schedule.py`
5. **Experiment with RL-based optimization:**
    ```
    python rl_models/optimize_schedule.py
    ```



For issues, suggestions, or collaboration, open an issue or contact the author.
