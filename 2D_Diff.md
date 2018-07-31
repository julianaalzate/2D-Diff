# 2D-
2D dimensional diffusion equation
@author: Juliana Alzate
"""
# =============================================================================
# Importing libraries and external functions
# =============================================================================
import numpy as np
import matplotlib.pyplot as plt
from matplotlib import style
# =============================================================================
# Declaration of physical variables for the problem.
# =============================================================================
# plate size, mm
w = h = 10.
# intervals in x-, y- directions, mm
dx = dy = 0.1
#  Thermal diffusivity of stell, mm2.s-1
D = 4
Tcool = 300
Thot = 700
nx = int(w/dx)
ny = int(h/dy)
