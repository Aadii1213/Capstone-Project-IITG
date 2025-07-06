# Capstone-Project-IITG
Title: Dynamic Pricing System for Urban Parking Lots Project Type: Capstone Project – Summer Analytics 2025 Organized by: Consulting &amp; Analytics Club, IIT Guwahati Powered by: Pathway


Problem Statement:-
Urban parking spaces are scarce and often inefficiently used due to static pricing models. During peak hours, lots are overcrowded, while during off-peak times, they are underutilized.
This project addresses this problem by developing a real-time dynamic pricing engine using data from 14 parking locations collected over a period of 73 days.

Objective :-
My objective was to build an intelligent pricing system that could adjust parking prices in real time using various demand factors. I also aimed to make these price changes smooth, explainable, and operationally effective.

What I Did 
- I processed and analyzed time-series data from all 14 parking lots using Pandas and NumPy.
- I implemented three models:
- Model 1: A simple baseline model that increased price linearly with occupancy.
- Model 2: A demand-based pricing model using a custom mathematical function based on queue length, traffic, special days, and vehicle types.
- Model 3: A competitive pricing model that considered the distance and pricing of nearby lots, using the Haversine formula.
- I developed real-time data streaming using Pathway, simulating live data using replay_csv() at a controlled input rate.
- I used daily tumbling windows to compute dynamic prices over time, reflecting changes in occupancy trends.
- I visualized pricing behaviors and trends using Bokeh and Panel for an interactive real-time dashboard.

Tools and Technologies Used:-
Python, Pandas, NumPy
Pathway (for real-time stream processing)
Bokeh and Panel (for visualizations)
Matplotlib (for static comparisons)
Google Colab (for end-to-end development)

Key Outcomes:-
- I developed three progressively advanced pricing models for intelligent urban parking management.

- I designed and deployed a real-time pipeline to process, predict, and visualize dynamic pricing.

- I ensured the models produced prices that were realistic, bounded, and interpretable.

- I delivered an interactive dashboard showing daily and real-time pricing evolution for each parking lot.



