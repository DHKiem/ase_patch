# ase_patch
### Step1: check your ase path first
```
>>> import ase
>>> print(ase.__file__)
```

### Step2: copy the file into the relevant path

e.g. (case for PAO lists update)
```
cp calculators/openmx/default_settings.py $ASE_DIR/calculators/openmx/
```

