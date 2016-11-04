# CSLO Images

Here are contained a set of images which each have one perturbation. [output.csv](output.csv) has each image listed with its corresponding URL and perturbation. Every image should be compared to [base.png](base.png), which is the original, unperturbed image.

## Perturbations

```python
ELEMENTS = ['a', 'p', 'img', 'li', 'h1', 'h2', 'h3', 'tr', 'button']

ATTRS = {
  'a': ['color',  'float', 'font-size', 'text-align'],
  'p': ['color',  'float', 'font-size', 'text-align'],
  'img': ['float', 'font-size'],
  'li': ['color',  'float', 'font-size', 'text-align'],
  'h1': ['color',  'float', 'font-size', 'text-align'],
  'h2': ['color',  'float', 'font-size', 'text-align'],
  'h3': ['color',  'float', 'font-size', 'text-align'],
  'tr': ['color',  'float', 'font-size', 'text-align'],
  'button': ['color',  'float'],
}

OPTIONS = {
  'color': ['black', 'red', 'green', 'blue', 'purple'],
  'float': ['none', 'left', 'right'],
  'font-size': ['1em', '.5em', '.8em'],
  'text-align': ['left', 'right', 'center'],
}
```
