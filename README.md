This is a data science repository where in we first scrape the United States Deaprtment of Health Cancer website <b>https://seer.cancer.gov/statfacts/</b>.
We go through most of the cancer types and scrape the data available there into multiple excel files based on the type of data.
We then clean the data and do some basic data analysis on them.
</br>
We use Jupyter Notebook to do all the tasks. We make use of python with various libraries like BeautifulSoup for webscrapping, pandas, numpy, matplotLib and Seaborn for charts.
### Steps to use this repository.
1. Fork the repository
2. Clone the repository to your local system.
3. Open the <b>New Data Extraction</b> notebook and run it. This will create a folder "Cancer_Research" in the directory where you cloned the repository. In it four folders will be created. They are:
    1. Age_Data -- This folder will store the excel file for all the cancer types which has data relating to the age of a person.
    2. Ethnicity_Data -- This folder will store the excel file for all the cancer types which has data relating to the ethnicity of a person.
    3. Stage_Data -- This folder will store the excel file for all the cancer types which has data relating to the which stage the cancer has reached.
    4. Trend_Data -- This folder will store the excel file for all the cancer types over the years along with the modeled values.
    ![image](https://user-images.githubusercontent.com/37789394/209811444-a04c6d54-b2c4-40b5-9926-004454f2f6aa.png)

 4. Inside the "Cancer_Research" folder some excel files are also created. They are: 
    1. CancerList -- This excel file has the extensive list of all the cancer types data available in the United States Deaprtment of Health Cancer website.
    2. Age_Data_Complete -- This excel file has the consolidated data of all the data available in the Age_Data folder.
    3. Ethnic_Data_Complete -- This excel file has the consolidated data of all the data available in the Ethnic_Data folder.
    4. Stage_Data_Complete -- This excel file has the consolidated data of all the data available in the Stage_Data folder.
    5. Trend_Data_Complete -- This excel file has the consolidated data of all the data available in the Trend_Data folder.
 5. Open the <b>Detailed report on cancer New</b> notebook and run it. Once you run it you will be able to see all the insights we could find from the data.
 
 ![image](https://user-images.githubusercontent.com/37789394/209811083-edf86388-4504-4342-a0c1-cb126ee3d6b2.png)
 ![image](https://user-images.githubusercontent.com/37789394/209811136-7684c2c8-4db2-44d8-964d-c29cee372984.png)
 ![image](https://user-images.githubusercontent.com/37789394/209811235-fd414290-c79e-4158-b7e1-1b9a13d17cfc.png)

