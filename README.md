# Molecule Studio – Simple Chemistry Website

## Features
- Enter and validate SMILES notation
- Display 2D molecular structures
- Generate and display interactive 3D conformers
- Calculate formula, molecular weight, atoms, bonds, LogP and hydrogen-bond counts
- Download a PDF report with molecular details and a 2D structure

## Run locally
1. Install Python 3.10 or newer.
2. Open Terminal in this folder.
3. Create and activate a virtual environment (recommended).
4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Start the website:

   ```bash
   streamlit run app.py
   ```

## Deploy on Streamlit Community Cloud
1. Upload `app.py`, `requirements.txt`, and `README.md` to the root of a GitHub repository.
2. In Streamlit Community Cloud, choose that repository.
3. Set the main file path to `app.py`.
4. Deploy.

If deployment reports an RDKit installation error, check the Streamlit app logs and redeploy after confirming that the selected Python runtime is supported by the RDKit wheel.
