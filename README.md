# employment-during-covid
A Python exploratory data analysis on working hours lost, labor dependency ratio, and male vs. female labor participation around the world during the Covid-19 pandemic.

# Background Information
**Job loss** is one of the many negative effects of the Covid-19 pandemic with almost every country being affected. The study of job loss during Covid-19 may reveal, not only the level of the pandemic's effect to each country, but also the varying culture of termination around the world.

**What goes into the decision of letting workers go in an economy?** According to [Business Insider](https://www.businessinsider.com/what-getting-fired-looks-like-in-different-countries-2019-7), culture plays a vital role. German companies are required to have works council - employees who represent workers in front of board of execution - to seek termination alternatives. Sweden has programs to help retrain fired employees and get them new jobs and generous unemployment benefits. In countries with long-standing tradition about job security like Japan, layoffs are even considered a social taboo.

On the other hand, the United States has been known to be more on the brutal side of the process. When American get laid off, employers give them just hours to pack their belongings and leave. There is a popular idea among US corporate culture to think of layoffs as a sign of corporate competitiveness. During the pandemic, major US-based organizations have resorted to tens of thousands of job cuts, such as Verizon Wireless, Wells Fargo, Disney, and General Motors.

How companies lay off their wokers in time of uncertainty varies from countries to countries. It can reveal workers' perceived values and corporate cultures around the world. The percentage of working hours lost is also argued to depend on other factors such as level of income.

Beside job loss, the study also aims to investigate other employment-related factors provided by the dataset, such as labor dependency ratio and male versus female employment.

# Questions for Investigation
1. What are the countries and regions with the highest and lowest percentages of working hours lost?
2. Is there a correlation between level of incomes and the rate of job loss?
3. What are the countries and regions with the highest and lowest ratio of labor dependency?
4. Is there a correlation between level of lost working hours and labor dependency ratio?
5. What are the countries and regions with the highest and lowest gender equality ratio in labor force?

# Dataset

Data obtained from [ILOSTAT](https://ilostat.ilo.org/data/#) website in cvs form. Most of the estimates are from 2020. Dataset includes information about:
- Total weekly hours worked of employed persons
- Percentage of hours lost compared to the baseline (4th quarter of 2019)
- Percentage of hours lost compared to the baseline (4th quarter of 2019) expressed in full-time equivalent employment losses. This measure is constructed by dividing the number of weekly hours lost due to COVID-19 and dividing them by 40.
- Percentage of hours lost compared to the baseline (4th quarter of 2019) expressed in full-time equivalent employment losses. This measure constructed by dividing the number of weekly hours lost due to COVID-19 and dividing them by 48.
- Ratio of dependants (persons aged 0 to 14 + persons aged 15 and above that are either outside the labour force or unemployed) to total employment.
- Employed female in 2019 who, during a specified brief period, were in one of the following categories: a) paid employment (whether at work or with a job but not at work); or b) self-employment (whether at work or with an enterprise but not at work).
- Employed male in 2019 who, during a specified brief period, were in one of the following categories: a) paid employment (whether at work or with a job but not at work); or b) self-employment (whether at work or with an enterprise but not at work).
- Ratio of total weekly hours worked to population aged 15-64.

**Learn more about the code and visualization on my Kaggle page: https://www.kaggle.com/code/vanqtran/eda-investigate-employment-during-covid.**
