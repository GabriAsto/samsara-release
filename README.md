## `samsara`-release

Data realise of the paper `samsara`: _A Continuous-Time Markov Chain Monte Carlo Sampler for Trans-Dimensional Bayesian Analysis_

G. Astorino, L. V. Dall'Armi, R. Buscicchio, J. Pomper, A. Ricciardone, W. Del Pozzo. [arXiv:XXX.YYY](https://doi.org/10.48550/arXiv.2511.07385).

## Credits

You are free to use this dataset in your reasearch. If you use it, we kindly ask you to cite the paper above. 

If you want to cite specifically the data release, its DOI is: 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17665822.svg)](https://doi.org/10.5281/zenodo.17665822)

## Git LFS
Some of the data files are tracked with Git LFS, being large. 
Please make sure you have Git LFS installed. To obtain them, clone the repository with:
```bash
git lfs install
git clone <repo-url>
```

## Data
The minimal data used to build the figures in the test cases of the paper above are provided within the repository in the `./data/` subfolder. 
The `./data/` subfolder is further divided in subfolders: 
- `./data/analytic/`
- `./data/sinewaves_lorentzians/`
- `./data/GMM/`
- `./data/convergence/`
each one explicative of the test case.

In addition, `./data/sinewaves_lorentzians/` contains `./data/sinewaves_lorentzians/zeronoise/` and `./data/sinewaves_lorentzians/noisy/` for differentiating the data of the zeronoise run and the noisy run.

We further provide Jupyter Notebooks to reproduce the figures.


## Contents

In the subfolder `./notebooks/`, you can find all the notebooks used for the figures. In particular:
- `./notebooks/Analytic.ipynb/` for the figure of the analytic test case on the paper above;
- `./notebooks/SineWavesLorentzians.ipynb/` for the figure of the multi-species test case with overlapping sine waves and lorentzians signals on the paper above;
- `./notebooks/GMM.ipynb/` for the figure of the GMM test case on the paper above;
- `./notebooks/convergence.ipynb/` for the figure of the PSRF test case on the paper above;

The subfolder `./plots/` is again structured as `./data/`, without the division from zeronoise and noisy runs in the sine waves overlapped to Lorentzians test case. The figures are named as they appear on the paper above.

## Contributions

Feel free to open issues or pull requests if you find any problem.
If you want access to deeper data behind figures!
