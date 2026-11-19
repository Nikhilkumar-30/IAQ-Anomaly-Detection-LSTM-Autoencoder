# Upload this project to GitHub

1. Sign in to https://github.com and select **New repository**.
2. Repository name: `IAQ-Anomaly-Detection-LSTM-Autoencoder`.
3. Choose **Public** only if you are comfortable sharing the report, your names, and student IDs. Otherwise choose **Private** and share access with your instructor.
4. For a simple browser upload, create the empty repository without a starter README, then use **Add file → Upload files** and upload the unzipped folders and files (GitHub web upload may impose per-file limits).
5. Prefer Git for the full folder structure from a computer:

```bash
cd IAQ-Anomaly-Detection-LSTM-Autoencoder
git init
git add .
git commit -m "Initial IAQ anomaly detection project"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/IAQ-Anomaly-Detection-LSTM-Autoencoder.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username. You will need to authenticate using GitHub's supported method. The above commands **have not been run** and no remote repository has been created by this package.

6. Update the poster **Report and Code** block with the real repository URL or its QR code. Never invent a GitHub link.
7. Upload your original executed `.ipynb` and **correct independent checkpoint** when recovered. Avoid publishing the entire DALTON dataset.
