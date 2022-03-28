# Option 1: Install the App using Microsoft Dataverse for Teams

This article provides step-by-step instructions for deploying the Maturity Assessment App solution.

Estimated time to complete these steps: 30 minutes.

## Prerequisites
To perform the installation:

 - You need an M365 subscription with Microsoft Power Platform and Teams
   capabilities (excluding plans from EDU A1).

## Installation steps
You need to perform these 5 steps: 
 1. Download the app solution package
 2. [Install the Power Apps personal app in Teams](https://docs.microsoft.com/en-us/powerapps/teams/install-personal-app)
 3. Create your Microsoft Dataverse for Teams environment:
a.	Click on **Start now**, then select the Microsoft Teams group you want to add the solution to. Finally click on **Create**.
b.	Once the Studio is opened, name your app *“MyFirstApp”*, click on **Save** then select the **Back** button

**Note:** This operation will open the Power Apps Designer Studio to create an app. This step is required to activate your Microsoft Dataverse for Teams environment for the selected group and to enable the import solution experience.
 

4.	Import the solution:
a.	On the Power Apps app in Teams, select **Build**, then select the team where you activated the Dataverse for Teams environment.
b.	Select **See all**
c.	Click on **import** -> **import solution**
d.	Click on **Browse**. Select the package you downloaded *MaturityAssessementTool_x_x_x_x_managed.zip*, then click on **Next**.
e.	Select **Import**
f.	Once the solution has been successfully imported, click on **Build**, then **Installed apps** and finally **See all**.
g.	Select the **Power Platform Assessment Tool app**, then **Add to Teams**.
h.	Click on **Add**.
i.	**Pin** it to your left menu.

 
 
 
5.	Load data
a.	On the app home page, click on **Data Loader** button.
b.	Click on **Load Data** button. This operation will download the required data to start your assessment.
c.	Once data is loaded, go back to the **home page**, and **take the assessment**.
 

You are now ready to use the app !
One final step is required to integrate the Analytics report: 
