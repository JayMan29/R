# NIS ATTR Analysis

This repository contains an R script (`new code`) that analyzes NIS 2016–2022 data for ATTR-related hospitalizations, computes yearly rates, and runs CKD models.

To see the entire script without truncation, open it with line numbers using:

```bash
less -N "new code"
```

Use `/` inside `less` to search for sections like "Yearly ATTR rates" or "Multivariable" if you want to jump to specific parts.

## Installing R (to get `Rscript`)
Run these commands in the repo's dev container or any Debian/Ubuntu shell to install base R and the `Rscript` executable:

```bash
sudo apt-get update
sudo apt-get install -y r-base
```

After installation you should see a path when you run:

```bash
which Rscript
```

## Running the analysis
Assuming the NIS dataset path in the script (`nis_path`) is valid for your machine, execute:

```bash
Rscript "new code"
```

If your NIS file lives elsewhere, edit the `nis_path` value near the top of the script before running.
