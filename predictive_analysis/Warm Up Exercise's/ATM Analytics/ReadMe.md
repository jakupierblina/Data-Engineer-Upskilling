Nje sfide shume e madhe per bankat eshte menaxhimi i ATM. 
ATM perpos sfidave te sigurise kane edhe sfida logjistike; si mirembajtja dhe mbushja e tyre me te holla ne menyre qe klientet kane gjithmone 
rastin ti perdorin pa nderprerje ne asnje periudhe kohere. 
Ne datasetin e ofruar ka transaksione ne ATM qe jane realizuar pergjate nje periudhe te caktuar nje javore. <br>
Qellimi eshte te analizohen te dhenat e perdorimit te ATM dhe te nxirren informacione te ndryshme qe permes vizualizimit 
dhe nderlidhjes se atributeve, mund te ndikojne ne te gjetura kritike per menaxhimin e ATM dhe fondeve te tyre.
<br>



### Solution

From the given dataset we have only 1 City - Izmir, and we have total of 359 ATM in the given city. Total balance of money these ATMs have start from 0-57050.0 euro. While total number of transaction done in these ATMs start from 0 to 200 transaction at most in one ATM. <br>

Bellow is a table that shows summary of the data set

<table border="1">
    <tr>
        <th>atmId</th>
        <th>354</th>
    </tr>
  <tr>
        <th>atmEmri</th>
        <th>354</th>
    </tr>
<tr>
        <th>atmQyteti</th>
        <th>1</th>
    </tr>
<tr>
        <th>atmAdresa</th>
        <th>297</th>
    </tr>
<tr>
        <th>bilancitotal</th>
        <th>9560</th>
    </tr>
<tr>
        <th>numri_incoming_transactions</th>
        <th>92</th>
    </tr>

<tr>
        <th>numri_outgoing_transactions</th>
        <th>72</th>
    </tr>
<tr>
        <th>income_total</th>
        <th>1598</th>
    </tr>
<tr>
        <th>outcome_total</th>
        <th>1598</th>
    </tr>
<tr>
        <th>numri_total_transactions</th>
        <th>162</th>
    </tr>
<tr>
        <th>dita</th>
        <th>7</th>
    </tr>
<tr>
        <th>koha_transaksionit</th>
        <th>162</th>
    </tr>

</table>


<b>Conclusion: </b> 1 City, with 354 ATM in different locations in the city. Total of 9.560 transaction done in all ATMs in 7 different days of the week.

### Visualization of data  


Show most frequent day of the week to use ATMs, from visualization we can see that the day most frequent using ATMs is Tuesday where Sunday and Wednesday are the days where ATMs are not used that much.

<img src="Weekdays most frequent.png" width="700" height="550">


We wanted to also see what type of action is mostly done when using ATM, withdraw or deposit. As it can be seen visually people use it for outgoing transaction aka withdraw rather than using for depositing or incoming transaction.

<img src="Proportion of Outgoing and Incoming Transactions.png" >

In conclusion to see which days of the week are used more for incoming vs outgoing transaction, the chart bellow interprets it. We see that Withdraw or outgoing transaction is more used than depositing. Furthermore the wednesday seems to be the day where both activities have a decrease of use, while the bussiest day of the week seems to be Tuesday.

<img src="Transactions Incoming vs Outgoing per Day of the Week.png"  width="900" height="550">
