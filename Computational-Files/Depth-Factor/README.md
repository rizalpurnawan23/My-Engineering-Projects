# Interpolation of Depth Factor for Computing Immediate Settlements of Foundations

In this project we use a machine learning (ML) approach for interpolations of a factor
called "depth factor" in the theory of immediate settlement of foundations [1].
In the approach presented in [2], the value of depth factor $I_f$ needs to be interpolated
from a table presented in [2]. A common interpolation approach is by taking a direct linear
interpolation between two points. We propose an alternative method for the interpolation
by making use of an ML model.

The detail development of the ML model can be accessed in
[this notebook](/Computational-Files/Depth-Factor/Depth_Factor.ipynb).
The notebook also provides a conclusive formula for the interpolation, which could be
an equivalent approach to the use of ML. While the ML model can be accessed and downloaded
[here](/Computational-Files/Depth-Factor/depth_factor.joblib).
A related document to this directory is a report located on
[this directory](/Engineering-Reports/Technical_Justification__Settlement_Transmission_Towers.pdf).

## Reference

[1] Das, B. M. and Sobhan, K. (2012). *Principles of Geotechnical Engineering*. Cengage Learning.

[2] Das, B. M. and Sobhan, K. (2012). *Principles of Geotechnical Engineering*. page 362. Cengage Learning.
