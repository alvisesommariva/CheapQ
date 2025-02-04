# CheapQ
 Matlab codes for cheap and stable tetrahedra-free quadrature on polyhedra

a) The zip file contains 4 demos. 

The files demo_01 and demo_02 illustrate the numerical examples performed in 
the section "Implementation and examples" of the paper 
         "Cheap and stable quadrature on polyhedral elements" 
by Alvise Sommariva, Marco Vianello. 

The files demo_03 and demo_04 show how to use the software on integrating 
functions and to perform comparisons between the available methods, also
using cubature compression

b) The cheap main routines are 
1. cubature_polyhedron_cheap
2. cheap_startup

Subroutines used are
a) cubature_triangle.m
b) dCHEBVAND.m
c) mono_next_grlex.m
d) polygauss_2013.m / polygauss_2018.m
e) tenscheb_norm2sq.m

