# Expenditure in Indian Prisons

<title>Expenditure in Indian Prisons</title>

For this assignment, I took the <a href="https://www.kaggle.com/rajanand/prison-in-india">Prison Statistics</a> for the year 2010, and looked at prison expenditure in particular. I used Tableau to generate graphs.

There is no dearth of articles about the dismal condition of Indian prisons. Every year, they become more overcrowded. There is a trivial correlation between number of inmates and total expenditure, ie the more the inmates, the more the expenditure. But how much money are states spending on each inmate?

<script type='text/javascript' src='https://dub01.online.tableau.com/javascripts/api/viz_v1.js'></script><div class='tableauPlaceholder' style='width: 860px; height: 709px;'><object class='tableauViz' width='860' height='709' style='display:none;'><param name='host_url' value='https%3A%2F%2Fdub01.online.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='&#47;t&#47;shivangistableau' /><param name='name' value='ExpenditureinIndianPrisons&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='showAppBanner' value='false' /><param name='filter' value='iframeSizedToWindow=true' /></object></div><br>

The smaller, northeastern states feature in the top 10 states by expenditure per inmate. Delhi, strangely, places second on this list. However, most of Delhi’s expenditure falls under the mysterious category of “Other expenditure related to inmates only”. <br><br>

<script type='text/javascript' src='https://dub01.online.tableau.com/javascripts/api/viz_v1.js'></script><div class='tableauPlaceholder' style='width: 860px; height: 709px;'><object class='tableauViz' width='860' height='709' style='display:none;'><param name='host_url' value='https%3A%2F%2Fdub01.online.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='&#47;t&#47;shivangistableau' /><param name='name' value='ExpenditureinIndianPrisons&#47;Sheet12' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='showAppBanner' value='false' /><param name='filter' value='iframeSizedToWindow=true' /></object></div><br>

When this category is excluded, Delhi moves further down the list. The other states remain more or less the same.

Is there anything common between these states? I thought there was a possibility that <u>states that have prisons with low occupancy spend more on each inmate</u>.<br><br>

<script type='text/javascript' src='https://dub01.online.tableau.com/javascripts/api/viz_v1.js'></script><div class='tableauPlaceholder' style='width: 860px; height: 709px;'><object class='tableauViz' width='860' height='709' style='display:none;'><param name='host_url' value='https%3A%2F%2Fdub01.online.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='&#47;t&#47;shivangistableau' /><param name='name' value='ExpenditureinIndianPrisons&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='showAppBanner' value='false' /><param name='filter' value='iframeSizedToWindow=true' /></object></div><br>

The chart showing the 10 states with lowest occupancy seems to support this hypothesis. Many states that featured in the high expenditure graph, also appear here. <br><br>

<script type='text/javascript' src='https://dub01.online.tableau.com/javascripts/api/viz_v1.js'></script><div class='tableauPlaceholder' style='width: 860px; height: 709px;'><object class='tableauViz' width='860' height='709' style='display:none;'><param name='host_url' value='https%3A%2F%2Fdub01.online.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='&#47;t&#47;shivangistableau' /><param name='name' value='ExpenditureinIndianPrisons&#47;Sheet32' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='showAppBanner' value='false' /><param name='filter' value='iframeSizedToWindow=true' /></object></div><br>

Plotting the occupancy percentages of high expenditure states makes it clear that <u>there is a correlation between the two factors</u>. In the above graph, 6 out of 10 states are also states with lowest prison occupancy, and the occupancy percentage of 8 states is equal to or less than 100%.


