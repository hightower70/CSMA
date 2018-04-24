# CSMA
Port of Java Matrix Package (JAMA) to C# .

It has the basic Matrix class, with overloaded operators and contains several decomposition methods:
* Cholesky Decomposition of symmetric, positive definite matrices
* LU Decomposition (Gaussian elimination) of rectangular matrices
* QR Decomposition of rectangular matrices
* Eigenvalue Decomposition of both symmetric and nonsymmetric square matrices
* Singular Value Decomposition of rectangular matrices

This repository is a fork of Tim Felty's port of the NIST JAMA library to C#.
I have removed the jagged array storage and changed to uniform storage. I've also added some overloaded operators, functions (ToString, Equals, GetHashCode) which are common in c# classes.

The original JAMA code included the following Copyright Notice:
This software is a cooperative product of The MathWorks and the 
National Institute of Standards and Technology (NIST) which has been released to the public domain. 
Neither The MathWorks nor NIST assumes any responsibility whatsoever for its use by other parties, 
and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic.
