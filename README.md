# Exemplos_radar_livro-3.Interpolation
 
 Produto referente a interpolação dos dados de pluviometros do CEMADEN (Centro Nacional de Monitoramento e Alertas de Desastres Naturais). 
 
Requisitos para execução;
import pandas as pd
from metpy.interpolate import (interpolate_to_grid, remove_nan_observations,remove_repeat_coordinates)
from mpl_toolkits.basemap import Basemap 
import matplotlib.pyplot as plt
import matplotlib as mpl
from scipy import linalg, optimize
import numpy as np
from matplotlib.colors import BoundaryNorm
from scipy.interpolate import griddata  
import numpy.ma as ma
 
 Dados Interpolados para Santa Catarina;
 
![image](https://github.com/vlsantos-bit/Exemplos_radar_livro-3.Interpolation/blob/master/interp_rbf.png)

Outros tipos de interpolações

![image](https://github.com/vlsantos-bit/Exemplos_radar_livro-3.Interpolation/blob/master/interp.png)
