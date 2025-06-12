# 📘 Respostas da Atividade 1

## 1️⃣ O que é Machine Learning?

**Machine Learning** é um ramo da inteligência artificial que permite que os computadores aprendam com dados sem serem programados explicitamente para cada tarefa.

---

## 2️⃣ O que são conjunto de treinamento, validação e teste?

Em Machine Learning, os dados geralmente são divididos em três partes:

- **Conjunto de Treinamento**: usado para ensinar o modelo a identificar padrões nos dados.
- **Conjunto de Validação**: É usado para melhorar o desempenho do modelo, ajudando ele a aprender bem sem decorar os dados, o que evita erros quando for usado com novos dados.
- **Conjunto de Teste**: usado para avaliar a performance do modelo em dados nunca vistos antes.

---

## 3️⃣Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.
Eu utilizaria algumas dessas estratégias:
- **Removeria** linhas ou colunas com dados ausentes, se forem poucos casos, analisando obviamente se isso causaria algum impacto significativo e levando em consideração o contexto.
- **Preencheria** os valores com 0 ou alguma medida estatística como média, mediana ou moda. Após fazer uma análise minuciosa dos dados, analisar outliers, entender a melhor opção a ser utilizada, sempre de acordo com o contexto. No caso de uma variável categórica, uma outra opção seria criar uma nova categoria, como por exemplo "não informado" ou "outro".
- Utilizar técnicas mais sofisticadas de **imputação**, como algoritmos que estimam os valores ausentes com base nos demais dados.

---

## 4️⃣ O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo? 

A **matriz de confusão** é uma tabela que mostra os acertos e erros de um modelo de classificação.. Ela mostra:

- Verdadeiros Positivos (VP)
- Falsos Positivos (FP)
- Verdadeiros Negativos (VN)
- Falsos Negativos (FN)

**Métricas calculadas:**

- Acurácia: % de predições corretas do total
- Precisão: dos casos que o modelo disse "sim", quantos eram realmente "sim"
- Recall: dos casos que eram realmente "sim", quantos o modelo identificou
- F1-score: média harmônica entre precisão e recall

---

## 5️⃣ Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos de machine learning?
Acho que pra mim, as áreas mais interessantes para aplicar machine learning são **saúde, meio ambiente, educação e justiça social.**
- Na **saúde**, posso ajudar no diagnóstico precoce de doenças, desenvolvimento de tratamentos personalizados e análise de exames médicos.
- No **meio ambiente**, consigo contribuir com monitoramento de desmatamento, previsão de mudanças climáticas e otimização do uso de recursos naturais. Além de mapeamento de áreas de risco para desastres naturais (o que também abrange uma causa **social**)
- Na **educação** daria pra contribuir com sistemas adaptativos que personalizam o aprendizado, identificam alunos em risco de evasão e democratizam acesso ao ensino de qualidade.
- Para **proteção às minorias**, vejo potencial em detectar e combater discriminação algorítmica, melhorar acesso a serviços públicos e identificar padrões de desigualdade social. Daria também pra auxiliar no combate à **fome e insegurança alimentar**  através de previsão de safras e escassez de alimentos, otimização de distribuição em bancos de alimentos e identificação de comunidades em risco nutricional.
Enfim, muitas e muitas coisas! Essas áreas me motivam demais porque são aplicações que podem genuinamente melhorar vidas e tornar o mundo mais justo e sustentável.
