# Modelagem do Sistema — Permanecer+

## Atores
- Gestor escolar: consulta indicadores e acompanha casos.
- Professor/equipe pedagógica: consulta estudantes e registra ações.
- Equipe de apoio: registra atendimentos e acompanha histórico.

## Fluxo principal
1. Estudante é cadastrado.
2. Indicadores de acompanhamento são associados.
3. O sistema calcula um sinal de acompanhamento.
4. A equipe analisa o caso.
5. Uma intervenção pode ser registrada.
6. O histórico ajuda no acompanhamento posterior.

## Regras de negócio
- Frequência abaixo de 75% gera 3 pontos.
- Frequência entre 75% e 84,9% gera 2 pontos.
- Frequência entre 85% e 89,9% gera 1 ponto.
- Média abaixo de 5 gera 3 pontos; entre 5 e 6,9 gera 2; entre 7 e 7,9 gera 1.
- Participação 0–1 gera 2 pontos; 2–3 gera 1.
- 6 ou mais pontos: sinal alto; 3–5: moderado; até 2: baixo.
