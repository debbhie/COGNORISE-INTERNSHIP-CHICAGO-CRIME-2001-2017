# CHICAGO CRIMES 2001 TO 2017

## TABLE OF CONTENT
- [CHICAGO CRIMES 2001 TO 2017 ANALYSIS OVERVIEW](#chicago-crimes-2001-to-2017-analysis-overview)
- [LANDING PAGE](#landing-page)
- [DATA SOURCE](#data-soure=ce)
- [TOOLS](#tools)
- [TYPES OF ANALYSIS USED FOR THIS PROJECT](#types-of-analysis-used-for-this-project)
- [KEY PERFORMANCE INDICATORS](#key-performance-indicators)
- [DATA CLEANING](#data-cleaning)
- [DATA PROCESSING](#data-processing)
- [DATA ANALYSIS](#data-analysis)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)

## CHICAGO CRIMES 2001 TO 2017 ANALYSIS OVERVIEW
The analysis of crime data from Chicago between 2001 and 2017 reveals significant trends and patterns in criminal activities over the 17-year period. The dataset contains a total of 7,941,282 recorded crime incidents, spanning various types of crimes, locations, and outcomes.

## LANDING PAGE
* ID: Unique identifier for record.
* CASE NUMBER: The chicago police department RD number (Record Division Number), which is unique to the incident.
* DATE: Date the incident occurred.
* BLOCK: The partially redacted address where the incident occurred, placing it on the same block as the actual address.
* PRIMARY TYPE: Type of crime.
* DESCRIPTION: A subcategory of the primary description
* LOCATION DESCRIPTION: Description of the location where thr incident occurred.
* ARREST: Indicates whether an arrest was made.
* Domestic: Indicates whether the incidents was domestic related.
* YEAR: Year the incident occurred.
* LONGITUDE
* LATITUDE

## DATA SOURCE
This dataset is from cognorise internship
-[download here](https://www.kaggle.com/datasets/currie32/crimes-in-chicago)

## TOOLS
- Analysis - Jupyter notebook
- Visualization - Jupyter notebook

## TYPES OF ANALYSIS USED FOR THIS PROJECT
* Statistical Analysis: mean, median, mode and standard deviation for numerical columns.
* Exploratory data analysis
* Comparative analysis
* Predictive analysis

## KEY PERFORMANCE INDICATORS
* Total number of crime incidents.
* Top 10 crime incidents by primary type and location.
* Arrest rate.
* Arrest rate by primary type.
* Percentage of domestic related crime incidents.
* seasonal variation in crime incidents.
* Trend analysis in total crime incidents.
 
## DATA CLEANING
Alot of errors were corrected especially in spelling.

## DATA PROCESSING
* Null values were replaced with 0.0 in longitude and latitude columns.
* The column for month was created by extracting from date column

## DATA ANALYSIS
### Total Number of crime incidents recorded: 
The crime data analysis spans from 2001 to 2017, with a total of 7,941,282 crime incidents recorded in Chicago. 
visualization of total incident yearly
![incident total yearly](https://github.com/user-attachments/assets/3ebc5b70-9554-4545-9f71-dfc652c48702)

![incident total visual](https://github.com/user-attachments/assets/d7552f64-c6d1-4e6e-b368-d5018d527cd3)

### Top 10 crime incident yearly by primary type: 
* Theft (1,639,788 incidents) is the most prevalent crime, accounting for the highest number of incidents among all categories. This high rate of theft suggests widespread issues related to property crimes. This could be driven by various factors, including economic conditions, unemployment, or inadequate security measures in both public and private spaces.
* Battery (1,442,711 incidents) which typically involves physical harm or threat, is the second most common crime. The high incidence of battery indicates significant levels of violence in the community. This points to underlying social issues such as gang activity, domestic violence, or interpersonal conflicts.
* Criminal Damage (922,993 incidents) which includes vandalism and property destruction, ranks third. The large number of criminal damage incidents suggests problems with public order and respect for property. This could be related to civil unrest, youth delinquency, or retaliatory actions.
* Narcotics (885,429 incidents) related crimes are a major issue, with nearly 900,000 incidents recorded. The high rate of narcotics crimes reflects widespread drug-related issues, including both use and trafficking. This often correlates with other crimes such as theft, violence, and gang activity, indicating a need for comprehensive drug enforcement and rehabilitation programs.
* Other Offenses (491,920 incidents) This category encompasses various less common or minor offenses. The broad nature of this category makes it harder to analyze, but it still represents a significant portion of the crime landscape. Further investigation into what specific crimes are included here could help tailor law enforcement strategies.
* Assault (481,658 incidents) which involves threats or attempts to cause physical harm, is another significant crime type. Like battery, the high number of assault incidents reflects underlying issues of violence in the community. It also indicates potential areas where conflict resolution and violence prevention programs could be beneficial.
* Burglary (470,953 incidents) involving illegal entry into buildings with intent to commit a crime, ranks seventh. The prevalence of burglary highlights security issues in residential and commercial properties. This suggests a need for improved security measures and community awareness programs to reduce such incidents.
* Motor Vehicle Theft (370,547 incidents) is a significant crime, though less common than burglary. This indicates a substantial problem with vehicle security in the area. Law enforcement could focus on improving vehicle theft prevention strategies and increasing public awareness about protective measures.
* Robbery (300,449 incidents) which involves taking property from a person by force or threat, is a notable crime. The occurrence of robbery suggests the need for better personal security measures, especially in high-risk areas. It also indicates the potential presence of organized crime or desperate individuals turning to robbery.
* Deceptive Practice (279,693 incidents) including fraud and other forms of deceit, round out the top ten. The relatively high incidence of fraud-related crimes points to issues in financial security, both online and offline. This calls for stronger consumer protection laws and awareness campaigns to prevent people from falling victim to such crimes.
Visualization of incident by primary type
![incident by primary type](https://github.com/user-attachments/assets/d32d7f07-2ba8-4bf6-a09d-0fccb1c80487)

![primary type visuals](https://github.com/user-attachments/assets/414b1d9f-c7f3-4865-8678-030a20168c1a)

### Top 10 crime incident yearly by Location: 
-  High-Risk Locations:
* Street (2,101,842 incidents) are the most common location for crimes, accounting for approximately 26.5% of all incidents. Crimes on streets are often more visible to the public, suggesting that many incidents could be related to street-level offenses such as theft, assault, or drug-related activities. The high number of crimes on streets indicates a need for increased street patrols, surveillance, and public awareness campaigns to reduce crime rates in these areas.
* Residence (1,341,749 incidents) are the second most common location for crimes, making up about 16.9% of incidents. Crimes in residences often involve domestic violence, burglary, or disputes among known individuals, which may be harder to prevent through traditional policing. This highlights the importance of neighborhood watch programs, better home security measures, and domestic violence intervention strategies.
* Sidewalk (815,595 incidents) Sidewalks, like streets, are public spaces with high pedestrian traffic, often linked to crimes such as muggings, pickpocketing, or assaults. The high incidence of crime on sidewalks calls for better lighting, public awareness, and perhaps increased foot patrols to deter criminal activities.

- Medium-Risk Locations:
* Apartment (812,512 incidents)are close in crime frequency to sidewalks, indicating a significant level of crime within multi-unit residential buildings. This could involve domestic disputes, theft, or vandalism. Security in apartment complexes should be prioritized, with measures such as improved access control, security cameras, and resident awareness programs.
* Other (294,286 incidents) This category likely includes a variety of less common crime locations, which might include areas such as parks, abandoned buildings, or industrial areas. Understanding the specific nature of these "other" locations could help tailor preventive measures to those particular environments.
* Parking Lot/Garage (Non-Residential) (225,454 incidents) Parking lots and garages are known for being relatively isolated and can be hotspots for vehicle theft, robbery, or vandalism. Enhanced security measures such as better lighting, security patrols, and surveillance systems are essential in these areas.
  
- Lower-Risk Locations:
* Alley (180,155 incidents) provide secluded areas that are attractive for crimes such as illegal dumping, drug deals, or assaults. Increased monitoring of alleys through surveillance and neighborhood involvement could help reduce crime in these hidden spots.
* School, Public Building (173,750 incidents) While these are generally safer spaces, the presence of crimes here indicates issues such as vandalism, bullying, or drug-related incidents within or near school premises. Ensuring a safe environment in schools and public buildings through security personnel, student programs, and anti-drug initiatives is crucial.
* Residence Garage (158,550 incidents) particularly in residential areas, are often targets for theft or vandalism. Reinforcing garage security, such as installing better locks and security cameras, could mitigate risks.
* Residence Porch/Hallway (138,492 incidents) Porches and hallways, as entry points to residences, are vulnerable to crimes such as burglary, package theft, or even physical assaults. Enhancing visibility, security measures, and community vigilance around these entry points can help deter potential crimes.
Visualization of incident by location
![incident by location](https://github.com/user-attachments/assets/93f84dbf-2122-4e37-876e-119e94f18d88)

![location visuals](https://github.com/user-attachments/assets/087e48cc-91f2-4a82-889b-d2dbd3ef19ff)

### Analysis of Arrests and Domestic-Related Crime Incidents:
* Arrest Rates, the data indicates that 28.33% of all crime incidents resulted in an arrest, meaning that out of the 7,941,282 total incidents, 2,249,420 led to arrests.
* Proportion of Arrest to Non-Arrest is 28% of the incidents resulted in arrests while Non-Arrests is 72% of the incidents did not result in arrests, with 5,691,862 cases falling into this category.
* Domestic-Related Incidents, the data shows that 12.84% of the total incidents are domestic-related. This means approximately 1,019,086 of the incidents are related to domestic violence or disputes.
Visualization of arrest vs non arrest
![arrest vs non arrest](https://github.com/user-attachments/assets/f273665a-e5d6-4b6c-9412-09bb867a7f60)

### Yearly Trend Analysis:
* Peak Crime Years (2006-2009): 2008 recorded the highest number of incidents (852,053), followed by 2006 (794,684) and 2009 (783,900).This period saw a sharp increase in crime, peaking in 2008.
* Declining Trend Post-2008: After 2008, there is a noticeable decline in the number of reported incidents. By 2011, the number of incidents dropped significantly to 352,066—a decrease of more than 50% compared to 2008. This downward trend continues through 2017.
* Lowest Crime Year: 2017 recorded the lowest number of incidents, with only 11,357 reported. This sharp decline suggests a substantial change in crime reporting or actual crime reduction.
* Stability and Minor Fluctuations: From 2012 to 2016, the incident numbers remained relatively stable, fluctuating between 262,995 and 335,670 incidents per year.
This period shows a consistent but gradual decrease in crime incidents.
Visualization of yearly trend
![yearly trend](https://github.com/user-attachments/assets/234f5e17-c4d0-43a7-b448-a839eafddd86)

![yearly tren visuals](https://github.com/user-attachments/assets/acf3003d-f747-4f38-b624-dad65cd9ede0)

### Seasonal Crime incidents:
* Summer (June to August) has the highest number of crime incidents, with a total of 2,167,238 incidents. The increase in crime during the summer months could be attributed to warmer weather, which often results in more outdoor activities and, consequently, more opportunities for crimes such as thefts, assaults, and public disturbances.
* Spring (March to May) follows with 2,019,485 incidents, indicating a gradual increase in crime as the weather begins to warm up. The rise in incidents during Spring might be related to increased social interactions and events as people become more active after winter.
* Fall (September to November) records 1,977,477 incidents, showing a slight decline from Spring but still maintaining relatively high crime rates. The transition from summer to fall may see continued outdoor activities and public events, keeping crime rates elevated.
* Winter (December to February) has the lowest number of incidents, with 1,777,082 reported crimes. The colder weather likely keeps more people indoors, reducing the opportunity for certain types of crimes, such as street-level offenses.
Visualization of seasonal crime incidents
![seasonal incident visual](https://github.com/user-attachments/assets/7e93590b-67b3-4c3c-96ff-81d1d631195a)

![Screenshot 2024-08-08 172239](https://github.com/user-attachments/assets/9f72d985-a83a-4114-b412-cb1fd729b2a3)


### Analysis of Statistical Values for Arrest and Domestic-Related Incidents:
- Mean Values:
* Arrest (0.283257): The mean value of approximately 0.28 indicates that about 28% of the crime incidents in the dataset resulted in an arrest. This aligns with the earlier finding that the arrest rate is 28.33%.
* Domestic (0.128374): The mean value of approximately 0.13 indicates that around 13% of crime incidents are domestic-related. This suggests that domestic violence or disputes form a significant portion of the total crime incidents, but still a minority.
- Median Values:
* Arrest (0.0): The median value of 0 indicates that the majority of incidents did not result in an arrest. This is because more than half of the data points are non-arrest cases, highlighting that arrests are not the outcome in most crime incidents.
* Domestic (0.0): Similarly, the median value for domestic-related incidents is 0, indicating that in more than half of the cases, the crimes are not domestic in nature.
- Mode Values:
* Arrest (False): The mode value for arrest being False (or 0) confirms that the most frequent outcome in the dataset is that no arrest was made. This reiterates the point that arrests are less common than non-arrests.
* Domestic (False):The mode value for domestic-related incidents being False indicates that the most common scenario is a crime that is not domestic-related.
- Standard Deviation Values:
* Arrest (0.450580): The standard deviation of approximately 0.45 indicates that there is significant variability in the arrest data. This means that while a sizable portion of incidents do result in arrests, the presence of many incidents without arrests creates a wide spread in the data.
* Domestic (0.334505): The standard deviation for domestic-related incidents is approximately 0.33, suggesting moderate variability. While the majority of cases are not domestic-related, there is still a considerable number of domestic incidents, leading to some spread in the data.


### Analysis of the Correlation Matrix between Arrest and Domestic Incidents:
* Correlation Values
Arrest and Domestic (-0.07157): The correlation coefficient between Arrest and Domestic is approximately -0.07157. This negative value indicates a weak inverse relationship between the two variables. In other words, as the likelihood of an incident being domestic-related increases, the likelihood of an arrest being made slightly decreases, and vice versa.However, because the value is close to zero, this correlation is weak, suggesting that there is minimal linear relationship between whether an incident is domestic-related and whether an arrest is made.
* Interpretation
Weak Relationship: The weak negative correlation suggests that there is little to no strong linear relationship between domestic incidents and arrests. In practical terms, this means that whether a crime is domestic-related or not does not significantly influence the likelihood of an arrest being made.
Possible Implications: The lack of a strong relationship could indicate that arrests in domestic-related incidents are influenced by other factors not captured in this simple bivariate correlation. For example, the nature of the incident, evidence available, or the presence of legal protections in domestic situations could play more significant roles in whether an arrest is made. It may also suggest that domestic incidents are either under-reported or handled differently compared to other types of crimes, possibly due to the sensitive nature of such cases or the complexities involved in resolving them.


## INSIGHTS 
* Crime Reduction: The significant drop in crime incidents after 2008 indicates effective crime reduction strategies, changes in law enforcement practices, or changes in data reporting methods.
* Property Crimes Dominate: Theft, criminal damage, burglary, and motor vehicle theft are all property-related crimes that together make up a significant portion of the top 10. This indicates a pressing need for better property protection measures.
* High Levels of Violence: Battery and assault are major concerns, reflecting the need for interventions to reduce violence in the community.
* Narcotics as a Root Cause: The high incidence of narcotics-related crimes suggests that drug issues may be a driving factor behind many of the other crimes, such as theft and violent crimes.
* Law Enforcement Efficiency: The overall arrest rate of 28% suggests room for improvement in law enforcement’s ability to apprehend suspects. This could be due to various factors, including the nature of the crimes, the resources available, and the cooperation of the community.
* Community and Policy Implications: These figures suggest a need for policies that enhance law enforcement capabilities, particularly in handling domestic violence cases, and community programs that aim to prevent crime and support victims more effectively.
* Public vs. Private Crime Locations: The data shows a significant distribution of crimes across both public (streets, sidewalks) and private (residences, apartments) locations. Public spaces, especially streets, are the most frequent crime locations, but residential areas also see a substantial share of criminal activity.


## RECOMMENDATIONS
* Enhanced Security Measures: Given the high rates of theft and burglary, there should be a focus on improving security in vulnerable areas. This could include increased police patrols, neighborhood watch programs, and public education on property protection.
* Drug Enforcement and Rehabilitation: The large number of narcotics incidents indicates the need for a dual approach of strict drug law enforcement combined with accessible rehabilitation services to address the root causes of drug-related crimes.
* Financial Crime Awareness: To combat deceptive practices, there should be stronger public education campaigns on fraud prevention, along with tighter regulations on financial transactions and online security.
* Improve Investigative Techniques: Investing in training, technology, and community policing strategies could help increase the arrest rate, particularly in areas with high unsolved crime rates.
* Streets and Sidewalks: Deploy more law enforcement officers in high-crime public areas to act as a deterrent.
* Residential Patrols: Implement regular patrols in residential areas, especially in neighborhoods with high crime rates.
* Schools and Public Buildings: Ensure these locations are equipped with adequate security personnel and systems to maintain safety.
* Policy Development: Policies aimed at reducing crime should consider the high variability in arrest rates and domestic-related incidents. Specific measures for high-risk groups and regions may be more effective than broad, one-size-fits-all approaches.



