# Modelo Entidade-Relacionamento

```text
ESTUDANTE
---------
id (PK)
nome
turma
frequencia
media
nivel

        1
        |
        | recebe
        |
        N
ATENDIMENTO
-----------
id (PK)
estudante_id (FK)
data
tipo
descricao
responsavel
```

Um estudante pode possuir zero ou vários atendimentos. Cada atendimento pertence a um estudante.
