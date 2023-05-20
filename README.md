Introduction:
**Life expectancy**
Life expectancy stands for an average life span a person is expected to live in a given set of conditions It depends on several factors which include social, economical, political and geographical conditions In the given dataset too we are intended to answer the given questions and building a model which will predict life expectancy by given set of inputs.

**Shape of the dataset:**
-	There are 22 columns and 2938 rows in our dataset

**Information of the data:**
#   Column                           Non-Null Count  Dtype  
---  ------                           --------------  -----  
 0   Country                          2938 non-null   object 
 1   Year                             2938 non-null   int64  
 2   Status                           2938 non-null   object 
 3   Life expectancy                  2928 non-null   float64
 4   Adult Mortality                  2928 non-null   float64
 5   infant deaths                    2938 non-null   int64  
 6   Alcohol                          2744 non-null   float64
 7   percentage expenditure           2938 non-null   float64
 8   Hepatitis B                      2385 non-null   float64
 9   Measles                          2938 non-null   int64  
 10  BMI                              2904 non-null   float64
 11  Under-five deaths                2938 non-null   int64  
 12  Polio                            2919 non-null   float64
 13  Total expenditure                2712 non-null   float64
 14  Diphtheria                       2919 non-null   float64
 15  HIV/AIDS                         2938 non-null   float64
 16  GDP                              2490 non-null   float64
 17  Population                       2286 non-null   float64
 18  Thinness  10-19 years            2904 non-null   float64
 19  Thinness 5-9 years               2904 non-null   float64
 20  Income composition of resources  2771 non-null   float64
 21  Schooling                        2775 non-null   float64


**Columns detail:**
1.	Country: Total 193 countries are there in our dataset,
2.	Year: Year in which life expectancy is calculated, 
3.	Status: Economic status of a country whether developed or developing, 
4.	Life expectancy: This is our target column, which tells average years people remain alive in that country,
5.	Adult Mortality: The probability that those who have reached age 15 will die before reaching age 60,
6.	Infant deaths: The number of deaths of infants per thousand before they complete 1 year of age,
7.	Measles: A viral infection that is serious for small children but easily preventable by a vaccine.
8.	BMI: It measures body fat based on height and weight,
9.	Under-five deaths: Deaths of children per thousand before they could complete 5 years of age,
10.	Polio: A viral disease which can cause paralysis,
11.	Total expenditure: Amount of money spent by the government on healthcare,
12.	Diphtheria: Serious infection of the nose and throat,
13.	HIV/AIDS: AIDS is a chronic immune system disease caused by Human Immunodeficiency Virus,
14.	GDP: Total value of all the goods and services produced in a country in one year,
15.	Population: Whole number of inhabitants residing in a particular country,
16.	Thinness  5-19 years: Thin population because of Malnutrition
17.	Income composition of resources: Measures how good a country is at utilizing its resources,
18.	Schooling: Number of people enrolled for education in school.

**Questions to be answered: **
1.	Does various predicting factors which has been chosen initially really affect Life expectancy? What are the predicting variables actually affecting life expectancy?
2.	Should a country having a lower life expectancy value(<65) increase its healthcare expenditure in order to improve its average lifespan?
3.	How do Infant and Adult mortality rates affect life expectancy?
4.	Does Life Expectancy has a positive or negative correlation with eating habits, lifestyle, exercise, smoking, drinking alcohol etc?
5.	What is the impact of schooling on the lifespan of humans?
6.	Does Life Expectancy have a positive or negative relationship with drinking alcohol?
7.	Do densely populated countries tend to have lower life expectancy?
8.	What is the impact of Immunization coverage on Life Expectancy?


