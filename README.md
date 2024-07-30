# Revolutionizing Delivery Services, Simulation
## Project Overview:
The We-Doo project focuses on validating an innovative business concept to transform delivery services in commuter townships. The primary goal was to develop a comprehensive simulation framework to model typical evening delivery runs for a small township. This framework aims to assist in planning and implementing We-Doo services in new townships and selecting the most suitable cargo bike for trial runs.

## Key Objectives:

### Simulation Development: Created a simulation framework to model delivery operations, incorporating synthetic data to represent real-world demands.
- Cargo Bike Analysis: Assessed various cargo bike ranges (30km, 35km, 40km, 45km) to determine the most efficient option for handling different levels of delivery demand.
- Parcel Receipt Rates: Investigated different average parcel receipt rates (p), ranging from 0.1 to 0.4, to understand their impact on delivery operations.
- Performance Metrics: Evaluated the delivery system's performance based on key metrics such as delivery delays, daily working time, tour length, and left-over parcels.

## Methodology:
### Data Generation
Developed a generateData() function to create synthetic data sets, ensuring reproducibility with specific seed values. This data included detailed map layouts, waypoints for delivery stops, and customer information.
### Simulation Execution
Ran multiple simulations using the generatorProcess function, incorporating various values for parcel receipt rates (p) and cargo bike ranges (r). The simulations spanned multiple days to provide a robust analysis of delivery operations.
### Analysis and Insights
Analyzed simulation results to determine the optimal cargo bike range and delivery strategies. Key findings include the 40km bike range offering a good balance of delivery efficiency and minimizing delays.

## Results and Future Directions:
The simulation results highlighted the strengths and weaknesses of different bike ranges under varying delivery demands. The project provides actionable insights for We-Doo to optimize their delivery services and make informed decisions about expanding their operations.
