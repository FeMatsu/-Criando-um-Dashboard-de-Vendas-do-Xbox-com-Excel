# Criando-um-Dashboard-de-Vendas-do-Xbox-com-Excel


## Objetivo do Desafio

O objetivo deste desafio é criar um **dashboard de vendas** com foco na **organização e visualização de dados**. A intenção é transformar dados brutos em informações visuais claras e úteis, permitindo uma **análise eficaz do desempenho de vendas** e a **tomada de decisões baseadas em dados**.

---

## Etapas do Projeto

### P1 de negócio:  
**Qual o faturamento total de vendas de planos anuais (contendo todas as assinaturas agregadas)?**  
- Foi criada uma **tabela dinâmica** para consolidar os dados de vendas anuais de todas as assinaturas.
- A partir dessa tabela, foi gerado um **gráfico de barras** com o total de vendas.

### P2 de negócio:  
**Qual o faturamento total de vendas de planos anuais, separado por auto renovação e não é por auto renovação?**  
- A tabela dinâmica foi ajustada para segmentar as vendas por tipo de renovação.
- O gráfico gerado mostra claramente a diferença de faturamento entre as assinaturas com e sem auto renovação.

### Segmentação de Dados:  
- Foi implementado um **filtro de segmentação** de dados por tipo de assinatura (Anual, Mensal e Trimestral), possibilitando ao usuário visualizar o faturamento conforme o tipo selecionado.

### P3 de negócio:  
**Qual o total de vendas de assinaturas do EA Play?**  
- O valor total foi extraído e adicionado ao dashboard em um quadro visual, com destaque e uso da imagem (asset) do **EA Play** para melhor identificação visual.

### P4 de negócio:  
**Qual o total de vendas de assinaturas do Minecraft Season Pass?**  
- Da mesma forma, o valor foi destacado em outro quadro visual, com o uso da imagem (asset) do **Minecraft**.

---

## Descrição Visual do Dashboard

O dashboard final apresenta:

- **Período de cálculo** claramente identificado no topo: `01/01/2024 - 31/12/2024`.
- Dois quadros visuais com destaque para o **faturamento das assinaturas do EA Play (R$ 1.350,00)** e do **Minecraft Season Pass (R$ 1.800,00)**, cada um com seus respectivos logos.
- Um gráfico horizontal detalha o total de assinaturas Xbox Game Pass com auto renovação (`Yes: R$ 747,00`) e sem (`No: R$ 2.824,00`).
- Um menu lateral interativo com **filtros por tipo de assinatura**: Anual, Mensal e Trimestral.
- Interface amigável com boas práticas de organização, cores e uso de ícones/imagens.

---

## Considerações Finais

O dashboard oferece uma visão clara e segmentada do desempenho de vendas dos produtos de assinatura da Xbox, permitindo que usuários analisem os dados com rapidez e embasamento visual. Com ele, decisões de negócio podem ser tomadas com mais confiança, considerando o comportamento de compra dos usuários e os resultados financeiros de cada plano.
"""
