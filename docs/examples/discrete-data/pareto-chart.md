---
layout: default
title: Pareto Chart
nav_order: 2
has_children: false
parent: Discrete Data
grand_parent: Examples
has_toc: false
---
# Pareto Chart

```cpp
pareto(y);
```


See result

[![e../../../examples/discrete_data/pareto/pareto_1.cppareto_1.svg)](examples/discrete_data/pareto/pareto_1.cpp)

More examples:
    
[![e...../../../examples/discrete_data/pareto/pareto_4.cppareto_4_thumb.pngples/discrete_data/pareto/pareto_2.cpp)  [![example_pareto_3](docs/examples/discrete_data/pareto/pareto_3_thumb.png)](examples/discrete_data/pareto/pareto_3.cpp) [![example_pareto_4](docs/examples/discrete_data/pareto/pareto_4_thumb.png)](examples/discrete_data/pareto/pareto_4.cpp)


Pareto Charts are a type of chart that uses both $y$ axes. The $y_1$ axis is used to represent bars with the data values in descending order. The $y_2$ axis is used to represent the cumulative distribution function of the data in the $y_1$ axis. By default, a Pareto Chart includes up to 10 items or as many items as needed to represent 95% of the cumulative distribution.

If you need Pareto *fronts* rather than Pareto *charts*, we refer to [Scatter Plots](../data-distribution/scatter-../data-distribution/plot-matrix.md two-dimens../data-distribution/parallel-coordinates.mdatrices](#plot-matrix) for../data-distribution.md fronts, or [Parallel Coordinate Plots](#parallel-coordinates) for many-objective fronts. These plot subcategories are described in Section [Data Distribution](#data-distribution). If you also need a tool to calculate these fronts efficiently, we refer to the [Pareto Front Library](https://github.com/alandefreitas/pareto-front).


