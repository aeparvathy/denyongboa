# Scenario-empowered digital transformation in Chinese commercial banks

Code for the paper *Scenario-empowered digital transformation in Chinese commercial banks: a conceptual framework* by Zhiwei Yin, Qiming Wang and Deyong Bao (submitted to the *Asia-Pacific Journal of Operational Research*).

The code implements the two-level model in Section 4 and reproduces all numerical results in Section 6.

## Files

| File | Content |
|---|---|
| `model.py` | Parameters (Tables 3 and 4), the fluid matching LP (3)–(6) and the strategic MILP (7)–(11) |
| `sim.py` | Online matching policies (Section 5.2) and Experiments 1–4 |
| `figs.py` | Figures 2 and 3 |
| `results.json` | Output of `sim.py` used in the paper |

## Requirements

Python 3.10 or later.

```
pip install -r requirements.txt
```

The MILP and LP are solved with HiGHS through `scipy.optimize`, so no commercial solver is needed.

## Reproducing the results

```
python sim.py    # about 2 minutes; writes results.json and prints a summary
python figs.py   # writes fig2.png and fig3.png
```

Random seeds are fixed, so the results match the paper exactly (tested with NumPy 2.4 and SciPy 1.17). Other library versions may give small differences in the simulation results.

## Notes

- Monetary values are in MU (1 MU = 1,000 CNY) and flows are monthly.
- All parameter values are illustrative. They are not estimated from the data of any bank.
- To test other settings, edit the parameter block at the top of `model.py`.

## Citation

If you use this code, please cite the paper (details will be added after publication).
