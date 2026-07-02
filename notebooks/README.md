# Jupyter notebooks

Notebooks implementing the integral-equation calculations.

---

## Note on archival dependencies

The notebooks in this repository document the computational workflow developed for the published theory.

Most notebooks can be executed directly using the material provided in this repository. However, a small number of notebooks refer to intermediate data files that were generated during the original research workflow and were not preserved in the archived project.

In particular, `MHNC.ipynb` references:

- `Bridge_function/bridge_eta0p443.out`
- `g_EqGrid_deltar_0p01_Yukawa_Nohydro_Pe10_kappa2_Gamma150.in`

These files are not currently available in the repository. Consequently, `MHNC.ipynb` is included primarily for methodological completeness and may require regeneration of these intermediate inputs before it can be executed end-to-end.
