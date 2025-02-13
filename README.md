# Direct Credits
https://github.com/karthik/wesanderson?tab=readme-ov-file

## To Install
```bash
pip install -e .
```

## To Use
```python
import matplotlib.pyplot as plt

# Check available colormaps
print(plt.colormaps())

# Use a Wes Anderson colormap
plt.imshow([[0,1]], cmap="Zissou1")
```