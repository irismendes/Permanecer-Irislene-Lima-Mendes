# Permanecer+ — Sistema de Acompanhamento da Permanência Escolar

**Autora:** Irislene Lima Mendes  
**Modalidade:** Projeto individual  
**Tema:** Permanência e evasão escolar  
**Ano:** 2026

## 1. Proposta
O Permanecer+ é uma aplicação web acadêmica criada para apoiar a escola no acompanhamento preventivo de estudantes. A solução organiza frequência, média, participação e registros de atendimento em um único fluxo.

O diferencial em relação a uma simples tela de indicadores é o registro da intervenção: depois de identificar um sinal de atenção, a equipe pode registrar a ação realizada e manter um histórico.

## 2. Funcionalidades
- Dashboard com indicadores gerais.
- Classificação de sinal em baixo, moderado e alto, baseada em regras transparentes.
- Cadastro de estudantes.
- Consulta dos indicadores de cada estudante.
- Registro de atendimentos pedagógicos, familiares, orientação e assistência.
- Banco SQLite local.
- API REST em Node.js.
- Interface responsiva.
- Dados iniciais totalmente fictícios.

## 3. Regra de sinal
O sistema soma pontos de três grupos: frequência, média e participação. Quanto maior a pontuação, maior a necessidade de acompanhamento. Essa classificação é apenas um indicador operacional e não uma previsão determinística de abandono.

## 4. Tecnologias
- HTML5
- CSS3
- JavaScript
- Node.js
- SQLite / better-sqlite3
- HTTP REST

## 5. Como executar
Requisitos: Node.js 22 ou superior.


### Backend
```bash
cd backend
npm install
npm start

```
A API ficará em `http://localhost:3000`.

### Frontend
Em outro terminal:
```cd frontend
npm install
npm start
# ou npm run dev

```
Abra `http://localhost:8000`.

## 6. Estrutura
```text
Projeto_Irislene_Permanencia/
├── backend/
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── app.js
│   └── package.json
├── data/
├── diagrams/
├── docs/
└── README.md
```

## 7. Modelagem resumida
**Estudantes** 1:N **Atendimentos** e **Estudantes** 1:1 **Acompanhamentos**.

Os dados pessoais são apenas demonstrativos. Para uso real, devem ser adotadas medidas de segurança, controle de acesso, minimização de dados e conformidade com a LGPD.
