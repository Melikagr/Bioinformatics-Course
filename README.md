# 🧬 Bioinformatics-Course

This repository collects Jupyter notebooks created for learning and experimenting with bioinformatics workflows using **Python (Biopython)** and **R (Bioconductor)**.  
It is intended for **educational and exploratory purposes**, not as production-ready pipelines.


## 🔎 What’s inside

| Folder / File | Description |
|---------------|-------------|
| `notebooks/`  | Example notebooks demonstrating various tasks (sequence handling, database fetch, GC content analysis, etc.) |
| `README.md`   | This overview and instructions |
| `.gitignore`  | Files to be ignored by Git (e.g. notebook checkpoints) |


## 📚 Notebooks Overview (Learning Path)

This repository is organized as a **progressive learning path**.  
Each notebook builds intuition for a different stage of a bioinformatics workflow.

| Notebook | Focus | What you learn |
|--------|------|---------------|
| `00_Introduction_to_Bioinformatics.ipynb` | Concepts | What bioinformatics is, where coding fits, and common workflows |
| `01_Introduction_to_Biopython.ipynb` | Python / Data processing | Working with sequences, FASTA/GenBank files, NCBI Entrez, basic biological transformations |
| `02_Introduction_to_R.ipynb` | R / Statistical analysis | Bioconductor ecosystem, RNA-seq data structures, DESeq2 workflow, visualization & interpretation |

**Recommended order:**  
`00 → 01 → 02`



## 🧠 Python vs R in Bioinformatics (High-level intuition)

This repository intentionally uses **both Python and R**, reflecting real-world bioinformatics practice:

### Python / Biopython
- Data retrieval (e.g. NCBI)
- File parsing (FASTA, GenBank)
- Sequence manipulation
- Preprocessing and lightweight workflows

### R / Bioconductor
- Statistical modeling
- Differential expression analysis
- Genomics-specific data structures
- Visualization and reproducible reporting


Think of **Biopython** as a data-handling and workflow *glue*,  
and **Bioconductor** as a statistical *engine* for genomics.



## 🚀 How to use

1. Clone the repository:  
   ```bash
   git clone https://github.com/Melikagr/Bioinformatics-Course.git
   cd Bioinformatics-Course
   ```


2. (Optional) Create a virtual environment and install dependencies:

    ```bash
    python -m venv venv
    source venv/bin/activate
    pip install biopython matplotlib
    ``` 

    > Note: Some notebooks require **R** and **Bioconductor**.  
    > See `02_Introduction_to_R.ipynb` for details.

3. Open any notebook in the notebooks/ folder

Use Jupyter Notebook to explore and run the examples.

Note: Some notebooks fetch data from online databases —
you will need an active internet connection and a valid email configured for Entrez.

## ⚠️ Important — Educational Use Only

This repository is created for **learning and demonstration purposes**.
It is **not** intended as a production-ready bioinformatics pipeline.
Use it as a sandbox for experimentation, exploration, and practice.


## 🔗 References & Further Reading
The following resources were used for learning, inspiration, and example datasets.


- **Biopython Official Documentation & Tutorial**  
  https://biopython.org/docs/latest/Tutorial/

- **Bioconductor Project**  
  https://www.bioconductor.org/

- **DESeq2 paper** (Love, Huber, Anders)  
  https://genomebiology.biomedcentral.com/articles/10.1186/s13059-014-0550-8

- **airway RNA-seq dataset**  
  https://bioconductor.org/packages/release/data/experiment/html/airway.html

- **STAT115 / BIO282 — Introduction to Computational Biology and Bioinformatics (Harvard, 2021)**  
  An influential course that inspired parts of the educational structure used in this repository.
