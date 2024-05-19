# Care-Home-Management-Dashboard
Care Home Management Dashboard using PowerBi

The main objective of this dissertation work is to create a dashboard for monitoring the activities of inhabitants in a care-home facility. This major objective is accomplished by a series of minor objectives listed below:
● To create machine learning models for activity classification from sensor data.
● To compare the performance of models.
● To create an architecture for storing and retrieving data.
● To create a dashboard addressing all the business questions.

## SYSTEM DESIGN

The data is continuously published from the sensors attached to the inhabitants in the care home . The data is transformed using the standard encoder and is passed to the classification model. The classification model predicts the activity from the feature input and the activity along with the timestamp and unique ID is saved in the database. A dynamic dashboard is connected to the database and it serves for the user interaction. The database mainly collects and stores 3 different sorts of data. One holds information about the resident, another the sensor collected data i.e., activity tracking, and the third is manual data input by staff or carer in the care facility.

## ABOUT THE DATASET
Attaching sensors and collecting data in real time requires a lot of permissions and formalities, which is difficult to achieve at this point in time. Therefore, a plan is made to test the system as the vital element of the system is the dashboard. Data is key for testing the dashboard. The database needs to be populated with user data. But populating the database with mere fake data doesn't make sense. To make the data more meaningful, investigation is done to understand the pattern of user activities. The inhabitants of two care homes are observed for two weeks and activity patterns are noted. The observations are most of the time the inhabitants are either sitting or lying. The whole inhabitants can be grouped into three to four categories depending on their level of activities. It is also observed that an inhabitant pursues the same activity for ten to fifteen minutes of time. Also, there is a fixed time for giving food and medicines to the inhabitants. A series of fake data has been created keeping all these points in mind to make the data as real as possible. A month of fake activity data of 10 imaginary inhabitants is populated in the database. A python script is written for this purpose. The populated data is then used for visualisation with the dashboard connected to the database.

## ABOUT THE DASHBOARD
The dashboard is created mainly for care home management. 10 fictional residents' 1 month activity data and manually entered information by a carer or staff member are gathered and maintained in a database. The data is then automatically transferred from the database to the PowerBI platform and visually analysed. There are actually two dashboards. One dashboard i.e. the Main dashboard , that would display general information such as resident details, upcoming appointments, and a summary of their daily activities, including their intake of food and water and other bodily functions while the other dashboard i.e. the Individual dashboard  will display each resident's activity and other bodily functions over time.

Kindly check the project details doc and programming code pdf for more details
