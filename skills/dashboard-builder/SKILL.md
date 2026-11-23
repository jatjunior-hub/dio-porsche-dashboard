---
name: dashboard-builder
description: Use quando o estudante precisa planejar, construir, revisar ou validar dashboards e painéis interativos a partir de dados estruturados.
---

# Skill: Construção e validação de dashboards

Ensine o estudante a transformar dados em dashboards claros, interativos e orientados à tomada de decisão.

## Princípio central

Um dashboard deve responder a perguntas de negócio. Não basta apresentar gráficos visualmente atraentes: cada indicador, filtro e visualização precisa ter uma finalidade clara e dados confiáveis.

## Processo

### 1. Entenda o objetivo do dashboard
Identifique o contexto do negócio, o público que utilizará o painel e as perguntas que precisam ser respondidas.

### 2. Defina indicadores e métricas
Ajude a selecionar KPIs relevantes, documentando fórmulas, critérios de inclusão, unidades de medida e eventuais limitações.

### 3. Planeje as visualizações
Escolha gráficos adequados ao tipo de informação:
- Barras para comparações e rankings.
- Linhas para evolução temporal.
- Cartões para indicadores principais.
- Tabelas para detalhamento.
- Gráficos de composição quando fizerem sentido para a pergunta.

Evite gráficos redundantes e elementos puramente decorativos.

### 4. Planeje filtros e interatividade
Identifique filtros úteis, como período, região, categoria, produto ou situação. Garanta que os filtros atualizem corretamente os indicadores e gráficos relacionados.

### 5. Defina a identidade visual
Oriente a criação de uma hierarquia visual consistente, com cores, tipografia, espaçamento, contraste e organização adequados ao contexto do projeto.

### 6. Construa o dashboard
Quando aplicável, ajude a desenvolver dashboards em HTML, CSS e JavaScript, respeitando os requisitos técnicos do projeto. Se houver exigência de arquivo único, mantenha HTML, CSS, JavaScript e dados no mesmo arquivo.

### 7. Valide os resultados
Verifique:
- Correspondência entre os dados de origem e os valores apresentados.
- Coerência dos cálculos dos KPIs.
- Funcionamento dos filtros.
- Ausência de erros no console.
- Comportamento em diferentes tamanhos de tela.
- Legibilidade e consistência das visualizações.

### 8. Prepare a entrega
Oriente a documentação do projeto, incluindo objetivo, perguntas de negócio, indicadores, tecnologias utilizadas, limitações e instruções de acesso ou publicação.

## Formato de saída

Apresente:
- Objetivo do dashboard.
- Perguntas de negócio.
- KPIs e respectivas fórmulas.
- Gráficos e justificativas.
- Filtros planejados.
- Estrutura técnica.
- Plano de validação.
- Pendências identificadas.

## Boas práticas e restrições

- Não invente dados, métricas ou resultados.
- Não apresente exemplos fictícios como resultados reais.
- Não altere a definição de um KPI sem explicar a mudança.
- Preserve a rastreabilidade dos dados utilizados.
- Respeite a privacidade e não exponha informações pessoais.
- Priorize clareza, acessibilidade e utilidade para o negócio.
- Ensine o estudante durante o processo, não apenas entregue o código.
- Conduza o estudante uma etapa por vez.

## Integração com outras skills

Quando a qualidade dos dados puder comprometer o dashboard, recomende primeiro a skill `data-treatment`.
