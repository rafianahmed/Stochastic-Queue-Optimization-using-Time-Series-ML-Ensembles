Service Optimization: Restaurant Queueing System

This project focuses on optimizing customer service in a restaurant environment by minimizing queue waiting times and improving server utilization. It compares a naïve baseline approach with optimized strategies through simulation.

Problem Overview

Restaurants often face congestion during peak hours. Customers may experience long waiting times if queues are not efficiently managed. This project models the system as a queueing problem and applies optimization to:

Reduce average waiting time

Improve server utilization

Ensure fairness in service distribution

Handle congestion during peak loads

Approaches Implemented

Naïve Baseline

First-Come-First-Serve or simple round-robin scheduling.

Implemented in naive.ipynb.

Improved Optimization Model

Incorporates dynamic scheduling and queue balancing.

Assigns customers based on arrival rates and service availability.

Implemented in improved.ipynb.

Time-based Simulation

time_simulation.ipynb and time_simulation_ver2.ipynb simulate the flow of customers, track waiting times, and compare performance of baseline vs optimized models.

Repository Structure

naive.ipynb – Baseline model

improved.ipynb – Optimized queue management

time_simulation.ipynb – Time-step simulation

time_simulation_ver2.ipynb – Alternative simulation model

Project Presentation.mp4 – Demo presentation

README.md – Documentation

How to Run

Requirements:

Python 3.x

Libraries: NumPy, Pandas, Matplotlib, Jupyter

Steps:

Clone repository

Open notebooks in Jupyter

Run and compare results

Results

Optimized model reduced average waiting time compared to the naïve baseline.

Balanced load across servers and minimized congestion under peak demand.

Simulation results show improved throughput and fairness.

Skills Demonstrated

Queueing Theory and Simulation

Optimization and Scheduling Algorithms

Python (NumPy, Pandas, Matplotlib)

Data Visualization and Analysis
