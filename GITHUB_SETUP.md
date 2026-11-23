# Publish this repository on GitHub

1. Create a new **empty** GitHub repository named `financial-document-rag-qlora`.
2. Extract this project folder locally, or upload its files through GitHub's **Add file → Upload files** interface.
3. Before committing, inspect the notebook and source for personal information, local paths, API keys, or tokens.
4. Do not upload model weights, private datasets, or generated binary indexes. `.gitignore` excludes common large artifacts.
5. Commit and push:

```bash
git init
git add .
git status
git commit -m "Add financial document RAG and QLoRA project"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/financial-document-rag-qlora.git
git push -u origin main
```

Replace `<YOUR_USERNAME>` with your GitHub username. Never put a GitHub token or password directly in source code.
