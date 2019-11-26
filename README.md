# jupyterthemes

jt -t onedork -f roboto -fs 14 -nfs 14 -tfs 14 -ofs 11



jt -t monokai -f fira -fs 13 -nf ptsans -nfs 11 -N -kl -cursw 5 -cursc r -cellw 95% -T



jt -t oceans16 -tf merriserif -tfs 10 -fs 12 -nf ptsans -nfs 13 -T -N -f roboto


jt -t monokai -f fira -fs 13 -cellw 90% -ofs 11 -dfs 11 -T -N


Make a file named 00_startup.py in ~/.ipython/profile_default/startup and stick the following snippet into it, and restart Jupyter



import os
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from jupyterthemes import jtplot
jtplot.style(theme=’monokai’, context=’notebook’, ticks=True, grid=False)
