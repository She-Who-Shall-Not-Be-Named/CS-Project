# CS-Project- Chicago Public Schools - Progress Report Cards
Project 2
Authors:
Alicia Isler , Mackenzie Eng 


Data set: https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t

Questions (Mackenzie):

Is there a correlation between the “location” (school safety score and environment score) and student attendance?

Why did you ask this question? Was there any information you wanted to learn?

I asked this question because I had an interesting discussion with a teacher I worked with. He talked about how he used to work in a school that was poorly situated to the point where he had to clean drug needles from the front of the school every morning. I wanted to know if students were more likely to come to school if the location was safe and had a supportive community. 

Did you succeed in answering the question? If you did succeed, what did you learn? If you weren’t successful, can you propose a method which might help
 solve the question (i.e. different data, or using a different tool than SQL etc.)?
 
I didn’t really succeed in answering the question. I learned that schools that had low average student attendance were sometimes less safe and ranked low in terms of having a supportive community but this wasn’t always the case. I would more data about where the students live to determine if that affects student attendance.

Which SQL tool(s) did you use to solve the question (i.e. aggregates, joins, cases etc.)?

		I used ORDER BY and ASC.
    
Which ZIP codes have the lowest average school safety scores and the lowest environment scores?

Why did you ask this question? Was there any information you wanted to learn?

I asked this question because at the school I worked at, we also talked about how school zoning can be harmful. Some of these schools can be good but struggle to succeed because of the neighborhood around the school, which may have gang activity or drug use. I wanted to know which of these ZIP codes were considered “bad neighborhoods”.

Did you succeed in answering the question? If you did succeed, what did you learn? If you weren’t successful, can you propose a method which might help
 solve the question (i.e. different data, or using a different tool than SQL etc.)?
 
I didn’t really succeed in answering the questions because once again, the correlation wasn’t as clear as I thought. For example, ZIP Code 60647 had a really high attendance rate but ranked low in terms of safety. Once again, I would need an external dataset about the actual ZIP Code demographic. 
Which SQL tool(s) did you use to solve the question (i.e. aggregates, joins, cases etc.)?

I used GROUPBY, AVG(), ORDERBY, and DSC.

Is there a correlation between teacher attendance, student attendance, and teacher performance (teacher score)?

Why did you ask this question? Was there any information you wanted to learn?

I asked this question because it is known that teachers can make a huge difference in a student’s life. I wanted to know if there was a link between how many times students were absent and how many times teachers were absent. 

Did you succeed in answering the question? If you did succeed, what did you learn? If you weren’t successful, can you propose a method which might help
 solve the question (i.e. different data, or using a different tool than SQL etc.)?
 
I did succeed in answering the question. They were closely correlated as schools with high teacher performance, which most likely includes them being there to teach, also high student attendance. 

Which SQL tool(s) did you use to solve the question (i.e. aggregates, joins, cases etc.)?

I used ORDERBY and ASC.



Questions (Alicia):


Is there a correlation between zip code and family attendance score ?

Why did you ask this question? Was there any information you wanted to learn?

I asked this question because zip codes are often indicative of the economical status of a household and that may affect how involved a family can be in a student's life. I wanted to make the connection because poorer neighborhoods may have less time for family engagement which can be reflective in school grades. 

Did you succeed in answering the question? If you did succeed, what did you learn? If you weren’t successful, can you propose a method which might help
 solve the question (i.e. different data, or using a different tool than SQL etc.)?
 
Yes I was able to answer the question and there did seem to be some correlation between the two 

Which SQL tool(s) did you use to solve the question (i.e. aggregates, joins, cases etc.)?

Group By

Does low parental involvement and high rates of misconduct affect the yearly progress made in a school? 

Why did you ask this question? Was there any information you wanted to learn?

I asked this question because the result of parents not being involved enough is usually more misbehaving in school which does ultimately affect how much progress is made throughout the school year. 

Did you succeed in answering the question? If you did succeed, what did you learn? If you weren’t successful, can you propose a method which might help
 solve the question (i.e. different data, or using a different tool than SQL etc.)?
 
Yes I was able to answer the question and there did seem to be some correlation between the two 

Which SQL tool(s) did you use to solve the question (i.e. aggregates, joins, cases etc.)?

Aggregate 

Which elementary school zip codes have a higher CPS Performance level?

Why did you ask this question? Was there any information you wanted to learn?

I asked this question because zip codes can reflect the state of a neighborhood and better neighborhoods are more likely to have better adjusted students for school 

Did you succeed in answering the question? If you did succeed, what did you learn? If you weren’t successful, can you propose a method which might help
 solve the question (i.e. different data, or using a different tool than SQL etc.)?
 
No I was not successful, I needed a different set of data 

Which SQL tool(s) did you use to solve the question (i.e. aggregates, joins, cases etc.)?

Group By





Project Writeup:					
1. 						 							
Information about your data


Why did you choose the data set you were working with?

We chose the Chicago Public Schools - Progress Report Cards dataset because education is still one of the most racially segregated sectors that affect our youth. This is especially true in cities like Chicago with a high urban population. This is a topic that especially interested Mackenzie because he spent most of the semester working as a student teacher in a middle school. His colleagues had brought up the fact that even the New York City Department of Education is implicitly segregated due to the very nature of school zoning relative to the neighborhood income demographic.

What was your dataset about? What were some of the important columns in your data and why are they important?

Our dataset measured the school performance for the Chicago Public Schools School Report Card. It is rich in a lot of information to gauge how successful a school is in educating young minds. Some of the most important columns in the dataset, excluding basic information, were Safety Score, Family Involvement Score, Environment Score, Teachers Score, Family Involvement Score, and etc. These columns are important because you can use them to determine if there are certain factors that affect how well students are doing in schools. 

What kind of things did you want to explore about your data?

We were interested in exploring correlations between different factors, such as the state of a school, and how it reflected student performance. Student performance can be used to determine how well a school is doing in educating its students. 




2. Answered in the Questions Section.
 								
3. What if anything, did the project teach you? Do you have any suggestions to improve this project? What issues did you face when trying to answer your questions/copying the data (or any other issues)?
 
The project taught us that there were many factors that affect student performance, and in turn, school performance. We can’t just make assumptions or have leading questions. For improvement, ee would incorporate other datasets, such as ones that are about the state of the neighborhoods, to improve this project. We could even bridge this project with the previous one about Housing Inflation to see if rising housing prices affect attendance and whatnot. There were some minor issues with importing the CSV file into Postgres. The process seems to be very time consuming, especially with large datasets like the one we found for this project. 



4. If you had unlimited time and resources (i.e. you can collect your own dataset and use tools other than SQL) what project would you pursue?

We would do a project on the affordability of popular cities given the new cost of living and economics of said city. 	



5. Did you enjoy this class? What did you like? What did you dislike? Do you have any advice for improvements or other suggestions? If you have multiple authors, please separate by author) 

Alicia: Yes, the class was very fun and informative. I liked how open ended everything was so your learning was really up to you. 

Mackenzie: I enjoyed this class because it was very relaxed and laid back due to your teaching style. I liked how while you lectured every now and then, there was a lot of time for self-learning. I also really liked how small the class/classroom was, eliminating a lot of distractions, which could affect how one learns for night classes. 

