# truss-data
This repository includes the data corresponding to the load cases and topology of the truss sizing optimization instances.

Here, the index sets of nodes and bars start from zero.

data_constraints: each line is an index of fixed nodes.
data_elems: each line includes indices of nodes connected to a bar (the first line is for bar 0).
data_force: each line includes the coordinates of a force exerted on a given node (the first line is for node 0).
data_nodes: each line includes the coordinates of a node w.r.t. the origin (the first line is for node 0).
R: each line is a row of matrix the topology matrix R (the first line is for the first row of matrix R).
