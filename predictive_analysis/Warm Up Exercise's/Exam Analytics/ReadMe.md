
<br>
Ky dataset esht overview e te dhenave te nxenesve ne shkollen "XYZ". Atributed, kategorite dhe detajet rreth kesaj tabele jan me poshte.


### Atributet e Dataset:
<ul> Gjinia - Gender</ul>
<ul>Raca/Etniciteti - Nationality</ul>
<ul>Niveli_edukimit_prindit -  Parent's education level </ul>
<ul>Shujta_drekes_pakoja - Lunch break commission group</ul>
<ul>Kurse_parapregaditore_ekstra - Extra hours of preparing for exams </ul>
<ul>Matematike - Math results</ul>
<ul>Lexim - Reading results </ul>
<ul>Shkrim - Writing results</ul>

<br>
#### To Do:
<ul> Predict performance of Students In Exams </ul>
<ul> Gender Prediction </ul>
<ul> Correlations between different attributes </ul>



### Solution:

#### 1. Dataset overview <br>
   Dataset ka 8 shtylla me 1.0000 data, nuk ka null values, or noizy data.
   Dataset eshte i pastert dhe gatshem  per te perpunu interpretation dhe model prediction. <br>

<table border="1">
    <tr>
        <th>Gjinia</th>
        <th>Raca/Etniciteti</th>
        <th>Niveli_edukimit_prindit</th>
        <th>Shujta_drekes_pakoja</th>
        <th>Kurse_parapregaditore_ekstra</th>
        <th>Matematike</th>
        <th>Lexim</th>
        <th>Shkrim</th>
    </tr>
    <tr>
        <td>female</td>
        <td>group B</td>
        <td>bachelor's degree</td>
        <td>standard</td>
        <td>none</td>
        <td>72</td>
        <td>80</td>
        <td>47</td>
    </tr>
    <tr>
        <td>male</td>
        <td>group C</td>
        <td>associate's degree</td>
        <td>free</td>
        <td>none</td>
        <td>56</td>
        <td>75</td>
        <td>65</td>
    </tr>
</table>


<br><br>


#### 2. Data interpretation <br> 

  Vizualizimi me poshte interpreton te dhenat e nivelit te edukimint ne baze te gjinise. Ashtu si duket ne vizualizim vajzat e shkolles "XYZ" kane prinderit me te shkolluar sesa djemt e po kesaj shkolle.  <br><br>

<img src="results/Comparison of Level of education based on Gender.png" width="700" height="500">


Ndersa ne vizualizimin e dyte eshte ne detaje krahasimi per 3 kategorite: Lexim, Shkrim dhe Matematike per dy gjinite se kush ka me shume pike ne keto teste. Mund te aludojme se ky rezultat i gjinise femrore te dominoje ne 3 kategorite dhe te jene me te sukseshme mund te vje edhe nga niveli i edukimit te prindit, shfaqur ne grafitin me larte. <br><br>

  <img src="results/show who is better in Math, Reading and Writing - females or males.png">

<br><br><br>

### Predict performance of Students In Exams 

We want to predict the performance of students for particular exam like Math. Using Linear Regression we will see how this prediction performs. Results F2 score : 0.923688173679362 which means is closer to 1 therefore means we have a nice model.
<br>
<img src="results/Linear_Regression_performance prediction of students.png" width="700" height="500">


### Predict Gender 

Logistic Regression performed Accuracy: 92%.This suggests that the model is performing well in predicting the gender-based performance of students. We have two classes 1: male, 0 female.

Class-specific performance: <br>
<b>Class 0:</b> With a precision of 0.90 and a recall of 0.93, the model performs well in identifying and predicting this class correctly. <br>
<b>Class 1:</b> With a precision of 0.93 and a recall of 0.90, the model is slightly better at identifying this class when it predicts it, but slightly less sensitive compared to class 0. <br>

<br>
<img src="results/ Confusion Matrix for Gender.png" width="700" height="500">


###  Correlation of dataframe

We see that the dataset have a nice correlation where strongest correlation is between Gjinia and Edukimi  i prindit. Weak corelation are the values close to 0 -- that means no correlation or no linear relationship such as Matematike, Lexim and Shkrim.

<img src="results/Correlation of dataframe - pearson.png" width="700" height="500">

