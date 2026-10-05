# Arquitetura

```text
USUÁRIO
   |
   v
FRONTEND
HTML + CSS + JavaScript
   |
 HTTP / JSON
   v
BACKEND
Node.js + Express
API REST
   |
 SQL
   v
SQLITE
Estudantes + Atendimentos
```

Fluxo: o usuário interage com o frontend; o JavaScript chama a API; o backend processa as regras e acessa o SQLite; a resposta retorna em JSON para a interface.
