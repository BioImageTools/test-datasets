# test-datasets

This contains test data for the BioImageTools nextflow modules.

> ⚠️ **Do not merge your test data to the `main` branch! Each pipeline and module has a dedicated branch.**

The structure of this repository is inspired by [nf-core/test-datasets](https://github.com/nf-core/test-datasets).

## Adding data

Check to see if a branch already exists for the module or pipeline you want to test. If not, create a new branch and commit your data there.

## Downloading test data

Due the large number of large files in this repository for each pipeline, we highly recommend cloning only the branches you would use.

```bash
git clone <url> --single-branch --branch <pipeline/modules/branch_name>
```

To subsequently clone other branches[^1]

```bash
git remote set-branches --add origin [remote-branch]
git fetch
```
