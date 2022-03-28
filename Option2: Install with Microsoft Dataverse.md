# Option 2: Install the App using Microsoft Dataverse 

This article provides step-by-step instructions for deploying the Maturity Assessment App solution.

Estimated time to complete these steps: 20 minutes.

## Prerequisites
To perform the installation, you should be either a:

 - Global administrator  
 - or Microsoft Power Platform administrator 
 - or a Power Platform environment System Administrator.

## Installation steps
You need to perform these 5 steps: 

1.	Download the app solution package.

2.	Use an existing environment with Microsoft Dataverse or [create a new one](https://docs.microsoft.com/en-us/power-platform/admin/create-environment?msclkid=aeeebf7aae9b11ec95a556b758b23ebc#create-an-environment-with-a-database).

3.	Import the solution

	a.	Select **Solutions** then **Import**
  
 	 ![image](https://user-images.githubusercontent.com/44406188/160414114-ff4534e6-b0f6-4461-aec8-6e5c735015ed.png)


	b.	Click on **Browse**. Select the package you downloaded MaturityAssessementTool_x_x_x_x_managed.zip, then click on **Next**.
	
	![image](https://user-images.githubusercontent.com/44406188/160414241-ed80cc78-e021-453d-9354-f780d4d5ce71.png)


	c.	Click on **Import**

4.	Launch the app (canvas app)

	a.	Once the solution has been successfully imported, go to **Apps**.

	b.	Click on **Power Platform Assessment Tool** (canvas).
	
	![image](https://user-images.githubusercontent.com/44406188/160414375-ec6b0549-3470-4bf2-94eb-53681fdaad9c.png)


5.	Load data

	a.	On the app home page, click on **Data Loader** button.
	
	![image](https://user-images.githubusercontent.com/44406188/160414415-73e34957-5a21-4133-ad1d-13a35a26c954.png)


	b.	Click on **Load Data** button. This operation will download the required data to start your assessment.
	
	![image](https://user-images.githubusercontent.com/44406188/160414456-de3c4d57-66f6-4ade-a104-de067ea933d4.png)


	c.	Once data is loaded, go back to the **home page**, and **take the assessment**.

	![image](https://user-images.githubusercontent.com/44406188/160414493-6d59a198-13d0-4bad-9602-c871b84556f6.png)


You are now ready to use the app.
One final step is required to integrate the Analytics report: 
