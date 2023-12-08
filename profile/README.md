## About `sbi`

`sbi` is a PyTorch package for simulation-based inference. Simulation-based inference is the process of finding parameters of a simulator from observations.

`sbi` takes a Bayesian approach and returns a full posterior distribution over the parameters of the simulator, conditional on the observations.
The package implements a variety of inference algorithms, including _amortized_ and _sequential_ methods.
Amortized methods return a posterior that can be applied to many different observations without retraining; sequential methods focus the inference on one particular observation to be more simulation-efficient.


## Get started

To get started using `sbi` begin by reading the [Documentation](https://www.mackelab.org/sbi/).


## Feedback and Contributions

We welcome any feedback on how `sbi` is working for your inference problems (see [Discussions](https://github.com/mackelab/sbi/discussions)) and are happy to receive bug reports, pull requests and other feedback (see
[contribute](http://www.mackelab.org/sbi/contribute/)).
We wish to maintain a positive community, please read our [Code of Conduct](CODE_OF_CONDUCT.md).

## Support

`sbi` has been supported by the German Federal Ministry of Education and Research (BMBF) through the project ADIMEM, FKZ 01IS18052 A-D) and through the Tübingen AI Center (FKZ: 01IS18039A). [ADIMEM](https://fit.uni-tuebingen.de/Project/Details?id=9199) is a collaborative project between the groups of Jakob Macke (Uni Tübingen), Philipp Berens (Uni Tübingen), Philipp Hennig (Uni Tübingen) and Marcel Oberlaender (caesar Bonn) which aims to develop inference methods for mechanistic models.

## Citation

If you use `sbi` consider citing the [sbi software paper](https://doi.org/10.21105/joss.02505), in addition to the original research articles describing the specific sbi-algorithm(s) you are using. 

```latex
@article{tejero-cantero2020sbi,
  doi = {10.21105/joss.02505},
  url = {https://doi.org/10.21105/joss.02505},
  year = {2020},
  publisher = {The Open Journal},
  volume = {5},
  number = {52},
  pages = {2505},
  author = {Alvaro Tejero-Cantero and Jan Boelts and Michael Deistler and Jan-Matthis Lueckmann and Conor Durkan and Pedro J. Gonçalves and David S. Greenberg and Jakob H. Macke},
  title = {sbi: A toolkit for simulation-based inference},
  journal = {Journal of Open Source Software}
}
```

The above citation refers to the original version of the `sbi` project and has a persistent DOI.
Additionally, new releases of `sbi` are citable via [Zenodo](https://zenodo.org/record/3993098), where we create a new DOI for every release.
