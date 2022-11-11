# Kenya_GDP_Analysis_and_prediction
Kenya GDP Analysis and prediction from data set of between year 1960 to 2020
 

# About Dataset 
GDP of each country and region(1960-2020)
GDP:Gross Domestic Product

Countries in the data set
'United States', 'United Kingdom', 'France', nan, 'Japan', 'Canada', 'Italy', 'Brazil', 'Turkey', 'Mexico', 'Netherlands', 'Spain', 'Switzerland', 'South Africa', 'Austria', 'Denmark', 'New Zealand', 'Finland', 'Norway', 'Greece', 'Bangladesh', 'Nigeria', 'Chile', 'Colombia', 'South Korea', 'Pakistan', 'DRC', 'Thailand', 'Israel', 'Peru', 'Morocco', 'Malaysia', 'Puerto Rico', 'Iraq', 'Sri Lanka', 'Hong Kong', 'Sultan', 'Uruguay', 'Ghana', 'Zimbabwe', 'Guatemala', 'Ecuador', 'Syria', 'Senegal', 'Kenya', 'Zambia', 'Luxembourg', 'Jamaica', 'Madagascar', 'Dominica', 'Cambodia', 'Cameroon', 'Bolivia', "C ô te d'Ivoire", 'Afghanistan', 'Panama', 'Trinidad and Tobago', 'Nepal', 'Costa Rica', 'Niger', 'Uganda', 'Sierra Leone', 'Chad', 'Haiti', 'Papua New Guinea', 'Benin', 'Nicaragua', 'Burundi', 'Liberia', 'Somalia', 'Bahamas', 'Mawlawi', 'Gabon', 'Congo (Brazzaville)', 'Rwanda', 'Fiji Islands', 'Central Africa', 'Suriname', 'Mauritania', 'Bermuda', 'Eswatini', 'Lesotho', 'Belize', 'Saint Vincent and the Grenadines', 'Argentina', 'Equatorial Guinea', 'Egypt', 'Kuwait', 'Tunisia', 'Jordan', 'Paraguay', 'French Polynesia', 'New Caledonia', 'Brunei', 'Oman', 'Indonesia', 'Solomon Islands', 'Saudi Arabia', 'Germany', 'Cuba', 'Qatar', 'Monaco', 'Malta', 'Liechtenstein', 'Guinea Bissau', 'Greenland', 'Kiribati', 'UAE', 'Tonga', 'Saint Lucia', 'Antigua and Barbuda', 'Grenada', 'Vanuatu', 'Angola', 'Mozambique', 'Namibia', 'Cape Verde', 'Bhutan', 'Maldives', 'Ethiopia', 'Marshall Islands', 'Samoa', 'the Federated States of Micronesia', 'Albania', 'Laos', 'Vietnam', 'Lebanon', 'Poland', 'Czech Republic', 'Libya', 'Kazakhstan', 'Belarus', 'Uzbekistan', 'Slovakia', 'Azerbaijan', 'Georgia', 'Yemen', 'Macedonia', 'Moldova', 'Kyrgyzstan', 'Tajikistan', 'Armenia', 'Palau', 'Hungary', 'Palestine', 'Bosnia and Herzegovina', 'Croatia', 'Serbia', 'Lithuania', 'Latvia', 'Isle of man', 'Faroe Islands', 'Myanmar', 'San Marino', 'Timor Leste', 'Turks and Caicos Islands', 'Sao Tome and Principe', 'Guam', 'Northern Mariana Islands', 'American Samoa', 'South Sudan', 'cura ç Ao'

States in the data set
'America', 'Europe', 'Asia', 'Oceania', 'Africa'



# :dart: Analysis Goal 
## Find out the following :->

1. **Is there a relationship between gender and heart failure ?** 

2. **Is there a relationship between Age with heart failure ?** 

3. **Is there a relationship between Diabetes with heart failure ?**

# :toolbox: libraries used
1. pandas
2. matplotlib
3. seaborn


# Repository Map
1. :ballot_box_with_check: heart_failure_clinical_records_dataset.csv - the dataset used in the analysis
2. :ballot_box_with_check: Heart-Failure-Analysis-and-visualization.ipynb - the jupyter notebook containing all the code, all analysis and visualization. 
3. :ballot_box_with_check: README.md

# Inspiration
**Why this analysis ?**

Coronary Heart Diseases is not a new occurrence in Kenya Today.
According to the latest WHO data published in 2020 Coronary Heart Disease Deaths in Kenya reached 11,972 or 4.54% of total deaths. The age adjusted Death Rate is 72.70 per 100,000 of population ranks Kenya #144 in the world.

However, There has been an increasing rate of Coronary Heart Disease in Kenya ever since 2018. This motivated me to understanding the causes of the increase in Coronary Heart Diseases and death rate in Kenya.

During my analysis I found out that tobacco use and exposure to tobacco smoke is a major cause of raised blood pressure and other forms of CVDs including heart attack and stroke that eventually result to high death-rates  


# Data analyis goals Findings and chart
1. **Is there a relationship between gender and heart failure ?** YES! From the data, it is observed that the male have more death count compared to women and hence are more likely to succumb to heart failure.
## chart
![gender and heart failure Linechart](https://george.m.ndichu.ltd.co.ke/media/github/gender-death-rel%20count%20plot.png "Relationship between gender and heart failure Linechart")

2. **Is there a relationship between Age with heart failure ?** YES! From the data, it is observed that Older people compared to the young are prone to succumbing to heart failure
## chart
![Age and heart failure Lineplot](https://george.m.ndichu.ltd.co.ke/media/github/age-heart-failure-lineplot.png "Relationship between age and heart failure Line plot")

3. **Is there a relationship between Diabetes with heart failure ?** NO! From the data, it is observed that there is little to no relationship between diabetes and heart failure
## chart 1
![Diabetes and heart failure Countplot](https://george.m.ndichu.ltd.co.ke/media/github/diabetes-heart-failure-countplot.png "Relationship between Diabetes and heart failure Count plot")
 ## chart 2
![Diabetes and heart failure Line plot](https://george.m.ndichu.ltd.co.ke/media/github/diabetes-heart-failure-lineplot.png "Relationship between Diabetes and heart failure Line plot")

# Research Findings
1. **Awareness** is paramount in the control of Coronary Heart Diseases in Kenya.

2. **Smoking** and **exposure to smoke** (Especially smoking tobacco and exposure to tobacco) is a major cause of raised blood pressure and other forms of CVDs including heart attack and stroke.

3. **Educating the public** on **adopting healthy lifestyles** is also key in the control of Coronary Heart Diseases in Kenya. More than half (56%) of the adult population has never had their blood pressure measured yet almost 1 in 4 Kenyans is living with hypertension and with just about a quarter of them being on medication.

4. About 11.6% (2.5 Million) of adult Kenyans and 9.9 % of youth aged between 13 -15 years use tobacco products; while 86.1% of adults are exposed to **second-hand tobacco smoke** in bars and night clubs and 24.8% of youth being exposed at home. This demonstrates that a high number of Kenyans are prone to tobacco-related NCDs such as hypertension and other CVDs

# :black_nib: Acknowledgements
## Citation
-Davide Chicco, Giuseppe Jurman: Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone. BMC Medical Informatics and Decision Making 20, 16 (2020). (link)

# Provenance
## SOURCES

[VIEW SOURCE ](https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records) or <https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records>

## COLLECTION METHODOLOGY
Please refer to source.

## License
**Attribution 4.0 International (CC BY 4.0)**

