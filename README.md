# 🧬 Evacuation Route Determination For High Rise Buildings Using Non-dominated Sorting Genetic Algorithm II (NSGA-II) 🧬
This project was developed as part of the undergraduate thesis at the [Department of Mathematics, Universitas Pendidikan Indonesia (UPI)](https://fpmipa.upi.edu/). If you want to know more about this project, you can visit this link [Repository UPI](http://repository.upi.edu/123636/).

## 🧭Background
Evacuation routes are an important aspect of the evacuation process. In emergency situations, determining efficient evacuation routes is crucial to minimize casualities and ensure quick and organized movement. This research is to determine the optimal evacuation route in high-rise building, which is an evacuation route that minimizes the total evacuation time and minimizes congestion during the evacuation process by considering the length of the road, road capacity, number of evacuees, and distribution of evacuees in the building. However, route planning in such environments is complicated due to multiple conflicting objectives.

This project proposes a multiobjective optimization approach using the Non-dominated Sorting Genetic Algorithm II (NSGA-II) to generate optimal evacuation routes in high-rise buildings. By simulating multiple constraints, the model performed iteratively until the maximum generation is reached to obtain the Pareto optimum, providing building managers with adaptable and effective evacuation strategies.

## 🏛️Dataset
The dataset used in this research is based on the floor plan and structural layout of the [Postgraduate Studies Building at Universitas Pendidikan Indonesia (UPI)](https://www.upi.edu/faculty-and-school/detail/14/school-of-postgraduates-upi), a academic building located in Bandung, Indonesia.

Dataset include:
- Floor by floor spatial layout (rooms, corridors, stairs)
- Distance between the spatial layout
- Maximum capacity of each spatial layout per floor
- Initial occupant distribution per room or floor

Due to privacy and institutional policy, the raw building layout may be abstracted into a graph based representation in the public version of this repository.

## 🧠Project Design Thinking
This section outlines the systematic thinking behind the project, from problem formulation to algorithmic implementation.

### 1. 📋Problem Formulation
The main goal is to determine multiple efficient evacuation routes in high-rise building that minimize total evacuation time and minimize congestion during the evacuation process. Since planning inherently involves trade offs between speed and safety, a multiobjective optimization approach is applied.

Two conflicting objectives:
- Minimize total travel time of evacuees to the safe zone
- Minimize route congestion during the evacuation process

### 2. 🔍Assumption Setting
To simplify the complexity of the real-world evacuation dynamics, the following assumptions are made:
- The building layout is static and represented as a directed graph
- The direction of the edge is assumed to be always towards the nearest node.
- All evacuees begin evacuating at the same time.
- The maximum speed of the evacuees is assumed to be the same, thus attributes such as age and gender are disregarded.
- Each evacuees is well acquainted with each component and layout of the building.

### 3. 📐Mathematical Modeling


## 👣Project Steps

### a. Building Representation as a network

### b. Multiobjective Optimization Using NSGA-II

## 📊Result & Insight


## 🚀Future Work
Although the proposed system shows promising results, several limitations remain and open up opportunities for further development.

Future Enhancements:
- Dynamic Evacuation Modeling: Incorporate time-varying hazard maps (e.g., fire spread simulation).
- Behavioral Simulation: Integrate agent-based modeling to reflect realistic human responses.

## 🙏Acknowledgements
Special thanks to:
- Thesis Advisor, for guidance throughout the research.
- UPI Postgraduate School: For providing access to building layout data.
- All contributors and peers who supported during the development of this project.

## References
All references for this project can you see in this link [References]
