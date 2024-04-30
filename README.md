# MIST4610 Project 2 (Group 1)
# Team Members: 
1. Charlie Kim [@charles8888](https://github.com/charles8888)
2. Gwen Wentworth [@gaw63800](https://github.com/gaw63800)
3. Caroline Cooper [@carolinetcooper6](https://github.com/carolinetcooper6)
4. Kishen Patel [@supersomeone03](https://github.com/supersomeone03)
5. Hubah Akhtar [@hubahakhtar](https://github.com/hubahakhtar)

# Data Source:
[Data Set: Youth Tobacco Survey](https://catalog.data.gov/dataset/youth-tobacco-survey-yts-data)

# Dataset Description:
The YTS was developed to provide states with comprehensive data on both middle school and high school students regarding tobacco use, exposure to environmental tobacco smoke, smoking cessation, school curriculum, minors' ability to purchase or otherwise obtain tobacco products, knowledge and attitudes about tobacco, and familiarity with pro-tobacco and anti-tobacco media messages. The YTS uses a two-stage cluster sample design to produce representative samples of students in middle schools (grades 6–8) and high schools (grades 9–12). The data for the STATE System were extracted from Youth Tobacco Surveys from participating states. Tobacco topics included are cigarette smoking prevalence, cigarette smoking frequency, smokeless tobacco products prevalence and quit attempts.

# Dataset Content(s):
Each row within our dataset is a youth tobacco survey entry conducted according to the recorded year. The important columns we have focused on within this dataset are the year the YTS was conducted (YEAR), the state in which it was conducted(LocationDesc), the topic type being “tobacco usage” for all data entries(TopicType), the detailed description of that topic (TopicDesc), the source of our data (DataSource), the responses from the YTS (Response), the data value(Data_Value) and its data type (Data_Value_Type), which genders were focused per survey (Gender), what races were observed (Race), the age group(s) observed (Age), and the education level of the student(s) (Education).

# Question 1:
How does education level affect the levels of which survey respondents use tobacco over time?

Explanation: This question is important as it is a topic that is relatively frequently researched. It is known that age is a strong indicator of brain development, and therefore, this question is more-so linking even linking brain development and using tobacco products. This is also a question which can be very useful for parents with children around this age; Some parents are very oblivious to assume “no, my middle or highschooler does not use tobacco products.” This display clearly shows that that is not true for many children of that age from this data set. In light of many recent campaigns to encourage open conversations between parents and their children about drug/alcohol safety, a display such as this will encourage parents to bridge that gap and join this movement of more open conversations about safety.

![image](https://github.com/charles8888/Project2/assets/150093221/4a152063-baab-4fd7-9726-8163c309ef01)

Analysis:
According to our histogram data analysis comparing the education levels and their responses, the most saturated section appears to be high schoolers responding with “Ever”, specifically during the late 1990s being the peak. The general trend across all six histograms is a constant decline as time goes on from 1999 to 2017. When it comes to the level of education, high schoolers seem to have a higher rate of tobacco usage than middle schoolers. In terms of the response, “Ever” appears to be the highest frequency of response type.

# Question 2:
How does the amount of people/density of people who frequently smoke change over time by state?

Explanation: 
This question is meaningful because we can see the various influences of social, economic, and cultural changes directly impacting the data. High smoking prevalence correlated with increased healthcare costs due to smoking related illnesses creates increasing healthcare costs. Also, states with stricter tobacco policies often experience declines in smoking rates which can aid in decreasing healthcare costs. We can track the data to use later to predict healthcare costs for the future. Analyzing smoking prevalence in different demographics alongside changing policies provides insights into the effectiveness of public health policies in place. The cultural norms continuously developing and “trends” coming and going reflects shifts in societal perceptions and behaviors. By integrating multiple data sources, researchers can uncover complex relationships between smoking behavior and socio-economic factors, informing evidence-based policies and interventions to reduce smoking prevalence and its associated burdens.

![image](https://github.com/charles8888/Project2/assets/150093221/a9df2b13-d304-4dee-ac77-71eb7449bb48)

![image](https://github.com/charles8888/Project2/assets/150093221/6e3c2f43-ed1a-47c6-9a5e-a0e2bdb7d000)

Analysis:
Based on the data analysis and results from our heat map, our team has concluded that tobacco usage among teenagers has overall been diminished across the United States as a whole. There are some outliers to the common pattern of decline in teenage tobacco usage, some of them being the states of Kentucky (KY), West Virginia(WV), and New Hampshire(NH). Looking solely on our data from 1999 to 2017, the states that appear to have little to no presence of teenage tobacco usage are California (CA), Utah (UT), Idaho (ID), Wyoming (WY), Colorado (CO), New Mexico (NM), Texas (TX), Iowa (IA), Virginia (VA), New York (NY), Maryland (MD), Vermont (VT), Massachusetts (MA), Rhode Island (RI), and Maine (ME). Specifically, we narrowed down our data analysis (line graph) to the Southern states Alabama, Georgia, Louisiana, and South Carolina. Among the four states, Georgia appeared to have the highest in 1999 but by 2017 had the lowest frequent tobacco consumption by students. This can allow us to make an assumption that anti-tobacco campaigns for the young students have proved to be more successful and effective in Georgia more than Louisiana, Alabama, and South Carolina.

# Manipulation(s) during Analysis:
To accurately display the density of frequent smokers across the different periods, we had to change the color legends to be consistent with each other. The colors on the map accurately show the range of .13% - 10.83%. That way our map would show the same colors. Tableau also helped us generate the longitude and latitude for each state based on the name. This allowed us to accurately plot on the map.
















