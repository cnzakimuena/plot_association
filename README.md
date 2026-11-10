# Association Plot
Script to generate an association plot. The plot uses systolic blood pressure measurements from the arm and finger ([Bland & Altman, 1995](https://www.thelancet.com/journals/lancet/article/PIIS0140673695917489/abstract)) for demonstration.

Environment setup:

```bash
conda create -n myenv python=3.11
conda activate myenv
```

Dependencies installation:

```bash
pip install -r requirements.txt
```

Usage:

```bash
python plot_association.py
```

<p align="center">
    <img src="figure.png" alt="example image" height="500">
</p>

### References

[Bland, J. M., & Altman, D. G. (1995). Comparing methods of measurement: why plotting difference against standard method is misleading. The lancet, 346(8982), 1085-1087.](https://www.thelancet.com/journals/lancet/article/PIIS0140673695917489/abstract)