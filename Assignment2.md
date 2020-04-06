# Analyzing the Causes of the Poor Education System in Nigeria and What Geospatial Methods can be Used to Improve These Issues 
By Tessie Baumann <br />
April 5, 2020

### Introduction
The purpose of this research is to determine what factors and covariates are causing the poor education rates found in Nigeria and how more accurate data, through the use of various geospatial techniques, can be used to improve Nigeria’s education system. Currently, a majority of the data found in Nigeria is based on surveys. While surveys are helpful in collecting data on the population in Nigeria, but they are often lacking in accuracy and outdated. Additionally, surveys are expensive to conduct and therefore not economical for Nigeria, but this does not mean such information is not necessary for the well-being of the country. [13] Nigeria is struggling with its educational system and needs correct data to be able to understand what factors are affecting their education rates and implement strategies to move forward and increase the educational opportunities available to their citizens.

### Human Development Topic
Education is a right that is vital for success in today’s world. It opens up countless opportunities and increases one’s ability to obtain a higher-paying job, receive adequate healthcare, and achieve a better standard of living. In addition to the individual benefits, having educated citizens can help countries get out of poverty and advance technologically. [12] An education is essential to achieving many human development goals, because it helps to end some of the unfreedoms that people experience such as hunger, poor healthcare, and lack of resources through raising one’s ability to earn higher wages. 
Listening to all of these points about education, it seems obvious that developing countries should push for this in order to grow their economies and improve the standard of living for their citizens. Unfortunately, there are many factors that prevent such a thing from happening in countries all over the world. One of the worst off when it comes to education, however, is Nigeria. There are currently around 10.5 million children who are between the ages 5-14 who do not attend school in Nigeria and even those who do manage to receive an education oftentimes do not obtain a quality one. [4] In Nigeria, schools are disproportionately placed around urban areas due to the better conditions that are available there, increased resources, and the number of teachers. [9] Children from rural areas have trouble getting to school because of the distance they have to travel, and considering many of the roads they have access to for traveling are foot paths, it is not easy for children living in rural areas to reach school. One example of this is in Yewa south, where 49.4% of the children who are going to secondary school have to travel more than 2 km to get to school. [8] 

When children are able to attend school in Nigeria, they face problems such as overcrowding, limited resources, and high pupil to teacher ratios. [9, 11] Additionally, primary and secondary schools are not being distributed appropriately to best suit the population in each sector. One example of this is the Akure region of Nigeria, which is divided into three parts: Ifedore, Akure North, and Akure South. On average, primary schools in Akure South have around four to five thousand more people enrolled per school than both Akure North and Ifedore, and when it comes to secondary schools, Akure South has more institutions than both Akure North and Ifedore added together. [9] Furthermore, there are not enough teachers to go around, causing pupil teacher ratios to skyrocket. In Nigeria, the official pupil to teacher ratio is 35 for public primary schools, but in Ogun State, Nigeria, only 19% of the schools have pupil teacher rations below or equal to that number, while 39% of schools have pupil teacher ratios between 35-50 and 42% are above 50. [11] 
  
Finally, if students manage to achieve primary and secondary school educations, then they will still likely have trouble attending a university to further their skill sets. While there is at least one university, college, and polytechnic in every state in Nigeria, these schools, like the other public primary and secondary schools, are primarily funded by the government. This means that if the economy struggles, then the schools face financial trouble. In addition to that, the institutions once again have a tendency to favor locations in cities rather than rural areas, leaving many students without options for a tertiary education. [1] When looking at a map that examines the poverty levels in Nigeria, there is a clear indication that the more populated areas tend to have lower poverty rates, demonstrating how the economy is doing better in places with increased levels of schools. Still, Nigeria as a whole is struggling, with large numbers of the population surviving on $1.25 or less per day. [6] Change needs to happen for the people living there, and one of the best ways of enabling others to better their lives is through education.

### Human Development Process
In his article about human development, Amartya Sen discusses the idea that human development is “the process of expanding the real freedoms that people enjoy.” This is done by eliminating unfreedoms that are preventing people from accessing opportunities to better their lives. Education is clearly one of those opportunities that enables one to increase their quality of life as explained above. The question that needs to be answered, though, is what factors are hindering this sustainability goal. 
  
Contrary to the belief of many, simply feeding money into the economy is not the solution. In Nigeria, the economy is one of the fastest growing economies globally and from 2006-2016 and likely since then, the economy has been growing at an annual rate of about 6%. Despite this economic success, however, poverty levels have remained formidable, with a record high of 69% of the population in poverty in 2010. Therefore, pumping money into the economy is not the fix that is needed. [2]
  
Instead, taking a look at geospatial methods is the route to take. In a couple studies, for example, it has been revealed that there is a positive correlation between the numbers of teachers and the enrollment of students. [10, 11] Information like this can help the government prioritize what factors are most important for the success of Nigeria’s educational system, so they can implement those first in an attempt to encourage the growth of the system. Some other elements that are hurting the educational system include distance to the school, a lack of facility resources, and poverty rates. [9] By using geospatial data and data science methods to find correlations between the data and feeding them covariates such as transportation routes, land cover, and nighttime lights along with census/survey data, a lot of information can be found to help decision-making when it comes to education in Nigeria and the advancement of human development.

### Data Science Methods
The ultimate goal is to increase the quality and accessibility of education for the children in Nigeria. This objective cannot be achieved, however, without the proper data showing where improvements can be made and revealing the factors are stopping children from going to school. It is extremely difficult for Nigeria to implement policies that change the system when the government does not have the proper data available to it to inform its decisions. Many of the sources of data coming from Nigeria are based on surveys, which are not conducive to collecting large amounts of data across the country because of their expense to the government. [13] Additionally, surveys take time to conduct and it is difficult to repeat them in places such as Nigeria, due to their lack of technological resources. [9] In effect, this means that with surveys alone, it is hard to implement education policies and subsequently gather the data to understand the results of the policies. Moreover, procuring the data in the first place to make any initial decisions to revamp education is challenging when surveys are the only method of amassing data. This is why data science methods are necessary to provide more time and cost-efficient ways to obtain the data necessary to aid in the advancement of education in Nigeria. 

First off, one type of data science that would be very useful to Nigeria is the bottom-up approach. This method involves taking very precise surveys of several small, distinct areas, that encompass a range of different population proportions. These surveys are called microcensus surveys and when joined with spatial covariate data in statistical models, can be used to predict populations in unsurveyed areas. [13] This saves the country a lot of time and money when it comes to determining where the population is located.

One specific geospatial method that has been used in Nigeria is Bayesian model-based geostatistics. Before working with the Bayesian approach, however, it is necessary to gather an applicable combination of covariates that can be fed into the model. These covariates are then combined with the use of data at known cluster centroid locations and survey data to map out predictions of what the unknown sections look like in terms of whatever population question is being addressed. This is similar to how the bottom-up method works and was used in to create a map illustrating the proportions of children under 5 years old in Nigeria along with creating a map showing the poverty rates throughout the country. [3, 6] In addition to the maps, there are also uncertainty levels that clarify how credible different predictions are. For example, in the data obtained about children under 5 years in Nigeria, there is a map that shows that the data predicted in the Southern region is much more certain than the data in the Northern region. [3]

Another method that has been successfully implemented in Nigeria is random forest. Random forest is a technique that uses census data and other covariates to distribute the population data based on different weights for different areas. There is an algorithm that goes through the covariates and determines which ones are most relevant to where the population is aggregated and to what degree in what sections of the country. From there, those covariates are used to form weights to distribute where people are located and in what numbers. [5] Random forest enables maps to be made with mostly accurate data on where members of the population are located and has been used to create maps such as the one on population in Nigeria by World Pop. [7] In fact, World Pop has population maps for Nigeria for every year since 2000. This type of data is huge for Nigeria when it comes to education because it reveals what are the most advantageous locations to place schools to cater to a majority of the local population in each area of the country. 
	
One other tool that is used to look at the distribution of education is the Theil Index. This is an equation that is used to measure inequalities in education distribution per region across Nigeria. The results from this equation show that there are big gaps in between regions of the country, especially between the Northern and Southern regions. This is not surprising considering that there is a greater number of urban areas located within the Southern region of Nigeria and schools tend to be concentrated around urban locations. The tool also found that education inequalities are much higher in rural areas than urban ones, which once again makes sense after the information revealed above. [12] 

### Discussion
It is clear that there are many factors that are causing the education systems in Nigeria to be so poor. After all, Nigeria is a complex society. Technology is changing, the economy is evolving, and the population is constantly growing. Nigeria is trying to keep up with the data but is having trouble, as is seen through the patterns shown in the articles referenced above. The government has tried to improve Nigeria’s education system through acts such as the Universal Primary Education and Universal Basic Education programs but failed because of the discrepancy between population distribution and the distribution of public education facilities. No amount of promoting education can overcome accessibility issues and the poor conditions found at some of the existing schools, especially those found in rural provinces. [9]

Data science methods, however, open up a world of possibilities for the country. Government leaders and other countries who would like to send aid can understand where members of the population reside and how to make schools accessible for all, especially in the rural areas. If this happens, then the increase in education will lead to positive results for the economy. Subsequently, if the economy is thriving, then the government, as the financier of Nigeria’s educational system, will have more money to put back into the system, which leads to better conditions and more resources in the schools. Such conditions would attract teachers out to rural areas and put an end to the tendency of teachers to stay in urban centers where the educational facilities feature better conditions. As the world continues to adapt, Nigeria must follow and use the new methods that are becoming available in order to move up the human development scale and improve life for its citizens. 

### Central Research Question
What factors are behind Nigeria’s poor educational system and how can the use of geospatial methods improve the data available to the country so that the government can make educated decisions on this issue? 



















## References
[1]	Akpan, P. A. “The Spatial Aspects of Higher Education in Nigeria.” Higher Education, vol. 16, no. 5, 1987, pp. 545–555. JSTOR, www.jstor.org/stable/3446832. 

[2]	Ajakaiye, Jerome, Olaniyan, Mahrt, Alaba. “Spatial and Temporal Multidimensional Poverty in Nigeria.” Growth and Poverty in Sub-Saharan Africa, 2016, Oxford Scholarship Online, www.oxfordscholarship.com/view/10.1093/acprof:oso/9780198744795.001.0001/acprof-9780198744795-chapter-10?p=emailAOgz7TQpcERn.&d=/10.1093/acprof:oso/9780198744795.001.0001/acprof-9780198744795-chapter-10. 

[3]	Alegana, Atkinson, Pezzulo, Sorichetta, Weiss, Bird, Erbach-Schoenberg, Tatem. “Fine Resolution Mapping of Population Age Structures for Health and Development Applications.” Journal of the Royal Society Interface, vol. 21, no. 105, 2015, royalsocietypublishing.org/doi/pdf/10.1098/rsif.2015.0073. 

[4]	“Education.” Unicef, www.unicef.org/nigeria/education. 
 
[5]	Nieves, Stevens, Gaughan, Linard, Sorichetta, Hornby, Patel, Tatem. “Examining the Correlates and Drivers of Human Population Distributions Across Low- and Middle-Income Countries.” Journal of the Royal Society Interface, vol. 14, no. 137, Dec. 2017, www.ncbi.nlm.nih.gov/pmc/articles/PMC5746564/pdf/rsif20170401.pdf. 

[6]	“Nigeria 1km Poverty.” World Pop, Jan. 2013, www.worldpop.org/geodata/summary?id=1267. 

[7]	“Nigeria Population 2020.” World Pop, 2018, www.worldpop.org/geodata/summary?id=6409.

[8]	Ogunyemi, Muibi, Eguarje, Fabiyi, Halilu. “A Geospatial Approach to Evaluation of Accessibility to Secondary Educational Institution in Ogun State, Nigeria.” IOP Conference Series: Earth and Environmental Science, vol. 20, 2014, IOP Science, iopscience.iop.org/article/10.1088/1755-1315/20/1/012045. 

[9]	Olamiju, Isaac, and Julius Olujimi. “Regional Analysis of Locations of Public Educational Facilities in Nigeria: The Akure Region Experience.” Journal of Geography and Regional Planning, vol. 4, July 2011, pp. 428-442. Research Gate, www.researchgate.net/publication/233855500_'Regional_Analysis_of_Locations_of_Public_Educational_Facilities_in_Nigeria_The_Akure_Region_Experience'. 

[10]	Olubadewo, Abdulkarim, Ahmed. “The Use of GIS as Educational Support System (EDSS) for Primary Schools in Fagge Local Government Area of Kano State, Nigeria.” Academic Research International, vol. 4, no. 6, Nov. 2013, Research Gate, www.researchgate.net/publication/277718678_Academic_Research_International_THE_USE_OF_GIS_AS_EDUCATIONAL_DECISION_SUPPORT_SYSTEM_EDSS_FOR_PRIMARY_SCHOOLS_IN_FAGGE_LOCALGOVERNMENT_AREA_OF_KANO_STATE_NIGERIA. 

[11] 	Opanuga, Okague, Oguntunde, Bishop, Ogundile. “Learning Analytics: Issues on the Pupil-Teacher Ratio in Public Primary Schools in Nigeria.” International Journal of Emerging Technologies in Learning, vol. 14, n. 10, May 2019, pp. 180-199, online-journals.org/index.php/i-jet/article/view/10129/5695.

[12]	Umar, Ismail, Abdul-Hakim. “Regional Inequality of Educational Attainment in Nigeria.” British Journal of Economics, Management & Trade, vol. 4, no. 3, 2014, pp. 420-430, journaljemt.com/index.php/JEMT/article/view/11477/20825. 

[13]	Wardrop, Jochem, Bird, Chamberlain, Clarke, Kerr, Bengtsson, Juran, Seaman, Tatem. “Spatially Disaggregated Population Estimates in the Absence of National Population and Housing Census Data.” Proceedings of the National Academy of Sciences of the United States of America, vol. 115, no. 14, 3 Apr. 2018, pp. 3529-3537, Perspective, www.pnas.org/content/pnas/115/14/3529.full.pdf. 




