### Analysis on Sleep Health and Lifestyle 

#### Dataset: 
The dataset is taken from kaggle.
https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset
#### Dataset Overview:
The Sleep Health and Lifestyle Dataset comprises 400 rows and 13 columns, covering a wide range of
variables related to sleep and daily habits. It includes details such as gender, age, occupation, sleep
duration, quality of sleep, physical activity level, stress levels, BMI category, blood pressure, heart rate,
daily steps, and the presence or absence of sleep disorders.
With the visualizations, I tried answering the below questions:
1. How does sleep duration vary by Occupation and gender?
2. Correlation between daily steps and heart rate
3. Relationship between sleep quality and stress level
4. Relationship between Sleep duration and BMI category
5. How does sleep disorder and stress level affect sleep quality

#### Dataset Columns:
- *Person ID*: An identifier for each individual.
- *Gender*: The gender of the person (Male/Female).
- *Age*: The age of the person in years.
- *Occupation*: The occupation or profession of the person.
- *Sleep Duration (hours)*: The number of hours the person sleeps per day.
- *Quality of Sleep (scale: 1-10)*: A subjective rating of the quality of sleep, ranging from 1 to 10.
- *Physical Activity Level (minutes/day)*: The number of minutes the person engages in physical activity
daily.
- *Stress Level (scale: 1-10)*: A subjective rating of the stress level experienced by the person, ranging from
1 to 10.
- *BMI Category*: The BMI category of the person (e.g., Underweight, Normal, Overweight).
- *Blood Pressure (systolic/diastolic)*: The blood pressure measurement of the person, indicated as systolic
pressure over diastolic pressure.
- *Heart Rate (bpm)*: The resting heart rate of the person in beats per minute.
- *Daily Steps*: The number of steps the person takes per day.
- *Sleep Disorder*: The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep
Apnea).

#### Q1: How does sleep duration vary by Occupation and gender?
From the below visualization, average sleep duration for each occupation based on the gender can be
visualized.
<img width="1081" alt="Avg Sleep Duration" src="https://github.com/harikakanakam/Visualization-Sleep-Health-and-Lifestyle/assets/113376852/44a2b6b9-ac6f-45cc-b30a-d8614445382d">

##### Observations from the above visualization:
- There are only male in sales representative occupation which has the lease average sleep
duration of 5.9 hours per day.
- Engineers have the highest average sleep duration in both male and female.
- It looks like, everyone has a good average sleep regardless of occupation. In overall, no
occupation has an average sleep duration less than 5 hours per day.

#### Q2: Correlation between daily steps and heart rate
The correlation between daily steps and heart rate can be depicted from the below graph for the age
groups for 30-40, 40-50 and otherwise. Age group is categorized as <20, 20-30, 30-40, 40-50, otherwise.
<img width="1085" alt="Heart rate vs daily steps" src="https://github.com/harikakanakam/Visualization-Sleep-Health-and-Lifestyle/assets/113376852/faff81fa-7c88-4f52-a51d-5830b109acf3">

##### Observations from the above visualization:
- Only people from the age group 40-50 other than otherwise has the fulfillment of average daily
steps of 10,000.
- From the trend lines, It is observed that for the age groups 30-40 and 40-50, there is decrease in
the heart rate with increase on the steps count.

#### Q3: Relationship between sleep quality and stress level
From the below horizontal graph, the relationship between sleep quality and stress levels can be
evaluated based on the age group.
<img width="1082" alt="sleep quality change with stress level" src="https://github.com/harikakanakam/Visualization-Sleep-Health-and-Lifestyle/assets/113376852/130be64a-1377-42bf-9e9b-c6cf60496868">

Stress levels are categorized as low(0-3), medium(4-6) and high(7-10)
##### Observations from the above visualization:
- It is clear that, with high stress levels, the average sleep duration is less regardless of age group.
- It can also be inferred that, as the stress level decreases, there is an increase in the average
sleep duration.
- Hence, it is clear that with less stress levels there can be a quality sleep.

#### Q4: Relationship between Sleep duration and BMI category based on average steps count
<img width="1083" alt="Sleep duration of BMI category" src="https://github.com/harikakanakam/Visualization-Sleep-Health-and-Lifestyle/assets/113376852/99c011ed-4b9c-4a36-a00d-79f757f744f7">

##### Observations from the above visualization:
- Obese people has the least count of average steps and a average sleep duration of 6.96 hours
per day.
- All the other three categories(Normal, Normal Weight and Overweight) has a similar count of
average step count whereas overweight people have the least average sleep duration compared
to people under 3 other BMI categories.

#### Q5: How does sleep disorder and stress level affect sleep quality
 <img width="1083" alt="Persons count based on sleep disorder" src="https://github.com/harikakanakam/Visualization-Sleep-Health-and-Lifestyle/assets/113376852/f857fd95-4ee8-41f8-8355-8ee5a92e1323">

##### Observations from the above visualization:
- There are so many people with no disorder has the highest average sleep duration indicating
that sleep disorder obviously affects the quality of the sleep.
- People with sleep disorders insomnia and sleep apena has the less duration of sleep and there
are less people comparative to the people with no disorder.
