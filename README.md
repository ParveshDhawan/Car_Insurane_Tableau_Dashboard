# Car_Insurane_Tableau_Dashboard
Tableau_Dashboard

Custom Field Manually Created :- 

%Claims from policies by model  =  % Claims (COUNT(IF [Claims Ind]>0 THEN [Claims Ind] END)/COUNT([Claims Ind]))
Avg cost Per claim =  SUM([Claim Amount])/COUNT(IF ([Claims Ind]>0)THEN [Claims Ind] END)
Loss Ratio  =  SUM([Claim Amount])/SUM([Premium])
Profit  =  SUM([Premium])-SUM([Claim Amount])
Profit Per policy holder = (SUM([Premium])-SUM([Claim Amount]))/COUNT([Policy Number])

![alt text](https://raw.githubusercontent.com/ParveshDhawan/Car_Insurane_Tableau_Dashboard/blob/master/Demo_Dashboard.png)

https://github.com/ParveshDhawan/Car_Insurane_Tableau_Dashboard/blob/master/Demo_Dashboard.png
https://github.com/ParveshDhawan/Car_Insurane_Tableau_Dashboard/blob/master/Demo_Dashboard.png
