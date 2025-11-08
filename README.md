[![CI](https://github.com/datarockstars/genai-course-notebooks/actions/workflows/ci.yml/badge.svg)](https://github.com/datarockstars/genai-course-notebooks/actions/workflows/ci.yml)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

# Mini-cours IA Générative — Notebooks

Six notebooks Jupyter, un par leçon :

1. 01_IA_generative.ipynb
2. 02_LLMs.ipynb
3. 03_stable_diffusion.ipynb
4. 04_LangChain_intro.ipynb
5. 05_Neural_Style_Transfer.ipynb
6. 06_Architectures_complexes.ipynb

## Installation

```bash
python -m venv .venv
source .venv/bin/activate  # (Windows: .venv\Scripts\activate)
pip install -r requirements.txt
```

## Notes

- Les cellules peuvent être longues à exécuter sur CPU (Stable Diffusion notamment).
- Pour la Leçon 5, placez `content.jpg` et `style.jpg` dans le dossier courant avant d'exécuter la cellule principale.
- Pour la Leçon 4 (LangChain), renseignez la variable d'environnement `OPENAI_API_KEY` ou adaptez à un modèle local via `langchain_community`.
