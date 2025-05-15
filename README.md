# Profitable App Profiles

In this project, I am working as a data analyst for a company that develops free-to-download mobile apps available on both Google Play and the App Store. The company's primary revenue stream comes from in-app advertisements, making user engagement a critical factor for financial success.

By analyzing mobile app data, I aim to uncover insights into which types of apps attract the most users and drive higher engagement. The goal is to provide the developers with data-driven recommendations on the kinds of apps that are likely to achieve stronger user engagement. By identifying key characteristics of popular apps, the company can better align its development efforts with market demand and increase revenue through more effective ad exposure.

## Project Structure

```
profitable-app-profiles/
│
├── data/              # Directory for raw and/or cleaned datasets used in the analysis
├── notebook/          # Contains the Jupyter Notebook that includes exploratory data analysis and results
├── .gitignore         # Specifies files and directories to be ignored by Git (e.g., virtual environments, cache files)
├── requirements.txt   # Lists Python packages required to run the project (generated from pyproject.toml)
├── pyproject.toml     # Project metadata and dependency configuration (used by modern Python packaging tools)
├── .python-version    # Defines the Python version for the virtual environment (used by tools like pyenv)
├── uv.lock            # Lock file for `uv` that ensures consistent dependency versions across environments
└── README.md          # Provides an overview of the project, setup instructions, and usage notes

```

## Dataset

The datasets used in this project are publicly available on Kaggle:

-   **[Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps):** A dataset containing data about approximately ten thousand Android apps from Google Play. The dataset can be downloaded directly from [this link](https://dq-content.s3.amazonaws.com/350/googleplaystore.csv).
-   **[Mobile App Store](https://www.kaggle.com/datasets/ramamet4/app-store-apple-data-set-10k-apps):** A dataset containing data about approximately seven thousand iOS apps from the App Store. The dataset can be downloaded directly from [this link](https://dq-content.s3.amazonaws.com/350/AppleStore.csv).

The CSV files used for analysis are stored in the `data/` directory for reproducibility.

## Getting Started

To run this project locally:

1. **Clone the repository**

    ```bash
    git clone https://github.com/xjwllmsx/profitable-app-profiles.git
    cd profitable-app-profiles
    ```

2. **Create and activate a virtual environment**

    ```bash
    uv venv
    uv pip install -r requirements.txt
    ```

3. **Launch Jupyter Notebook**
    ```bash
    jupyter notebook notebook/analysis.ipynb
    ```
    **NOTE:** If you're using `uv`, the dependencies are managed via `pyproject.toml` rather than `requirements.txt`.

## Try it Online

You can run the notebook directly in your browser via Binder:

[![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/xjwllmsx/profitable-app-profiles/HEAD?urlpath=%2Fdoc%2Ftree%2Fnotebook%2Fanalysis.ipynb)

## License

This project is for educational purposes only. The dataset used is publicly available and credited to its original creator on Kaggle.
