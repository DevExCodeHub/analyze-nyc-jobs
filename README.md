# analyze-nyc-jobs

## Login to IBM Cloud and Create Watson Studio Service
1. Register in [IBM Cloud](https://ibm.biz/Bd29xn).
2. Go to **Catalog**.
3. Search for `watson studio`.
4. Click on the service and then **Create**.
5. On the service page, click on **Get Started**.

## Create New Project
1. Scrol down the page and click on **Create a project**.
2. Select **Starndard**, then click on **Create Project**.
4. Make sure a cloud storage instance exists, or add a new **IBM Cloud Object Storage** instance by clicking on Add under Select storage service.
5. Name your project 'Analyze NYC Jobs'.
6. Click **Create**.
7. In your project page, nagivate to the `Assests` tab, drag the [data set](https://github.com/DevExCodeHub/analyze-nyc-jobs/blob/master/data/NYC_jobs.csv) file and drop it in the Load sidebar.

## Create Dashboard
1. On the same Assets page, click on **(+) Add to project ** icon.
2. Click the **Dashboard** icon.
3. Name your Dashboard.
4. Click `Associate a Cognos Dashboard Embedded service instance`, make sure a 
Cognos Dashboard Embedded instance exists, or add a new **Cognos Dashboard Embedded** instance by clicking on create.
5. Click **Save**.
6. Select a template, `template with 5 sections prefered`.
7. Click **Create**
8. On left side, click on **Selected Sources(+) **
9. Select **Data Assets**, then select **NYC_Jobs.csv** and click on **Select**.

**Now you can build your own visulazation or just follow the instructor steps.**
