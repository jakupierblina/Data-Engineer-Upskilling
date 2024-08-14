
Atributet e Dataset:
Gjinia - String - Gjinia e nxenesit
Raca/Etniciteti - String - Grupi i Races/Etnicitetit te nxenesit
Niveli_edukimit_prindit - String - Niveli i edukimit te prinderve (me i larti nga te 2)
Shujta_drekes_pakoja - String - Lloji i pakos se ushqimit ne shkolle
Kurse_parapregaditore_ekstra - String - Indikatori se a ka qene ne ndonje kurs ekstra 
Matematike - Number - Rezultati ne Matematike
Lexim - Number - Rezultati ne Lexim
Shkrim - Number - Rezultati ne Shkrim

Context:
Performance prediction
Performance of Students In Exams
Gender Prediction
Correlations between different attributes


Solution:

1. Data Preparation
   Dataset ka 8 shtylla me 1.0000 data, nuk ka null values, or noizy data.
   Dataset eshte i pastert dhe gatshem  per te perpunu interpretation dhe model prediction.
| Gjinia | Raca/Etniciteti	| Niveli_edukimit_prindit |	Shujta_drekes_pakoja	| Kurse_parapregaditore_ekstra | Matematike | Lexim | Shkrim |
| female |	group B	| bachelor's degree	 | standard	| none |	72	 | 72	| 74 |
| female |	group C |	some college |	standard |	completed |	69	| 90|	88 |
|female	|group B	|master's degree	|standard|	none|	90	|95|	93|
|male	|group A	|associate's degree	|free/reduced	|none	|47	|57	|44|
|	male	|group C|	some college |	standard|	none	|76|	78|	75|
...	...	...	...	...	...	...	...	...

3. Data interpretation
   ![Alt text](results/Comparison of Level of education based on Gender.png "Comparison of Level of education based on GenderComparison of Level of education based on Gender")

5. Model prediction
   4.1 Logistic Regression
   3.