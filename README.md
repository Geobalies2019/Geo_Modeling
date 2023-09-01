# Geo_Modeling
Documents models in the environmental sciences
Credits: The models contained within this repository originate from the book titled "A Guide to Modeling with MATLAB."
We will be modeling using process-oriented and deterministic approach.

The core of conceptual model lies in a proportionality relationship, which can be expressed through a differential equation. In this context, the conceptual model serves as an abstract framework, outlining how various elements or variables within a system interconnect. The proportionality relationship signifies that changes in one variable directly influence another in a predictable manner, potentially through mathematical operations like multiplication or division. To precisely capture this connection, a differential equation is employed, providing a mathematical representation of how these variables change concerning one another. This approach is fundamental in numerous scientific and engineering disciplines, enabling a rigorous analysis of complex relationships within systems.

## Model Types
- Deterministic models
- Statistical models
## Deterministic models
In deterministic models, all the variables and parameters are expressed as functions of distinct spatial and temporal variables. These independent variables are conventionally denoted as x, y, z, and t.
### Space Dimensions
- 0D: Only time dependency, no space dependency (Ordinary differential equation).
- 1D: Has one space dimension. Typically for changes in vertical direction (e.g soil).1D steady state models lead to ordinary differential equations.
- 2D: Has two space dimensions. Horizontal and Vertical models.
- 3D: Complex models that requires methods such as Finite Differences, Finite Volumes or Finite Elements