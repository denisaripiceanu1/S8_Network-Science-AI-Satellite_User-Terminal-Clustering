# S8 - Network Science & AI - Satellite User Terminal Clustering

This project focused on optimizing communication resources for Low Earth Orbit (LEO) satellite constellations during my 8th semester at ENSEEIHT. The main objective was to group ground user terminals into the minimum possible number of clusters while strictly respecting a maximum cluster radius of 45 km and a variable capacity limit of 1, 2, or 4 Gbps.   

To solve this NP-hard spatial optimization problem, we processed large datasets and compared CIR (Committed Information Rate) and PIR (Peak Information Rate) demand models. We implemented several algorithms from scratch in Python, including an optimized P-center approach, a Gravity Mean-Shift heuristic, and an advanced Split-Merge algorithm. Our custom Split-Merge approach utilized KD-Trees via SciPy for fast spatial queries, Haversine distance calculations, and a Boyle-Dykstra projection method to dynamically resolve capacity constraints and reassign terminals from overloaded clusters.   

I found it incredibly rewarding to design scalable heuristics that bridge mathematical optimization with real-world telecommunication challenges. Developing robust algorithms to handle tens of thousands of virtual terminals significantly strengthened my skills in Python programming, algorithmic efficiency, and spatial data analysis.
