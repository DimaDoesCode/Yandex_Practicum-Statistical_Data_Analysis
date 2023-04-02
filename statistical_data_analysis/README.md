# Statistical Data Analysis
## Data
The following data is available:<br>
Table users - information about users:
<pre> -user_id - unique user identifier
 -first_name - user's first name
 -last_name - user's last name
 -age - user's age (years)
 -reg_date - date of tariff activation (day, month, year)
 -churn_date - date of tariff cancellation (if the value is missing, the tariff was still active at the time of data extraction)
 -city - user's city of residence
 -tarif - name of the tariff plan</pre>
Table calls - information about calls:
<pre> -id - unique call number
 -call_date - date of the call
 -duration - duration of the call in minutes
 -user_id - identifier of the user who made the call</pre>
Table messages - information about messages:
<pre> -id - unique message number
 -message_date - date of the message
 -user_id - identifier of the user who sent the message</pre>
Table internet - information about internet sessions:
<pre> -id - unique session number
 -mb_used - volume of internet traffic used during the session (in megabytes)
 -session_date - date of the internet session
 -user_id - user identifier</pre>
Table tariffs - information about tariffs:
<pre> -tariff_name - tariff name
 -rub_monthly_fee - monthly subscription fee in rubles
 -minutes_included - number of included minutes of talk time per month
 -messages_included - number of included messages per month
 -mb_per_month_included - volume of included internet traffic per month (in megabytes)
 -rub_per_minute - cost of an additional minute of talk time beyond the tariff package
 -rub_per_message - cost of sending a message beyond the tariff package
 -rub_per_gb - cost of an additional gigabyte of internet traffic beyond the tariff package</pre>

## Task
Preliminary analysis of tariffs on a small sample of clients.

<a href="https://github.com/DimaDoesCode/Yandex_Practicum-Statistical_Data_Analysis/blob/master/statistical_data_analysis/Project%20Statistical%20data%20analysis.ipynb">To view the Jupyter Notebook code of the research, click on this link.</a>

## Libraries used
<i>pandas, numpy, seaborn, matplotlib.pyplot, scipy</i>