# Projeto MkDocs

Este projeto foi iniciado com MkDocs e utiliza um ambiente virtual Python (venv).

## Como usar

1. **Ative o ambiente virtual:**
   
   No PowerShell:
   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```
   
   No CMD:
   ```cmd
   .\.venv\Scripts\activate.bat
   ```

2. **Instale o tema Material para MkDocs:**
   ```powershell
   pip install mkdocs-material
   ```

3. **Configure o tema no arquivo `mkdocs.yml`:**
   ```yaml
   theme:
     name: material
   ```

4. **Rodar o servidor MkDocs:**
   ```powershell
   mkdocs serve
   ```

5. **Gerar a documentação estática:**
   ```powershell
   mkdocs build
   ```

Acesse a documentação localmente em http://127.0.0.1:8000/ após rodar `mkdocs serve`.
