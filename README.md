# Radiology AI Tutorial: Hands-On Introduction for Radiologists

Welcome! This repository contains interactive notebooks designed to give radiologists a practical, hands-on introduction to artificial intelligence in medical imaging — **no prior programming experience required**.

***

## What Is This?

This tutorial walks you through building an AI model that segments the prostate on MRI. You will see, step by step, how AI "learns" to identify anatomical structures — the same kind of technology behind AI tools you may already encounter in clinical practice.

Everything runs in your web browser. You do not need to install any software.

***

## What Is Inside

| File                                            | What It Does                                                                                                              |
| ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| `python_primer_for_radiologists.ipynb`          | Start here if you have never written code. A 30–45 minute introduction to Python using medical imaging examples.          |
| `medical_imaging_hands_on_model_training.ipynb` | The main tutorial. Loads a prostate MRI dataset, preprocesses it, trains a segmentation model, and evaluates the results. |

***

## How to Open and Run the Notebooks

The notebooks run on **Google Colab** — a free, browser-based environment provided by Google. You only need a Google account.

### Step 1 — Open the notebook on GitHub

1. Make sure you are on the repository's main page on GitHub (the page you are reading this on).
2. Click on the file you want to open — for example, `medical_imaging_hands_on_model_training.ipynb`.
3. GitHub will show you a preview of the notebook.

### Step 2 — Open in Google Colab

Once the notebook preview is open on GitHub, you have two options:

**Option A (easiest):**
In your browser's address bar, the URL will look like:

```
https://github.com/YOUR-USERNAME/radiology_ai_tutorial/blob/main/medical_imaging_hands_on_model_training.ipynb
```

Change the word `github.com` to `githubtocolab.com` and press Enter. Colab will open the notebook directly.

**Option B:**

1. Go to <https://colab.research.google.com>
2. Click **File** → **Open notebook**
3. Select the **GitHub** tab
4. Paste the URL of this repository and press Enter
5. Click on the notebook you want to open

### Step 3 — Run the notebook

Once the notebook is open in Colab:

1. Sign in with your Google account if prompted.
2. Read the text cells (white background) — they explain what each step does in plain language.
3. To run a code cell (gray background), click on it and press **Shift + Enter**, or click the play button (▶) on the left side of the cell.
4. Run the cells **from top to bottom, in order**.
5. Each cell will show its output (results, images, numbers) directly below it.

> **Tip:** If you see a warning that says "This notebook was not authored by Google," click **Run anyway**. This is normal for notebooks shared from GitHub.

***

## Recommended Order

1. If you have never coded before, open **`python_primer_for_radiologists.ipynb`** first.
2. Then open **`medical_imaging_hands_on_model_training.ipynb`** for the full AI training experience.

***

## What You Will Learn

* How medical images (NIfTI format) are loaded and preprocessed for AI
* What data augmentation is and why it matters
* How a U-Net model learns to segment anatomy from labeled examples
* How to evaluate model performance with clinical metrics (Dice score)
* How to visualize the model's predictions alongside ground truth

***

## Questions or Issues

If something is not working, try the following:

* Make sure you are running cells in order from top to bottom.
* If a cell gives an error, re-read the error message — it often tells you exactly what went wrong.
* Try **Runtime** → **Restart and run all** in the Colab menu to start fresh.

If you are still stuck, contact the tutorial authors.

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, share, and adapt the material with attribution.
