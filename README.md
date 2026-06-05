# Tissue SIV Decay

This repository contains the manuscript companion notebook for the joint PLN/MLN
FDC-SIV decay analysis in Chan CN, Busman-Sahay K, Nekorchuk M, et al.,
"Anti-CD21/CR2 antibody treatment disrupts SIVmac239 deposition on follicular
dendritic cells during antiretroviral therapy."

## Reproduce the analysis

Install the locked uv environment:

```sh
uv sync --locked
```

Run the notebook:

```sh
uv run jupyter nbconvert --to notebook --execute --inplace joint_PLN_MLN_LME_manuscript_v5.ipynb
```

The notebook writes these tracked manuscript artifacts:

- `figure4B_joint_PLN_MLN_LME_v5.png`
- `figure4B_joint_PLN_MLN_LME_v5.pdf`
