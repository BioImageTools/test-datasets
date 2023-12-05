# test-datasets
Test data for the BioImageTools nextflow modules and workflows. This is structured like [nf-core/test-datasets](https://github.com/nf-core/test-datasets).


# Creating/Downloading test data

Since the test data may be fairly large we recommend storing test data for a module or pipeline in a branch. Also in order to prevent this repo from growing too much try to reuse existing datasets as much as possible.

Just like [nf-core/test-datasets](https://github.com/nf-core/test-datasets) to clone a test dataset use:
```bash
git clone <url> --single-branch --branch <pipeline/modules/branch_name>
```

If more test datasets are needed use:
```bash
git remote set-branches --add origin [remote-branch]
git fetch
```
