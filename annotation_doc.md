## Annotation documentation
Here are some annotation documentation about `/BDGRN/`.

### `aupr_cutoff.R`
compute the aupr of all datasets with cutoff=50% on undirected graph.

### `auprc_test50.R` 和 `auroc_test50.R`
compute the aupr/auroc of all datasets with cutoff=50% and traverse window parameter (`w`) from 0.1 to 0.9.

### `epr_cutoff100.R` 和 `epr_cutoff50.R`
compute the EPR(early precision ratio) of all datasets with setting cutoff = 100% (no filter) and cutoff=50%.

### `example.R`
you can run `example.R` to quickstart a test with `BDGRN`.

### `win50.R`
compute the aupr of all datasets by setting cutoff = 50% and window parameter `w=2/3`.
