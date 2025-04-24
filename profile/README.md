## About `sbi`

`sbi` is a PyTorch package for simulation-based inference. Simulation-based inference is the process of finding parameters of a simulator from observations.

`sbi` takes a Bayesian approach and returns a full posterior distribution over the parameters of the simulator, conditional on the observations.
The package implements a variety of inference algorithms, including _amortized_ and _sequential_ methods.
Amortized methods return a posterior that can be applied to many different observations without retraining; sequential methods focus the inference on one particular observation to be more simulation-efficient.


## Get started

To get started using `sbi` begin by reading the [Documentation](https://sbi-dev.github.io/sbi/).


## Feedback and Contributions

We welcome any feedback on how `sbi` is working for your inference problems (see [Discussions](https://github.com/sbi-dev/sbi/discussions)) and are happy to receive bug reports, pull requests and other feedback (see
[contribute](http://sbi-dev.github.io/sbi/contribute/)).
We wish to maintain a positive community, please read our [Code of Conduct](https://sbi-dev.github.io/sbi/code_of_conduct/).

## Support

`sbi` has been supported by the German Federal Ministry of Education and Research (BMBF) through project ADIMEM (FKZ 01IS18052 A-D), project SiMaLeSAM (FKZ 01IS21055A) and the Tübingen AI Center (FKZ 01IS18039A).

## Citation

The `sbi` package has grown and improved significantly since its initial release, with
contributions from a large and diverse community. To reflect these developments and the
expanded functionality, we published an [updated JOSS
paper](https://doi.org/10.21105/joss.07754). We encourage you to cite this
newer version as the primary reference:

```latex
@article{BoeltsDeistler_sbi_2025,
  doi = {10.21105/joss.07754},
  url = {https://doi.org/10.21105/joss.07754},
  year = {2025},
  publisher = {The Open Journal},
  volume = {10},
  number = {108},
  pages = {7754},
  author = {Jan Boelts and Michael Deistler and Manuel Gloeckler and Álvaro Tejero-Cantero and Jan-Matthis Lueckmann and Guy Moss and Peter Steinbach and Thomas Moreau and Fabio Muratore and Julia Linhart and Conor Durkan and Julius Vetter and Benjamin Kurt Miller and Maternus Herold and Abolfazl Ziaeemehr and Matthijs Pals and Theo Gruner and Sebastian Bischoff and Nastya Krouglova and Richard Gao and Janne K. Lappalainen and Bálint Mucsányi and Felix Pei and Auguste Schulz and Zinovia Stefanidi and Pedro Rodrigues and Cornelius Schröder and Faried Abu Zaid and Jonas Beck and Jaivardhan Kapoor and David S. Greenberg and Pedro J. Gonçalves and Jakob H. Macke},
  title = {sbi reloaded: a toolkit for simulation-based inference workflows},
  journal = {Journal of Open Source Software}
}
```

This updated paper, with its expanded author list, reflects the broader community
contributions and the package's enhanced capabilities in releases
[0.23.0](https://github.com/sbi-dev/sbi/releases/tag/v0.23.3) and later.

If you are using a version of `sbi` prior to 0.23.0, please cite the original sbi
software paper:

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
