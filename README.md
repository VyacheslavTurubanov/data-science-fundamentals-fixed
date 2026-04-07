# Data Science Fundamentals (Fixed Version)

## Overview

This repository contains a fixed and runnable version of the **Share Network SQL/Pandas lecture notebooks**.

The original materials contained multiple issues that prevented successful execution, including:

* broken file paths
* incorrect variable names
* inconsistent joins and column references
* unstable environment configuration

These issues have been resolved to make the project reproducible and runnable locally.

---

## Common Issues

If you see errors like:

ModuleNotFoundError

Make sure:
- You are using Python 3.11–3.12
- You ran: poetry install
- You started Jupyter via: poetry run jupyter notebook

If Poetry uses wrong Python version:

poetry env use python3.12

## Requirements

* Python **3.11–3.12** (⚠️ Python 3.13+ is NOT supported)
* Poetry

---

## Setup (Poetry)

1. Install Python 3.12 (recommended)
   https://www.python.org/downloads/

2. Install Poetry (if not installed):
   https://python-poetry.org/docs/#installation

3. Install dependencies:

```bash

poetry env use python3.12
poetry install
```

4. Run Jupyter Notebook:

```bash
poetry run jupyter notebook
```

---

## Project Structure

* `lecture_1_fixed.ipynb` – SQL basics

* `lecture_2_fixed.ipynb` – joins

* `lecture_3_fixed.ipynb` – pandas

* `lecture_4_fixed.ipynb` – visualization

* `lecture_5_fixed.ipynb` – machine learning

* `chinook.db` – SQLite database

* `data/` – CSV datasets

---

## Notes

* All notebooks are designed to run locally
* No external data sources are required
* Environment is fully managed via Poetry
* The Python version is intentionally restricted for compatibility with dependencies

---

## Purpose

This repository is intended for learning and practice.

It preserves the original structure and intent of the course while fixing execution issues and ensuring a stable development environment.
