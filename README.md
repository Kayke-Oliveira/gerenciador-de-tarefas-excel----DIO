# 📊 Gerenciador de Tarefas em Excel

Um gerenciador de tarefas simples, intuitivo e funcional desenvolvido no Microsoft Excel (2019v), projetado para otimizar o acompanhamento e a organização do fluxo de trabalho diário.

## 🎯 Por que este projeto é útil?

No dia a dia, a falta de visibilidade sobre pendências e prazos pode levar à perda de produtividade e atrasos. Este projeto resolve esse problema centralizando o controle de atividades em uma interface clara e automatizada.

Com ele, é possível:

* **Padronizar a entrada de dados**, evitando erros operacionais.

* **Priorizar demandas rapidamente** através de sinalizações visuais.

* **Acompanhar o progresso em tempo real** sem a necessidade de cálculos manuais ou softwares complexos e pagos.

## 🛠️ Recursos e Elementos Técnicos Utilizados

O projeto utiliza recursos nativos do Excel para garantir dinamismo e boa usabilidade:

* **Validação de Dados:** Aplicada na coluna de *Status* para criar uma lista suspensa padronizada (ex: *Not Started*, *In Progress*, Stuck e *Done*).

* **Formatação Condicional (Status):** Destaque de cores automático alterado conforme o estado atual da tarefa.

* **Formatação de Data (`Data Abreviada`):** Padronização visual da coluna de prazos de entrega (*Due Date*).

* **Formatação Condicional (Prioridade):** Realce visual dinâmico com base no nível de relevância/urgência registrado na coluna *Priority*.

* **Contagem Total (`CONT.VALORES`):** Cálculo automático da quantidade geral de tarefas registradas na tabela.

* **Contagem de Concluídas (`CONT.SE`):** Métrica automatizada que contabiliza quantas tarefas atingiram o status `"Done"`.

* **Cálculo de Pendências (`SOMA` + `CONT.SE`):** Fórmulas combinadas para mensurar e somar com precisão as atividades restantes.

* **Dashboard Visual (Gráfico de Rosca):** Gráfico dinâmico alimentado pelas métricas de *Atividades Concluídas* vs. *Atividades Restantes*, oferecendo uma visão geral rápida do progresso.

## 🚀 Como Utilizar

1. Faça o download do arquivo `.xlsx`.

2. Abra no Microsoft Excel ou Google Planilhas.

3. Insira suas tarefas na tabela informando nome, data de entrega, prioridade e status.

4. Acompanhe os indicadores e o gráfico atualizarem-se automaticamente à medida que você altera os dados!
