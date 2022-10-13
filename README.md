# I Want to Work From Home!!!

I graduated with my bachelors degree in spring of 2019. Since the Coronavirus pandemic shut down offices across the country less than a year later, I have spent most of my career working remotely. Therefore, the anticipated return to the office, often referred to as the “return to normal”, actually isn’t normal to me at all. The ability to continue to work remotely is very important to me. Therefore, I set out to see what the data says about how remote work impacts data science salaries, if the ability to work remotely is influenced by experience level, or if the ability to work remotely is influenced by company size.

To explore these questions, I found a data set on Kaggle entitled ‘Data Science Job Salaries’. This data set contained 607 records and 19 attributes. For this analysis we will focus on the following attributes: experience_level, salary_in_usd, remote_ratio, and company_size.

### Q1 - How is salary impacted by remote ratio?

While working remotely is important to me, I do not want it to be at the expense of my salary. Therefore, the first question I asked was does the amount of remote work impact a data scientist's salary. 

The Kaggle dataset divides the records into 3 categories of remote work. 
- No Remote Work (less than 20%)
- Partial Remote Work (20 - 80%)
- Full Remote (more than 80%)

<p align="center">
<img width="800" alt="SalaryComparison" src="https://user-images.githubusercontent.com/78283026/195484670-865df1ef-1ed9-4a3d-89d4-55cbd2969d8b.png"></br>
Figure 1 - Remote Work Salary Comparison
</p>

I found the mean and the median salary for the entire dataset and for each of the remote work categories. The mean salary for the entire dataset is $112,298, while the median is $101,570. The fact that the mean salary of the data set is higher than the median salary indicates that there are high-earners within the dataset that are driving the mean up. 

The mean and median of the No Remote Work category are almost identical to the mean and median of the dataset (see Figure 1 above). However, the mean and median salary for the Partial Remote Work category is significantly lower than the mean and median salary of the dataset. And the mean and median salary of the Full Remote category is slightly higher. Therefore, salary-wise I should benefit from working fully remotely according to this data.

### Q2 - How is remote ratio impacted by experience level?

Next, I wanted to know if there are points in my career where I am more likely to work remotely based on my level of experience. 

The kaggle dataset breaks experience down into 4 levels:
- EN - Entry Level/Junior
- MI - Mid Level/Intermediate
- SE - Senior Level/Expert
- EX - Executive Level/Director

<p align="center">
<img width="800" alt="ExperienceLevel" src="https://user-images.githubusercontent.com/78283026/195485941-669125d9-4b74-4442-a52e-161056b18f83.png"></br>
Figure 2 - Remote Work based on Experience Level
</p>

As can be seen in figure 2, a majority of data scientists work fully remote at every experience level. 56% of Entry Level data scientists work fully remote. That number goes up to 71% once a data scientist reaches Senior Level.

### Q3 - How is remote ratio impacted by company size?

The last question was if I could increase my chances of working remotely based on the size of the company I work for.

The kaggle dataset categorized company size using the following criteria:
S - <50 employees
M - 50-250 employees
L - >250 employees

<p align="center">
<img width="800" alt="CompanySize" src="https://user-images.githubusercontent.com/78283026/195487610-4af97199-acb6-4500-bbc6-b65e03ef9953.png">
</br> Figure 3 - Remote Work based on Company Size
</p>

As can be seen in Figure 3, more than 50% of data scientists worked fully remotely at all sizes of companies. The small and large companies mirrored each other across all three remote categories. However, medium sized companies were significantly less likely to have employees working partially remote with only 6%. Comparatively, large and small companies have 30% and 22% of employees working partially remote respectively.

### Conclusion
Overall, it appears that the data scientist career path should not hinder my ability to work remotely in the future. According to this analysis, I will not need to compromise my earning potential in order to work remotely. As I advance in my career, the potential to work remotely increases, and I will not need to filter my job hunt for a certain sized company. The future looks bright for remote work!
