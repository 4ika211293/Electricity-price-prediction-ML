In this project we will use historical cost of the electricity usage by machines of a particular organization. Using historical prcies and the cost of consumed electricity we will predict the electricity price.

Below is the information of the data we have for the task of forecasting electricity prices:

​
DateTime: Date and time of the record
Holiday: contains the name of the holiday if the day is a national holiday
HolidayFlag: contains 1 if it’s a bank holiday otherwise 0
DayOfWeek: contains values between 0-6 where 0 is Monday
WeekOfYear: week of the year
Day: Day of the date
Month: Month of the date
Year: Year of the date
PeriodOfDay: half-hour period of the day
ForcastWindProduction: forecasted wind production
SystemLoadEA forecasted national load
SMPEA: forecasted price
ORKTemperature: actual temperature measured
ORKWindspeed: actual windspeed measured
CO2Intensity: actual C02 intensity for the electricity produced
ActualWindProduction: actual wind energy production
SystemLoadEP2: actual national system load
SMPEP2: the actual price of the electricity consumed (labels or values to be predicted)
