## Pré Análise - Curingas Balatro

## Informações Gerais do Dataset

- Total de curingas: 150
- Distribuição por raridade:
  - Incomum: 85 curingas (56.7%)
  - Comum: 60 curingas (40%)
  - Lendário: 5 curingas (3.3%)

## Análise de Preço Base
  - Estatísticas de preço:
    - Média: 333.374 (inflacionada pelos Lendários)
    - Mediana: 5.0
    - Mínimo: 0.0
    - Máximo: 9.999.999
    - 75% dos curingas têm preço base de 6.0 ou menos

- Requisitos de Desbloqueio
  - Observações importantes:
    - A maioria dos curingas (105 de 150, ou 70%) está "Disponível desde o início"
    - Os 5 curingas Lendários são obtidos através da "Carta Espectral da Alma"
    - Existe uma grande variedade de requisitos especiais para os demais curingas (40 requisitos diferentes)

## Análise do Efeito dos Curingas
  - Todos os curingas têm efeitos únicos (150 efeitos únicos para 150 curingas)
  - O efeito mais básico (+4 Mult) está presente no curinga "Joker" comum

# Análise dos Testes de Hipóteses - Jogo Balatro

Com base nos testes estatísticos apresentados, posso definir as seguintes conclusões sobre os curingas (Jokers) do jogo Balatro:

## 1. Relação entre Raridade e Preço Base

- **Conclusão principal**: A raridade dos curingas influencia diretamente seu preço base, com diferenças estatisticamente significativas (p-value = 0.0000).
- **Detalhamento das diferenças**:
  - Curingas Lendários têm preço base drasticamente maior (aproximadamente 10 milhões) comparado aos demais
  - Não existe diferença estatisticamente significativa entre curingas Comuns e Incomuns (p-adj = 0.8281)
  - A hierarquia de preços é: Lendário >> Incomum ≈ Comum

## 2. Influência do Requisito de Desbloqueio no Preço

- **Conclusão principal**: Existe uma relação significativa entre os requisitos de desbloqueio e os preços base (p-value = 0.0000).
- **Observações relevantes**:
  - O requisito "Obtido usando a Carta Espectral da Alma" está diretamente associado aos curingas de maior valor (9.999.999)
  - Requisitos como "Ganhe uma corrida" e "Ganhe uma corrida em 18 rodadas ou menos" estão associados a preços intermediários (8-10)
  - Muitos requisitos de desbloqueio estão associados a curingas de custo zero

## 3. Distribuição de Curingas por Raridade

- **Conclusão principal**: A distribuição de curingas entre as raridades não é uniforme (p-value = 0.0000).
- **Proporção observada**:
  - Incomuns: 85 curingas (57%)
  - Comuns: 60 curingas (40%)
  - Lendários: 5 curingas (3%)
 
## 4. Análise dos Clusters
A análise de clusters revela quatro grupos distintos de curingas:

- Cluster 0 (60 curingas):
  - Todos são de raridade Comum
  - Preço base médio: 4.07
  - Inclui curingas como "Joker", "Coringa ganancioso", "Cartões de Crédito"

- Cluster 1 (5 curingas):
  - Todos são de raridade Lendária
  - Preço base médio: 9.999.999
  - Incluem "Canio", "Tribuuleto", "Yorick", "Chicot" e "Perkeo"

- Cluster 2 (57 curingas):
  - Todos são de raridade Incomum
  - Preço base médio: 6.44
  - Incluem "Estêncil do Coringa", "Quatro dedos", "Cartão de fidelidade"

- Cluster 3 (28 curingas):
  - Todos são de raridade Incomum
  - Preço base médio: 2.00
  - Incluem "Adaga Cerimonial", "Coringa de Aço", "Hack"
 
## Conclusões Finais

- O jogo Balatro implementa um sistema de raridade que afeta significativamente o valor dos curingas, com os Lendários sendo extremamente valiosos.
- Os requisitos de desbloqueio estão correlacionados com o valor dos curingas, sugerindo que curingas mais difíceis de obter tendem a ter maior valor.
- A distribuição de curingas é intencionalmente desbalanceada, com uma proporção muito menor de curingas Lendários.
- Existe uma clara segmentação de curingas em grupos distintos, com o Cluster 3 representando um subgrupo de curingas Incomuns que, apesar de sua raridade, têm preço base zero.
