# Option 1: Install the App using Microsoft Dataverse for Teams

This article provides step-by-step instructions for deploying the Maturity Assessment App solution.

Estimated time to complete these steps: 20 minutes.

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
    
    ![image](https://user-images.githubusercontent.com/44406188/160390449-2dc88dc2-633c-4bb4-8485-28add757351b.png)
    
    b.	Once the Studio is opened, name your app *“MyFirstApp”*, click on **Save** then select the **Back** button

![image](https://user-images.githubusercontent.com/44406188/160390527-e753761f-116d-4a41-a700-bb67819816e7.png)

**Note:** This operation will open the Power Apps Designer Studio to create an app. This step is required to activate your Microsoft Dataverse for Teams environment for the selected group and to enable the import solution experience.

 ![image](https://user-images.githubusercontent.com/44406188/160390549-3cec8231-79a9-4f2a-8b4e-b48d1642dc68.png)


4.	Import the solution:

    a.	On the Power Apps app in Teams, select **Build**, then select the team where you activated the Dataverse for Teams environment.
    
    b.	Select **See all**

    ![image](https://user-images.githubusercontent.com/44406188/160390602-db194f60-82e5-4f1a-80e7-15580802f442.png)

    c.	Click on **import** -> **import solution**

    d.	Click on **Browse**. Select the package you downloaded *MaturityAssessementTool_x_x_x_x_managed.zip*, then click on **Next**.

    e.	Select **Import**
    
    ![image](https://user-images.githubusercontent.com/44406188/160390629-669de59c-1cda-4ea6-a321-b4043d8ac28a.png)

    f.	Once the solution has been successfully imported, click on **Build**, then **Installed apps** and finally **See all**.
    
    ![image](https://user-images.githubusercontent.com/44406188/160391237-f17f6fd0-559e-428e-8f18-14b9eda0f2a5.png)


    ![image](https://user-images.githubusercontent.com/44406188/160390690-81850e30-ef73-4026-adbd-1c20bc6db2bc.png)

    g.	Select the **Power Platform Assessment Tool app**, then **Add to Teams**.
    
    ![image](https://user-images.githubusercontent.com/44406188/160390800-3b9d8698-8cf4-4e5a-bc20-c2b2ee85eafb.png)
    
    h.	Click on **Add**.
    
    i.	**Pin** it to your left menu.

    ![image](https://user-images.githubusercontent.com/44406188/160390843-47a75145-8d2c-42ed-afa8-fe3999b04019.png)

    ![image](https://user-images.githubusercontent.com/44406188/160390900-05b0f423-b6d4-4d0c-8579-81aa0f0d8525.png)

 
5.	Load data

    a.	On the app home page, click on **Data Loader** button.
    
    ![image](https://user-images.githubusercontent.com/44406188/160390935-b78ae0f9-c099-4c83-bf29-8a123e5c2140.png)

    b.	Click on **Load Data** button. This operation will download the required data to start your assessment.
    
    ![image](https://user-images.githubusercontent.com/44406188/160390969-6efd5d19-194d-4a50-931e-f389060c7717.png)

    c.	Once data is loaded, go back to the **home page**, and **take the assessment**.
 
    ![image](https://user-images.githubusercontent.com/44406188/160390996-12d25233-479a-4065-8ca5-5d4a89c556c6.png)


You are now ready to use the app !

One final step is required to integrate the Analytics report: [Deploy the Maturity Assessment Report.](/Deploy%20the%20Assessment%20Report%20(Power%20BI).md)

## Explore all documentation

- [Introduction to the Power Platform Assessment App](/README.md)
- [Option 1: Install the app using Microsoft Dataverse for Teams environment.](/Option1%3A%20Install%20with%20Dataverse%20for%20Teams.md)
- [Option 2: Install the app using Microsoft Dataverse.](/Option2%3A%20Install%20with%20Microsoft%20Dataverse.md)
- [Deploy the Maturity Assessment Report.](/Deploy%20the%20Assessment%20Report%20(Power%20BI).md)

