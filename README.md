# The Greenwich Corner Books — Projeto Integrador (DWS • POO • BD)

Sistema web completo de gerenciamento de uma livraria em Greenwich Village, Nova York, desenvolvido para o **Projeto Integrador do 2º Ano do Curso Técnico em Informática (UNASP-HT)**.

## Como Publicar no GitHub Pages (Passo a Passo)

1. Crie um novo repositório público no GitHub (ex.: `the-greenwich-corner-books`).
2. Clique em **uploading an existing file** (ou arraste os arquivos) e envie **todos os arquivos e pastas desta raiz** (`index.html`, `.nojekyll`, `.gitignore`, `README.md`, `css/`, `js/`, `backend/`, `database/`).
3. Clique em **Commit changes**.
4. Vá em **Settings → Pages**, em **Branch** selecione `main` e a pasta `/ (root)`, e clique em **Save**.
5. Aguarde ~1 minuto e acesse o link gerado pelo GitHub Pages. O sistema funciona imediatamente no navegador com persistência local!

## Como Executar Localmente com Python (Flask + SQLite)

1. Instale as dependências:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```
2. Inicie o servidor Flask (cria e popula `database/livraria.db` automaticamente):
   ```bash
   python app.py
   ```
3. Abra `index.html` no navegador (ou via Live Server).
