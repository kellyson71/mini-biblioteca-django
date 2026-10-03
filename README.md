> [!IMPORTANT]
> **Repositório Central da Disciplina (DSW):**  
> Todas as atividades desta matéria foram reunidas, padronizadas e documentadas no repositório oficial:  
> 🔗 [**kellyson71/Desenvolvimento-de-Sistemas-Web**](https://github.com/kellyson71/Desenvolvimento-de-Sistemas-Web)  
> *(Acesse o link acima para visualizar o índice completo de atividades do curso de ATV-001 a ATV-007)*

---

# Atividade de Pesquisa - Models e Django Admin (Mini Biblioteca)

**Disciplina:** Desenvolvimento de Sistemas Web (DSW)  
**Professor:** Irlan Arley Targino Moreira  
**Aluno:** Kellyson Medeiros  

Aplicação web desenvolvida em Django demonstrando a criação e configuração de modelos de dados (*Models*), execução de migrações no banco SQLite, personalização do painel administrativo (`admin.py`) e exibição pública dos registros através de views e templates.

## Funcionalidades
- **Model `Livro`:** Cadastro de livros com título, autor, ano de publicação e status.
- **Django Admin Customizado:** Configuração de `list_display`, filtros laterais e busca por termos.
- **Catálogo de Livros:** Rota `/livros/` exibindo listagem estilizada e responsiva.
- **Relatório e Evidências:** Inclusão de `RESPOSTAS.pdf` com respostas teóricas e print comprobatório em `evidencias/lista-livros.jpg`.

## Como Executar
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 manage.py migrate
python3 manage.py runserver
```
