# USA-unemployment-Rate
Objective : To do time series analysis to forecast the unemployment rate of USA 

Introduction : 
Unemployment rate has been a major talking point in America’s political scenario especially since the global financial meltdown of 2008. Even though the unemployment rate has majorly been steady in the range of 3%-6%, there have been times, like the 1970s and 1980s recession and the global financial meltdown of 2008, when it rose to a staggering 7%-10%, with a peak of 10% in October ’09.  
Since then, controlled economic policies and measures have led to revival of job market. In February 2017, US economy added 235,000 jobs and have seen the unemployment rate lower down to 4.7%. However, the major talking point still remains about the unemployment rate in terms of benefits. Though policies vary by state, unemployment benefits generally pay eligible workers up to $450 per week maximum. Benefits are generally paid by state governments, funded in large part by state and federal payroll taxes levied against employers, to workers who have become unemployed through no fault of their own. United States have allocated $36 Billion unemployment benefits in budget of fiscal year 2017. Thus, ensuring that the requisite measures are taken to keep the unemployment rates under control are necessary and forecasting plays a major role in it. 
One of the greatest benefits of forecasting is that it provides the ability to manipulate the policies and other economic factors affecting the unemployment rate, so that it stays in control. Also, it helps gauge the extent of budget allocation required for the benefits.

Methodology:
In this project, we have taken month-wise unemployment rate from January 1948 till February 2017 and have tried to build a time series model to forecast the rate. 
We have used MATLAB and R to code for this project (Appendix I). We have divided the data into train and test set and then we have built a stationary model without trends and seasonality. To further evaluate the possibility of trends and seasonality, we have then built a model incorporating stochastic trends and stochastic seasonality. Also, a non-stationary time series model was developed.
Both stationary model and the non-stationary model are then used to do 20 steps ahead prediction. 
Further, we also built an ARMAV model by taking into consideration the “Labour Force Participation Rate” as the second time series. We then used the model to perform a 20 steps ahead prediction and compared it with the results observed for stationary and non-stationary models.



