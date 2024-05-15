"# SolvingLargeScaleRoute_Genetic_Algorithm" 
Source: Route Optimization - A Real World Scenario: https://www.kaggle.com/datasets/mexwell/large
scale-route-optimization  
The example demonstrated in this dataset is inspired by a real-world optimization scenario. The customer is a 
manufacturing company. They have warehouses in different locations. When they receive orders from their 
clients, a planner needs to plan the item-to-truck assignment for order delivery. The planner also needs to 
decide the route of each delivery truck, namely, the sequence of the stops to deliver orders to different 
destinations. A delivery assignment has its associated cost determined by the type of the assigned delivery truck 
and the corresponding travelling distance. The optimization objective here is to minimize the overall delivery 
cost. 
This is a variant of the vehicle routing problem (VRP). The constraints modelled are: - There are different types of trucks from which we can choose. A truck has a capacity limit on both area and 
weight. (We assume that there is no limit on the number of trucks for each type) 
- An item is only available by a specific time. A truck can start only when all items assigned to it are available.
- - The available time difference between the earliest and last available items in the same truck should be less 
than a user-defined limit (e.g., 4 hours). - All items need to be delivered to their destinations before their deadlines. - Depending on their properties, some products can be put in the same truck, but some cannot. - A truck can have N stops at most, where N is a user-defined number. - A truck must stay at each stop for M hours to unload the items, where M is a user-defined number. Each stop 
will incur a fixed cost in addition to the delivery cost.
