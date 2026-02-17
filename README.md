# datafun-06-eda

## Project 6 Workflow

1. Create new repository titled datafun-06-eda with deafult readme

```bash
git clone https://github.com/kander643/datafun-06-eda
```

1. Add .gitignore and requirements.txt files
2. Use Git to add, commit, and push new files

```bash
git add -A
git commit -m "update:
git push -u origin main
```

3. Create a virtual environment and activate

```bash
uv venv
```

in powershell

```bash
.venv\Scripts\Activate
```

4. Install external packages

```bash
uv pip install jupyterlab numpy pandas pyarrow matplotlib seaborn
```

## Data Set Description

*Seaborn: Planets [Link Here](https://github.com/mwaskom/seaborn-data/blob/master/planets.csv)

**Total records:** 1,035

This dataset contains information about exoplanets discovered using various detection methods.

| Column Name     | Description                                      |
|----------------|--------------------------------------------------|
| method          | Method used to detect the planet (e.g., Radial Velocity, Transit) |
| number          | Number of planets discovered in the system      |
| orbital_period  | Orbital period of the planet in days            |
| mass            | Mass of the planet (in Jupiter masses)          |
| distance        | Distance of the planetary system from Earth (in parsecs) |
| year            | Year the planet was discovered                  |