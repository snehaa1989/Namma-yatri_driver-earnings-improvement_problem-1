# Namma yatri open mobility challenge by Juspay

Problem Statement: Most drivers have a daily earning model and must work long hours to make ends meet. Hence, lack of stable earnings is widespread and affects the livelihoods of many drivers and their families. 

Common problems:
● Uncertain demand
● Lack of complete visibility of demand
● Inefficient routing or planning
● High operational costs
● Earnings not in sync with effort or operating costs
● Debt at high interest
● Health issues impacting earnings


Solution Scope & Deliverables: The ideas can be around new technology, business models, policies, products or service offerings. 

Few themes of ideas:
1. Better or alternate utilization of the vehicle & drivers' time (Esp. during off-peak time)
2. Improve earnings through digital enablement & technology
3. Reduce costs (operational, maintenance, interest costs etc.)
4. Ecosystem / Policy initiatives to improve earnings


## Dataset

The datasets are custom, which can be found in ```data``` folder as csv file. Here are the informaions:

- 24 famous areas of Bangalore city
- distance
- auto travel time
- position

## Prerequisites

- python
- pulp
- matplotlib
- seaborn
- numpy
- pandas

## Usage

Run ```solution.ipynb``` to plot the result. You can set varaible K to indicate numbers of auto drivers. Note that K greater than 4 might take hours.


Once **K (num of auto drivers)** is larger, it is better not to solve it with linear programming. We should use meta heuristic methods instead, though the solution might not be optimal, yet a lot faster.

## next steps : Django or flask integration
## Hope you like it!
