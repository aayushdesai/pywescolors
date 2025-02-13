# Direct Credits
https://github.com/karthik/wesanderson?tab=readme-ov-file

## To Install
```bash
pip install -e .
```

## To Use
```python
import matplotlib.pyplot as plt
import wes_colors

# Check available colormaps
print(plt.colormaps())

# Use a Wes Anderson colormap
plt.imshow([[0,1,2,3,4]], cmap="Zissou1")
```

## To set it as a cycler
```python
import matplotlib.pyplot as plt
from wes_colors import wes_colors
plt.rc('axes', prop_cycle=plt.cycler(color=wes_colors.get_wes_cycle('Darjeeling1')))
```

How they look:
### Zissou1
![Zissou1](Figures/Zissou1.png)
### Darjeeling1
![Darjeeling1](Figures/Darjeeling1.png)
### Darjeeling2
![Darjeeling2](Figures/Darjeeling2.png)
### Moonrise1
![Moonrise1](Figures/Moonrise1.png)
### Moonrise2
![Moonrise2](Figures/Moonrise2.png)
### Moonrise3
![Moonrise3](Figures/Moonrise3.png)
### Rushmore
![Rushmore1](Figures/Rushmore.png)
### Royal1
![Royal1](Figures/Royal1.png)
### Royal1
![Royal1](Figures/Royal2.png)



