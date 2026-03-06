# 🕵️ Projeto de Testes e Qualidade de Software

Bem-vindo ao repositório oficial do **Projeto de Testes e Qualidade de Software**! Este projeto foi desenvolvido com o objetivo de documentar e apresentar, de forma clara e estruturada, os resultados de uma análise de qualidade realizada em aplicações web. Aqui você encontrará um estudo de caso completo, com a aplicação de conceitos de testes manuais, categorização de bugs e sugestões de melhorias, baseado em materiais de referência e sites especialmente preparados para avaliação.

## Sobre o Projeto

Este repositório serve como um portfólio de habilidades em **Garantia da Qualidade (QA)**. O foco principal é demonstrar a capacidade de analisar sistemas, identificar falhas, oportunidades de melhoria e novas funcionalidades, classificando-as e priorizando-as de acordo com o impacto na experiência do usuário e na funcionalidade do sistema.

A abordagem utilizada é o Behavior Driven Development (BDD) com a linguagem Gherkin, permitindo que os cenários sejam escritos de forma clara e acessível para todos os envolvidos no projeto (devs, QA's, PO's, etc.).

## Conceitos Aplicados

Para garantir uma análise padronizada e de alta qualidade, utilizei as seguintes classificações para cada item reportado:

### **TIPO**
*   **Correção:** Itens que exigem reparo para que a aplicação funcione normalmente.
*   **Nova funcionalidade:** Demandas para desenvolvimento de novos recursos que otimizem a experiência do usuário.
*   **Melhoria:** Otimizações para aprimorar a usabilidade e a experiência geral com a aplicação.

### **CLASSIFICAÇÃO**
*   **Utilidade:** Erros que **impedem** o usuário de realizar as tarefas propostas. Devem ser priorizados.
    *   *Exemplo:* Erros de servidor, falhas ao clicar em botões.
*   **Usabilidade:** Problemas que **dificultam ou atrapalham** a execução de funções, mas não as impedem.
    *   *Exemplo:* Falta de instruções claras, botões que funcionam apenas no segundo clique.
*   **Desejabilidade:** Oportunidades para tornar a aplicação mais intuitiva, rápida e fácil de usar, frequentemente relacionadas à experiência do usuário (UX).
    *   *Exemplo:* Melhorias visuais, de alinhamento ou sugestões que superem as expectativas.

### **PRIORIDADE**
*   **🟢 Baixa:** Pequenas falhas ou oportunidades que contribuem para o aprimoramento, mas podem ser tratadas por último.
*   **🟡 Média:** Erros e inconsistências que comprometem significativamente a usabilidade ou itens que não atendem completamente às expectativas.
*   **🔴 Alta:** Itens mais urgentes, relacionados a erros que **impedem** o usuário de realizar suas tarefas.

## 🌐 Sites Analisados

A análise foi conduzida nos seguintes ambientes de teste:

1.  **Certificação:** [https://qualidade.apprbs.com.br/certificacao](https://qualidade.apprbs.com.br/certificacao)
2.  **Site:** [https://qualidade.apprbs.com.br/site](https://qualidade.apprbs.com.br/site)

## 📝 Estrutura do Relatório de Itens

Cada item encontrado durante os testes foi documentado seguindo o formato abaixo, para facilitar a identificação e o trabalho dos desenvolvedores:

```markdown
**Item [Número] – [Título Descritivo]**
**Tipo:** [Correção | Nova funcionalidade | Melhoria]
**Classificação:** [Utilidade | Usabilidade | Desejabilidade]
**Prioridade:** [Alta | Média | Baixa]

**Descrição:** [Descrição detalhada do problema, funcionalidade ou melhoria sugerida.]
