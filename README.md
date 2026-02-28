 Computer Networks Simulation Project (CNI)

 Overview
This project is a Python-based network simulation developed as part of the Computer Networks (CNI) coursework.  
The goal of the project is to understand how a network behaves when the traffic load changes and how different performance metrics are affected.

The simulation was implemented and tested using Google Colab, which made it easy to run experiments and visualize results.

Objectives
- Simulate packet transmission in a network environment  
- Generate different traffic workloads  
- Measure important network performance metrics  
- Analyze and visualize results using graphs  

Tools and Technologies
- Python  
- Google Colab  
- Jupyter Notebook (.ipynb)  
- NumPy and Matplotlib for analysis and plotting  

Project Components
Workload Generator 
Creates different traffic patterns by controlling packet arrival rates.

Simulation Loop
Models packet transmission, basic queuing, and processing inside the network.

Metrics Collection  
Collects and computes key metrics such as:
- Throughput  
- Latency / Delay  
- Packet loss  

Visualization
Graphs are generated to clearly show how network performance changes with varying traffic loads.


 How to Run
1. Open the notebook file in Google Colab  
2. Run all cells in sequence  
3. Observe the output graphs and printed metrics  

Results
The results highlight how increasing traffic impacts network delay, throughput, and packet loss.  
The generated graphs help in understanding congestion behavior and overall network performance.

 Limitations
- The network model is simplified  
- Real-world traffic traces are not used  
- The simulation does not run in real time  

Future Scope
- Use real network traffic datasets  
- Add more advanced queueing models  
- Automate experiment configuration  
- Build a simple interface for parameter tuning  

