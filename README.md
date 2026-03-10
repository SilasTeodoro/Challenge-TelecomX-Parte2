# 📈  Challenge Telecom X Parte 2 - Alura - Análise de Churn de Clientes

##  Sobre o Projeto  
Este projeto tem como objetivo identificar clientes com alta propensão a cancelar serviços (Churn) em uma empresa de telecomunicações. É uma continuação do projeto anterior, [Challenge Telecom X](https://github.com/SilasTeodoro/Challenge-TelecomX), e busca analisar os fatores e padrões que levaram os clientes a cancelarem os serviços da TelecomX.

Através de modelos de Machine Learning, examinamos o comportamento dos usuários para propor estratégias de retenção baseadas em dados. Após uma análise aprofundada, identificaram-se padrões relevantes, como tipos de contratos e métodos de pagamento, que possivelmente influenciaram os cancelamentos.

---

# Relatório Detalhado de Análise de Churn de Clientes

# 📊 Previsão de Evasão de Clientes (Churn Prediction)

## 📈 Desempenho dos Modelos
> Comparação dos Modelos e Performance:
* Baseline (Dummy) – 73,92% acurácia | 0% recall → ponto de partida
* LinearSVC – 80,83% acurácia | 54% recall → melhor detecção
* Random Forest – 80,27% acurácia | 45% recall → robusto, sem escalonamento

> O **LinearSVC** foi capaz de identificar uma fatia maior de clientes que realmente pretendem sair.
---

## 🔍 Insights de Negócio (Feature Importance)
A análise de importância de variáveis revelou os principais gatilhos de evasão:

1. **Tipo de Contrato:** Clientes com contratos mensais (Month-to-Month) têm maior tendência a cancelar os serviços.
2. **Serviço de Internet:** Usuários de Fibra Óptica apresentam churn mais elevado, indicando possíveis questões na qualidade do serviço ou percepção de valor.
3. **Tenure (Tempo de Casa):** Novos clientes estão no período crítico nos primeiros meses.

---

## Conclusões e Insights
A análise revelou que o perfil do cliente propenso ao *churn* é complexo, mas alguns padrões claros emergiram:
*   **Duração do Contrato:** Clientes com contratos mensais são significativamente mais propensos a churnar. Contratos mais longos demonstram uma forte relação com a retenção.
*   **Serviços de Internet e Adicionais:** A "Fibra Óptica" está associada a uma alta taxa de *churn*. A ausência de serviços de segurança (Segurança Online, Backup, Proteção de Dispositivo, Suporte Técnico) aumenta drasticamente a probabilidade de *churn*.
*   **Método de Pagamento:** O "Cheque eletrônico" é um método de pagamento associado a uma alta taxa de *churn*.

---

## Ações Sugeridas para Reduzir Churn

1. **Incentivar Contratos de Longo Prazo / Fidelização**

   * Oferecer descontos progressivos ou benefícios exclusivos para clientes que optam por contratos de 1 ou 2 anos.
   * Criar programas de fidelidade que recompensem a permanência do cliente.
   * Comunicar claramente os benefícios e a economia a longo prazo de contratos estendidos.
   * Incentivar a migração de contratos mensais para anuais, com foco em retenção.

2. **Melhorar a Proposta de Valor da Fibra Óptica / Qualidade Técnica**

   * Investigar os motivos específicos de *churn* para clientes de fibra óptica (qualidade do serviço, suporte, preço).
   * Oferecer pacotes mais atraentes ou serviços adicionais gratuitos.
   * Realizar auditoria no serviço de Fibra Óptica para mitigar perdas neste setor.

3. **Monitorar Clientes com "Cheque Eletrônico"**

   * Identificar problemas com o processo de "Cheque eletrônico" ou avaliar se deve ser substituído por métodos mais estáveis e automáticos.
   * Considerar incentivar métodos de pagamento mais seguros para reduzir risco de churn.

---

## 🛠️ Tecnologias Utilizadas

* ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
* ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
* ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
* ![Seaborn](https://img.shields.io/badge/Seaborn-4D88FF?style=for-the-badge&logo=python&logoColor=white)
* ![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
* ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
* ![LinearSVC](https://img.shields.io/badge/LinearSVC-007ACC?style=for-the-badge&logo=python&logoColor=white)
* ![Random Forest](https://img.shields.io/badge/Random_Forest-4CAF50?style=for-the-badge&logo=python&logoColor=white)
* ![Dummy Classifier](https://img.shields.io/badge/Dummy_Classifier-9E9E9E?style=for-the-badge&logo=python&logoColor=white)
* ![OneHotEncoder](https://img.shields.io/badge/OneHotEncoder-FF9800?style=for-the-badge&logo=python&logoColor=white)
* ![StandardScaler](https://img.shields.io/badge/StandardScaler-673AB7?style=for-the-badge&logo=python&logoColor=white)

---

## 📂 Estrutura do Repositório

* `images/`: Gráficos gerados.
* `Challenge_TelecomX_Parte_2.ipynb`: Código completo e análises.
* `dados`: Base de dados [Dados Fictícios]

---

**Desenvolvido por:** Silas Teodoro da Silva.<br>
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SilasTeodoro)[![LinkedInd](https://img.shields.io/badge/LinkedIn-100000?style=for-the-badge&logo=github&logoColor=white)](https://www.linkedin.com/in/silas-teodoro/)
