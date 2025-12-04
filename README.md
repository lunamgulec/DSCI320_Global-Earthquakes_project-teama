# TeamA - Global Earthquakes

## Describe your dataset in about 150-200 words

We selected a real-time earthquake dataset provided by the U.S. Geological Survey (USGS), a reputable U.S. government scientific agency known for its authoritative, open-access data on natural phenomena, such as earthquakes, volcanoes, water resources, and landslides. The USGS collects this data through a global network of seismic monitoring stations that continuously detect and record seismic activity from seismic events around the world. 

Our chosen dataset includes information about earthquakes, where each record represents an individual earthquake and its detailed attributes, such as location (`latitude`, `longitude`, `locationSource`, etc.), time of occurrence (`time`), magnitude (`mag`), depth (`depth`), event type (`type`), and more. The dataset is publicly available and can be accessed through the [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php), which provides live earthquake feeds that update every minute, and can be filtered/chosen per time range (past hour, week, or month). 

For this project, we downloaded a static version of “All Earthquakes” under “Per month” and will use only this single version for our project, which contains information about global earthquakes for the past 30 days, from the date accessed of October 23, 2025. This ensures consistency across our analyses, allows us to avoid confusion, unmatched data, or any discrepancies caused by real-time updates, and allows us to build reliable visualizations that reflect global earthquake trends.


## Describe your topic/interest in about 150-200 words

Our project explores global earthquake patterns through data analysis and interactive visualization. Our motivation is to understand trends in global earthquake data and transform this complex scientific data into clear, visually engaging insights that help people, regardless of their technical background, understand when and where earthquakes occur, how intense they are, and whether certain patterns emerge across regions or time.

We also aim to improve our own skills in data analysis and visualisation in Python (specifically Pandas and Altair) and storytelling skills. By combining Pandas and Altair in Python, we aim to apply the full data analysis process, from exploration to analysis to visualization, to communicate findings in an intuitive and interactive way, applying skills learned in our tutorials. Beyond identifying trends, we also want to highlight how data visualization can make abstract environmental phenomena more tangible and informative.

This topic also aligns with our shared interest in data-driven storytelling and visual analytics, while also leveraging our diverse backgrounds. With so much seismic data available everyday, and with earthquakes being unpredictable yet globally impactful events, our project aims to make the complex data more interpretable and engaging, demonstrate how open data can be used to raise awareness about natural hazards, and show the importance of accessible scientific communication.


## Team Members

- Luna Gulec: 4th year BCom student specializing in BTM (Business Technology Management) with a minor in Data Science. I am interested in global datasets, primarily being able to spot different geographic trends.
- Ericson Ho: 4th year BCS student. I am interested in analyzing and visualizing geographic and weather data to understand environmental patterns and inform real-world decision-making.
- Logan Wu: 4th year BSc Student specialising in Statistics. I am interested in exploring any data relations and data insights.
- Athena Wong: 4th year BCom student specializing in BTM (Business Technology Management) with a minor in Data Science. I am interested in exploring any datasets.


## Images

{You should use this area to add a screenshot of an interesting view, and eventually, of your dashboard}

<img src ="images/test.jpg" width="300px">

## Package requirements

- `altair`
- `pre-commit`
- `pandas`

## References

Class Tutorials



