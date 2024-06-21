Readme PySaar 2024:

Aim of this project was the modelling of a N-fold Pendulum and the numerical solution of the equations.
Two approaches were chosen: the Lagrange Methode and the Kane Methode. Lagrange Methode works up until three pendulums. For N>3 choose the Kane Methode.

Documentation and additional information could be found here:
https://pysaar2024documentation.streamlit.app/

For the Lagrange Methode there are additional examples called "Single_Pendulum_Lagrange" and "Double_Pendulum_Lagrange" (for a single and a double pendulum respectively).
If you want to use the Lagrange Methode for N<=3 in a flexible implementation use "N-fold_Pendulum_Lagrange".

For N>3 as mentioned above choose "Single_n-fold_Pendulum_Kane_Method" or "Multiple_n-fold_Pendulum_Kane_Method".
As the name suggest, "Single_n-fold_Pendulum_Kane_Method" is only for one N-fold pendulum.
"Multiple_n-fold_Pendulum_Kane_Method" calculates an arbitrary number of N-fold pendulums to visualize the chaotic nature of the system.

Multiple packages are imported in the scripts. Here is a list of packages that you might need to install (as those are not part of the standard library; note: maybe some packages are missing, please take a look at the imports at the top and chek if you get an error):
- numpy
- sympy
- matplotlib
- scipy
- IPython
