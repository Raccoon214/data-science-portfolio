# Bradley Beitscher — Data Science & ML Portfolio

Welcome! This repo collects selected projects from my AI/Data Science journey (Flatiron School and beyond). Each project includes context, reproducible code, and results.

## Highlights
- End-to-end ML pipelines (classification, regression, clustering)
- Clear business framing (CRISP-DM)
- Reproducible environments (`environment.yml`)
- Polished write-ups in `/docs` (auto-published to GitHub Pages)

## Structure
```
.
├─ projects/                # One folder per project
│  └─ _project-template/    # Copy this to start a new project
├─ docs/                    # Case studies (published via GitHub Pages)
├─ assets/                  # Images used in docs/README
├─ tools/                   # Utility scripts (e.g., lint, nb-convert)
├─ environment.yml          # Base environment for exploring the repo
├─ requirements.txt         # (Optional) pip requirements
├─ LICENSE
└─ README.md
```

## Getting Started
1. **Create/activate env**  
   ```bash
   conda env create -f environment.yml
   conda activate ds-portfolio
   ```

2. **Start a new project**
   ```bash
   cp -r projects/_project-template projects/your-project-name
   ```

3. **Run notebooks reproducibly**
   ```bash
   jupyter lab
   ```

4. **Publish docs** (GitHub Pages)  
   - In GitHub repo settings → **Pages**: set source to **Deploy from branch**, folder: **/docs** on `main`.
   - Edit `docs/index.md` to add featured projects.

## Featured Projects (placeholder)
- [Iris SVM — ROC/AUC & margin intuition](docs/iris-svm.md)
- [Retail Churn — cost-aware recall optimization](docs/churn-case-study.md)
- [Product Returns — Random Forest feature importances](docs/returns-case-study.md)

## Contact
- **LinkedIn:** (add link)
- **Website/Blog:** (optional)
- **Email:** Bradley_Beitscher@dpsk12.net

---

> Tip: Keep project READMEs short and outcome-focused; link deep dives to `docs/` pages.
