# Optimal placement to minimize the time it takes for a pallet rack machine to pick up items for different orders.

A machine that goes through a pallet rack to pick up items for an order can be seen as a traveling salesman problem.
Which path should the machine take to minimize the distance?
But we need also to take into an account that there could be several types of orders containing a different set of items, and that we can choose the placement of the items in the pallet rack.
We get a bilevel optimization problem. First must choose an item placement that in turn optimizes the length the machine has to travel to be able to safices all the orders.
