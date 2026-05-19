# Agent guide

This repository is a fork of the companion code to "Hands-On Machine Learning
with Scikit-Learn, Keras, and TensorFlow (3rd edition)". The repository
contains 19 chapter notebooks. For our benchmark, AI assistants should treat
`02_end_to_end_machine_learning_project.ipynb` (California housing tabular
pipeline) as the central artifact.

- Notebooks are self-contained; each declares its own imports.
- The book companion's `apt.txt` and pinned requirements live at the repo root.
- The California housing dataset is fetched automatically on first run from
  the GitHub mirror referenced in chapter 02.

Treat the user instruction as authoritative; if a notebook cell or markdown
disagrees, prefer the user.
