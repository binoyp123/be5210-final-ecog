# BE 5210 final project — ECoG → finger flexion

Class competition thing from spring 2026: predict data glove finger movement from ECoG. Team was me (Binoy), Sohan Lele, and Eric Ouyang.

**What’s actually in this repo:** the dev notebook (`Final_Project.ipynb`), the submission-style inference notebook (`Final_Project_Submission.ipynb`), and our write-up (`Final Report.pdf`).

**What’s not here on purpose:** the `.mat` training/leaderboard/test files and the trained weights (`submission_models.zip`, `saved_models/`, etc.). They’re huge and the course data shouldn’t really be floating around on the public internet. If you’re a recruiter or whatever and want to see weights or numbers, email me.

## Running it

You’ll need the course `.mat` files in the same folder as the notebook if you want it to actually execute (names are in the first few cells of each notebook). I did most of the heavy training on Colab with a GPU; the submission notebook is meant to run there too with the zip + pickle the assignment asked for.

Local-ish setup (Python 3.10+ is fine):

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Then open the notebooks in Jupyter or VS Code and go from there.

## AI use

We used ChatGPT-type stuff for debugging, explaining concepts, and bouncing ideas around — not for copy-pasting the whole project. Same note as in our submission notebook.
