# Financial Product Valuation with AI‑Generated Economic Scenarios (VAE)

This project builds an end-to-end pipeline to generate forward-looking multivariate economic scenarios using a Variational Autoencoder (VAE) and use them for valuation and risk analysis of financial products (options, structured products, portfolios). 
The aim is to produce realistic, probabilistic scenario paths that preserve temporal dynamics. 
A VAE learns a continuous latent distribution (typically Gaussian) from historical data, enabling principled sampling of new scenarios and direct quantification of epistemic uncertainty.

## Installation

1. Create and activate a Python virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt 
```
## Usage

Open the notebooks in order to reproduce the pipeline:

```bash
jupyter notebook notebooks/ProjetVAE2025.ipynb
```

