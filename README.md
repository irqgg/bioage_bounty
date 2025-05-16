# BioAge FHE: Privacy-Preserving Epigenetic Age Prediction

This project implements **epigenetic age estimation** using DNA methylation data under **Fully Homomorphic Encryption (FHE)**, enabling **privacy-preserving predictions** of biological age.

## Live Demo

Try the encrypted prediction model directly in your browser: [Bio-Age-FHE on Hugging Face](https://huggingface.co/spaces/iri4/bio-age-fhe)

## Repository Structure

- `notebooks/` – Jupyter notebooks with all the experiments and evaluations.
- `bounty_report.pdf` – Summary report describing methods, implementation, and results.
- `sample_test_data.csv` – Example methylation data used for testing and comparison.

## Included Notebooks

- `hannum_fhe.ipynb`: FHE inference using the Hannum clock.
- `phenoage_fhe.ipynb`: FHE inference using the PhenoAge clock.
- `comparison_hannum_phenoage_fhe.ipynb`: Visual and numerical comparison across models.

They also include performance comparison using **Concrete-Numpy** for encrypted inference benchmarking.

## Models Used

- **Hannum Clock**: Predicts biological age using a linear model based on specific CpG sites.
- **PhenoAge Clock**: A more complex epigenetic estimator trained to capture physiological aging.

## FHE Framework

This project uses [Zama’s Concrete-ML](https://github.com/zama-ai/concrete-ml).
