# india-sexual-assault
This was made as part of the final project for my visualization class. 

Parliament diagram:
This project includes parliamentary data from the Association for Democratic Reforms, available here. (https://adrindia.org/content/lok-sabha-elections-2019) I was able to just copy out the tables from the pdfs. It was made in d3. 
It includes:
- scrollytelling 
- d3-transitions 

Slope graph:
It also includes Crimes Against Women data from the National Crime Records Bureau (http://ncrb.gov.in/).
I copied the data out of the pdfs again and fixed it up in Visual Studio Code. 
It includes: 
- hovering 
- highlighting 
- responsiveness
- d3-tootip

Force Diagram:
The list of women MPs in the Lok Sabha can be found here. (https://yourstory.com/herstory/2019/05/women-politicians-lok-sabha-2019)
I copied this list and did a ton of processing on it to convert it to a json. You can find that in my notebook. The final bits of processing were done in Visual Studio Code. 
It includes: 
- scrollytelling
- dragging 
- hovering

Skills/Tools:
Python, pandas, regex, d3

Codebook:

dummydata2.json has all of the women MPs and their party + state affiliations. Look at the csv to json notebook to see what the numbers mean! 

rape_rates_state.csv has the number of reported cases of crimes against women divided by the population of women in each state at the time of recording. That calculation was done by the National Crime Records Bureau - I just cleaned it up into a csv. The fields are states and the years in question (2011-2017). 
