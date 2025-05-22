**Análise - Melhores resultados**

Regressão Linear: R²: 0.7836 / MAE: 4181.19 / Colunas: age, bmi, smoker, children, region, sex

Polinomial (grau 2): R²: 0.8693 / MAE: 2685.34 / Colunas: age, bmi, smoker, children, region

Árvore de Decisão R²: 0.7535 / MAE: 2854.54 / Colunas: age, bmi, smoker, children, region

Random Forest R²: 0.8683 / MAE: 2470.50 / Colunas: age, bmi, smoker, children, region



     
**Regressão Linear**

- X = df[['age', 'bmi', 'smoker']]
- y = df['charges']

🔹 Regressão Linear: R²: 0.7776932310583374 MAE: 4260.560091099392

-X = df[['age', 'bmi', 'smoker', 'children']]
-y = df['charges']

🔹 Regressão Linear: R²: 0.7811147722517886 MAE: 4213.798594527246

-X = df[['age', 'bmi', 'smoker', 'children', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest']]
-y = df['charges']

🔹 Regressão Linear: R²: 0.7835569786290856 MAE: 4182.011828516012

-X = df[['age', 'bmi', 'smoker', 'children', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest', 'sex']]
-y = df['charges']

🔹 Regressão Linear: R²: 0.7835929767120724 MAE: 4181.194473753638

- X = df[['age', 'bmi', 'smoker','region_northeast', 'region_northwest', 'region_southeast', 'region_southwest', 'sex']]
- y = df['charges']

🔹 Regressão Linear: R²: 0.7800795892260536 MAE: 4222.908401655544

- X = df[['age', 'bmi', 'smoker', 'sex']]
- y = df['charges']

🔹 Regressão Linear: R²: 0.7776757765738431 MAE: 4260.991696434016

- X = df[['age', 'bmi', 'smoker', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest']]
- y = df['charges']

🔹 Regressão Linear: R²: 0.7800755882073586 MAE: 4222.996246596083

**REGRESSÃO POLINOMIAL**

- X = df[['age', 'bmi', 'smoker']] )
- y = df['charges']

🔹 Regressão Polinomial (Grau 2): R²: 0.8611724832684049 MAE: 2841.1964029834344

- X = df[['age', 'bmi', 'smoker', 'children']]
- y = df['charges']

🔹 Regressão Polinomial (Grau 2): R²: 0.8670430253632888 MAE: 2773.5716510212515

- X = df[['age', 'bmi', 'smoker', 'children', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest']]
- y = df['charges']

🔹 Regressão Polinomial (Grau 2): R²: 0.8692975322069121 MAE: 2685.3448170096553

- X = df[['age', 'bmi', 'smoker', 'children', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest', 'sex']]
- y = df['charges']

🔹 Regressão Polinomial (Grau 2): R²: 0.8665830903164846 MAE: 2729.5001336394184

- X = df[['age', 'bmi', 'smoker', 'sex']]
- y = df['charges']

🔹 Regressão Polinomial (Grau 2): R²: 0.8669441556658776 MAE: 2783.3568052029177

- X = df[['age', 'bmi', 'smoker', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest']]
- y = df['charges']

🔹 Regressão Polinomial (Grau 2): R²: 0.8634718819857696 MAE: 2774.5009453542843

**ÁRVORE DE DECISÃO**

- X = df[['age', 'bmi', 'smoker']]
- y = df['charges']

🔹 Árvore de Decisão para Regressão: R²: 0.7415009348241524 MAE: 3133.5445017126863

- X = df[['age', 'bmi', 'smoker', 'children']]
- y = df['charges']

🔹 Árvore de Decisão para Regressão: R²: 0.7057417401991726 MAE: 3114.2239903134323

- X = df[['age', 'bmi', 'smoker', 'children', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest']]
- y = df['charges']

🔹 Árvore de Decisão para Regressão: R²: 0.7534676355524017 MAE: 2854.5474588395523

- X = df[['age', 'bmi', 'smoker', 'children', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest', 'sex']]
- y = df['charges']

🔹 Árvore de Decisão para Regressão: R²: 0.6931530273154684 MAE: 3346.800375768657

- X = df[['age', 'bmi', 'smoker', 'sex']]
- y = df['charges']

🔹 Árvore de Decisão para Regressão: R²: 0.7148920902238374 MAE: 3249.5640118619403

- X = df[['age', 'bmi', 'smoker', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest']]
- y = df['charges']

🔹 Árvore de Decisão para Regressão: R²: 0.7129131727182038 MAE: 3361.141628018657

**RANDOM FOREST**

- X = df[['age', 'bmi', 'smoker']]
- y = df['charges']

🔹 Random Forest para Regressão: R²: 0.8346644445453022 MAE: 2755.556764385067

- X = df[['age', 'bmi', 'smoker', 'children']]
- y = df['charges']

🔹 Random Forest para Regressão: R²: 0.8591950981146624 MAE: 2517.3415036891884

- X = df[['age', 'bmi', 'smoker', 'children', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest']]
- y = df['charges']

🔹 Random Forest para Regressão: R²: 0.8683655116929723 MAE: 2470.5008867561573

- X = df[['age', 'bmi', 'smoker', 'children', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest', 'sex']]
- y = df['charges']

🔹 Random Forest para Regressão: R²: 0.8642420637164046 MAE: 2553.140980431126

- X = df[['age', 'bmi', 'smoker', 'sex']]
- y = df['charges']

🔹 Random Forest para Regressão: R²: 0.850458809196456 MAE: 2635.058765970476

- X = df[['age', 'bmi', 'smoker', 'region_northeast', 'region_northwest', 'region_southeast', 'region_southwest']]
- y = df['charges']

🔹 Random Forest para Regressão: R²: 0.8440732717786896 MAE: 2753.100368511072
