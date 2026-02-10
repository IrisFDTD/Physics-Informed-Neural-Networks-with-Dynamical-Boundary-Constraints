# Supplementary material - Physics-Informed Neural Networks with Dynamical Boundary Constraints

Andrés Martínez-Esteban $^{1,2}$, Pablo Calvo-Barlés $^{2,3}$, Luis Martín Moreno $^{2,3}$ and Sergio G Rodrigo $^{1,2,*}$

*$^1$ Departamento de Física Aplicada, Facultad de Ciencias, Universidad de Zaragoza, 50009 Zaragoza, Spain*

*$^2$ Instituto de Nanociencia y Materiales de Aragón (INMA), CSIC-Universidad de Zaragoza, 50009 Zaragoza, Spain*

*$^3$ Departamento de Física de la Materia Condensada, Universidad de Zaragoza, Zaragoza 50009, Spain*

$^*$ corresponding author: sergut@unizar.es

# Abstract
Physics-informed neural networks (PINNs) are numerical solvers that embed all the physical information of a system into the loss function of a neural network. In this way the learned solution accounts for data (if available), the governing differential equations, or any other constraint known of the physical problem. However, they face serious issues, notably their tendency to converge on trivial or misleading solutions. The latter occurs when, although the loss function reaches low values, the model makes incorrect predictions. These difficulties become especially significant in differential equations involving multi-scale behavior, such as rapidly varying terms and solutions exhibiting strong oscillatory behavior. To address these challenges, we introduce the Dynamical Boundary Constraint (DBC) algorithm, which imposes restrictions on the loss function based on prior training of the PINN. To demonstrate its applicability, we tested this approach on examples of different areas of physics.
