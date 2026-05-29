<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<div align="center">

</div>

# Planejamento das Sprints

<details>
<summary>Sprint 1</summary>



## User Stories da Sprint

| Rank | Prioridade | ID | User Story | Estimativa | Sprint | Requisito do parceiro |
|------|------------|----|------------|------------|--------|-----------------------|
| 1 | ALTA | US-1 | Como cliente, quero visualizar uma visão geral dos setores econômicos com base na RAIS para entender quais segmentos estão em destaque | 5 | 1 | RF01, RNF02, RNF06 |
| 2 | ALTA | US-4 | Como cliente, quero filtrar os dados pelo ano de 2024 para analisar  | 7 | 1 | RF04, RNF05 |
| 3 | MÉDIA | US-7 | Como cliente, quero visualizar dados por região (UF e município) para entender a distribuição geográfica na região | 5 | 1 | RF07, RNF04 |
| 4 | MÉDIA | US-8 | Como cliente, quero visualizar gráficos claros e interativos para facilitar a interpretação dos dados | 3 | 1 | RF08, RNF02 |

### Requisitos
- RF01 → Visão geral dos setores
- RF04 → Filtro por ano
- RF07 → Visualização por região
- RF08 → Gráficos interativos
- RNF02 → Usabilidade
- RNF04 → Volume de dados
- RNF05 → Atualização de dados
- RNF06 → Clareza visual

### Definition of ready: 
- User story claramente definido, incluindo critérios de aceitação.
- Tarefas definidas, atribuidas e relacionadas às User Stories
- A user story foi estimada e priorizada corretamente na sprint.
- Houver entendimento de quais visuais serão utilizados
- Os dados necessários da RAIS estiverem identificados
- A fonte de dados estiver acessível e validada

### Definition of done: 
- Os dados da RAIS estiverem carregados, tratados e filtrados corretamente
- O dashboard no Power BI apresentar:
  US-1,US-4,US-7,US-8
-Os gráficos estiverem legíveis, organizados e com títulos claros
-Os filtros estiverem funcionando corretamente (sem quebra de dados)
-A navegação e interação do usuário estiverem intuitivas

---

### Burndown<br>
<img width="1484" height="729" alt="image" src="https://github.com/user-attachments/assets/0f0b54b2-f817-41ef-9d91-fa7a0677aa8c" />
<br>

### Video de demonstração Sprint 1

[Video sobre consulta feita pelo BigQuery](https://youtu.be/zopgMaqeDP4)

[Codigo usado no SQL](https://github.com/Icarus-Lab-s/Mapeamento-do-Ecossistema-Industrial-Regional/blob/main/documentation/assets/SQL%20UTILIZADO%20PARA%20CONSULTA.sql)

[Apresentação do PowerBI](https://youtu.be/Vb84qCSkiZw)
    
## [MVP SPRINT 1](https://github.com/Icarus-Lab-s/Mapeamento-do-Ecossistema-Industrial-Regional/blob/main/MVP/SPRINT%201/SP1.md)
📝 Acima segue a entrega do MPV da primeira sprint

---

</details>

<details>
<summary>Sprint 2</summary>



## User Stories da Sprint

| Rank | Prioridade | ID | User Story | Estimativa | Sprint | Requisito do parceiro |
|------|------------|----|------------|------------|--------|-----------------------|
| 5 | ALTA | US-2 | Como cliente, quero comparar os setores econômicos para identificar quais possuem maior volume de vínculos empregatícios | 5 | 2 | RF02, RNF01 |
| 6 | ALTA | US-3 | Como cliente, quero visualizar indicadores de emprego por setor para apoiar análises estratégicas  | 5 | 2 | RF03, RNF03 |
| 7 | ALTA | US-5 | Como cliente, gostaria de visualizar em uma segunda tela focada no setor aeronáutico para aprofundar a análise | 5 | 2 | RF05, RNF06 |


### Requisitos
- RF02 → Comparação entre setores econômicos
- RF03 → Indicadores de emprego por setor
- RF05 → Análise específica do setor aeronáutico
- RNF01 → Boa performance na exibição dos dados
- RNF03 → Dados confiáveis e consistentes
- RNF05 → Deve permitir atualização dos dados

### Definition of Ready
- User story claramente definido, incluindo critérios de aceitação.
- Tarefas definidas, atribuidas e relacionadas às User Stories
- A user story foi estimada e priorizada corretamente na sprint.
- Dados de pesquisa apurados
- Visuais faceis de entender

### Definition of done: 
- Perguntas respondidas adequadamente
- O dashboard no Power BI apresentar:
  US-2,US-3,US-5
- Tela da área aeronáutica informativa
-Os filtros estiverem funcionando corretamente (sem quebra de dados)
-A navegação e interação do usuário estiverem intuitivas

---

### Burndown<br>
<img width="1560" height="411" alt="image" src="https://github.com/user-attachments/assets/734fc4b8-6758-4ec8-b6c9-b89c83da8b5f" />

---

## [MVP SPRINT 2](https://github.com/Icarus-Lab-s/Mapeamento-do-Ecossistema-Industrial-Regional/blob/main/MVP/SPRINT%202/SP2.md)
📝 Acima segue a entrega do MPV da segunda sprint

---

</details>

<details>
<summary>Sprint 3</summary>

## User Stories da Sprint

| Rank | Prioridade | ID | User Story | Estimativa | Sprint | Requisito do parceiro |
|------|------------|----|------------|------------|--------|-----------------------|
| 6 | ALTA | US-6 | Como cliente, quero analisar o desempenho do setor aeronáutico em relação aos demais setores | 5 | 3 | RF06, RNF01|
| 9 | MÉDIA | US-9 | Como cliente, quero identificar tendências e padrões nos dados de emprego para apoiar decisões | 5 | 3 | RF03, RNF03|
| 10 | BAIXA | US-10 | Como cliente, quero navegar entre diferentes telas do dashboard para explorar os dados de forma intuitiva | 2 | 3 | RF09, RNF02 |

### Requisitos
- RF03 →  apresentar indicadores de emprego por setor
- RF06 →  permitir a comparação do setor aeronáutico com outros setores
- RF09 →  permitir navegação entre diferentes telas
- RNF01 → boa performance na exibição dos dados
- RNF02 → ser intuitivo e de fácil utilização
- RNF03 → Os dados apresentados devem ser confiáveis e consistentes

### Definition of ready: 
- User story claramente definido, incluindo critérios de aceitação.
- Tarefas definidas, atribuidas e relacionadas às User Stories
- A user story foi estimada e priorizada corretamente na sprint.
- Houver entendimento de quais visuais serão utilizados
- Os dados necessários da RAIS estiverem identificados
- A fonte de dados estiver acessível e validada


### Definition of done: 
- Perguntas respondidas adequadamente
- O dashboard no Power BI apresentar:
  US-6,US-9,US-10
- Tela da área aeronáutica informativa
- Dados concretos e sem erros
- A navegação e interação do usuário estiverem intuitivas
- Pesquisa de setor apurada
  
</body>
</html>
