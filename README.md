![image](https://github.com/femidata/Nigeria-s-Election-2023/assets/54317999/191bf7af-b353-47f8-b52b-d57c667db7a7)

# <p style="background-color:#008000; font-family:newtimeroman; color:#FFF9ED; font-size:250%; text-align:center; border-radius:8px 50px;">NIGERIA'S ELECTION 2023</p>
## <p style= "font-family:newtimeroman; color:#008000; font-size:150%; text-align:center; border-radius:8px 50px;">(Data Mining Process))</p>

### <p style="font-weight: bold; font-size:30px; color:green; text-align:justify">Introduction</p>
Nigeria is western African country regarded as the country with the largest economy in Africa. The country is said to have an estimated population of over two hundred and thirty million <b>(230,000,000)</b> people.
Nigeria is a republic that practices the democratic type of government, hence why an election is held every four (4) years to elect government officials that will be in charge of running the country for the next four (4) years. The 2023 general election is one of the elections which held the of 25th of February, 2023.<br><br>

The project will be divided into three (3) parts namely;<br><br>

1. Data Scraping - The data will be scrapped in this session
2. Exploratory Data Analysis (EDA)
3. Data Visualization in Power BI 

## <p style="font-weight: bold; font-size:30px; color:green; text-align:justify">Dataset</p>
It is not news that access to public dataset in Nigeria is almost non-existent, as no public organizations readily provide downloadable datasets to the public. infact, it took a hours of using [google](www.google.com) to search for the dataset before getting this website that offers the closest thing to the 2023 general elections data.
The dataset for this project is gotten from [civichive](https://civichive.org/)  at https://liveresults.civichive.org/. However, it is not readily available for download so scrapping the website API is the only option to get the required dataset. This webscrapping of API is the focus of the first part of project.  

The APIs used for this analysis was gotten from the aid of the developer mode of the browser used ([Brave Browser](https://brave.com/))

The following are the links to the APIs
- State Information - https://liveresultsapi.civichive.org/api/v1/states
- Party Information - 'https://liveresultsapi.civichive.org/api/v1/party'
- Presidential Election - https://liveresultsapi.civichive.org/api/v1/election/presidential/2023/data
- Gubernetorial Election - https://liveresultsapi.civichive.org/api/v1/election/gubernatorial/2023/data
- Senatorial Election - https://liveresultsapi.civichive.org/api/v1/election/senatorial/2023/data
- House of Representatives Election - https://liveresultsapi.civichive.org/api/v1/election/reps/2023/data

Before scrapping begins, all required libraries will be imported.
