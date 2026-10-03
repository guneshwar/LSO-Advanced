Genuine CANAD-R benchmark instance: r10.1

Source
------
Converted directly from the uploaded official R.tgz archive.

Dimensions
----------
Nodes       : 20
Arcs        : 120
Commodities : 40

CANAD setting
-------------
Fixed-cost setting : 1
Capacity setting   : 1

Files
-----
arcs.csv
    Exact format used by the DFCND notebooks:
    arc,tail,head,capacity,fixed_cost,flow_cost

    flow_cost is deliberately set to 0.0 to reproduce the
    zero-flow-cost setting used for the polar-cut experiments.

arcs_native_flow_cost.csv
    Same instance, but preserves the native CANAD variable cost
    in the flow_cost column.

demands.csv
    Exact format used by the DFCND notebooks:
    origin,destination,demand

No synthetic data were introduced in the conversion.
