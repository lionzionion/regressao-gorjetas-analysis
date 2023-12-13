# regressao-gorjetas-analysis

# Explorando a base de gorjetas

## a. Regressão de `tip` explicada por `net_bill`:

- Carrega pacotes necessários: pandas, seaborn, matplotlib, numpy e statsmodels.
- Carrega a base de dados e cria variáveis como na aula.
- Executa uma regressão de `tip` explicada por `net_bill`.

## b. Gráfico de Dispersão:

- Reproduz o gráfico de dispersão para as variáveis `tip` e `net_bill`.

# 2. Mudança de perspectiva

- Ajusta um modelo de regressão de `tip_pct` por `net_bill`.
- Constrói o gráfico de dispersão correspondente.

# 3. Comentários sobre os Gráficos e Ajuste

- Compara dois gráficos de dispersão e análise da diferença entre ajustes manuais e automáticos.
- Calcula e compara R² dos dois ajustes.

# 4. Ajuste do modelo em outra escala

- Obtém valores preditos para `tip_pct`.
- Obtém valores preditos para `tip` como `tip_pct * net_bill`.
- Calcula R² do modelo para `tip` e compara com o R² do item 1.

**Nota sobre R² no item 3:**

A comparação dos R²s no item 3 requer a definição de `r_squared_auto`, que não está disponível no código fornecido.

# Observações finais:

Este script fornece uma análise passo a passo da regressão de gorjetas, explorando diferentes perspectivas e realizando comparações entre ajustes manuais e automáticos.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para obter mais detalhes sobre os termos da licença.
