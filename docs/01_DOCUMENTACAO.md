# Permanecer+ — Documentação Acadêmica

**Acadêmica:** Irislene Lima Mendes  
**Tema:** Permanência e prevenção da evasão escolar  
**Tipo:** Projeto individual

## 1. Introdução
O Permanecer+ é uma aplicação para apoiar o acompanhamento de estudantes e a identificação de sinais que merecem atenção da equipe escolar. O sistema organiza informações de frequência, desempenho e registros de acompanhamento.

## 2. Problema
Informações de frequência, desempenho e atendimentos podem ficar espalhadas em registros diferentes, dificultando uma visão integrada do estudante.

## 3. Objetivo geral
Desenvolver um sistema simples para centralizar indicadores escolares e registrar ações de acompanhamento.

## 4. Objetivos específicos
- Cadastrar estudantes;
- Registrar frequência e desempenho;
- Calcular um nível de acompanhamento;
- Exibir indicadores em um dashboard;
- Registrar atendimentos;
- Consultar o histórico de acompanhamento.

## 5. Público-alvo
Gestão escolar, coordenação pedagógica, professores autorizados e equipe de acompanhamento estudantil.

## 6. Requisitos funcionais
**RF01:** cadastrar estudante.  
**RF02:** listar estudantes.  
**RF03:** calcular nível de acompanhamento.  
**RF04:** apresentar dashboard.  
**RF05:** registrar atendimento.  
**RF06:** consultar atendimentos.

## 7. Requisitos não funcionais
**RNF01:** interface responsiva.  
**RNF02:** frontend e backend comunicados por API.  
**RNF03:** armazenamento em SQLite.  
**RNF04:** código organizado.  
**RNF05:** dados de demonstração fictícios.

## 8. Regras de negócio
- **RN01:** frequência abaixo de 75% exige atenção.
- **RN02:** média abaixo de 6,0 exige atenção.
- **RN03:** indicadores podem elevar o nível de acompanhamento.
- **RN04:** o sistema não afirma que um estudante irá abandonar a escola; ele apenas auxilia no acompanhamento.
- **RN05:** atendimentos devem registrar data, estudante e responsável.

## 9. Tecnologias
HTML5, CSS3, JavaScript, Node.js, Express, SQLite e API REST.

## 10. LGPD
Os dados da demonstração são fictícios. Em uma implantação real seriam necessários controle de acesso, autenticação, autorização e medidas de proteção de dados pessoais.

## 11. Conclusão
O Permanecer+ centraliza informações escolares e registros de acompanhamento em uma ferramenta única, apoiando a análise da equipe escolar.
