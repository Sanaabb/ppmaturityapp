# Deploy the Maturity Assessment Report (Power BI)

## Prerequisites

•	You must have a Microsoft Power BI Pro license to configure and publish the report.

•	Sign into Power BI and create a workspace to publish the report. 

## Configure the Maturity Assessment Report

1.	Download the report template.

2.	Configure the Power BI Service:

	a.	Connect to PowerBI.com and [create a group workspace](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-create-the-new-workspaces#create-one-of-the-new-workspaces) OR use an existing one.

	b.	[Add team members](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-give-access-new-workspaces) who will need access to the report. Ensure that every member has a Power BI Pro license.

3.	Get the environment URL: There are 2 scenarios according to the installation option.

	a.	Option 1: [Get the environment URL from from Microsoft Dataverse for Teams](https://docs.microsoft.com/en-us/powerapps/teams/view-table-data-power-bi#step-1-get-the-environment-url)

	OR

	b.	Option 2: [Get the URL from a Microsoft Dataverse environment](https://docs.microsoft.com/en-us/powerapps/maker/data-platform/data-platform-powerbi-connector?msclkid=a39d51caaedf11ec966ba0a99d1a393d#find-your-dataverse-environment-url)


4.	Configure the report from the template:

	a.	Open [Power BI Desktop](https://www.microsoft.com/en-us/p/power-bi-desktop/9ntxr16hnw1t?msclkid=4476f116aee011ecaaa543dea269ce9d&activetab=pivot:overviewtab), click on **File**, **Import**, then **Power BI template**.
	
	![image](https://user-images.githubusercontent.com/44406188/160500351-c0fb5dd7-313d-4072-af35-3f078e59e6c7.png)


	b.	Select the downloaded template: *"Maturity Assessment Report.pbit"*. and paste the environment URL, then **Load**.

	**Note:** Paste only the root URL without the prefix “https://”. Example: orgfxxxxxx.crm.dynamics.com
	
	![image](https://user-images.githubusercontent.com/44406188/160500391-ebd80eef-99a7-499d-8390-b0c3a5ee764c.png)


	c.	Sign-in with your organizational credentials, then **Connect**.

	d.	Save the report and click on **Publish**. Select the group workspace.
	
	![image](https://user-images.githubusercontent.com/44406188/160500450-253ecbd9-b905-491d-bc1a-a804fd171fd7.png)
	
	![image](https://user-images.githubusercontent.com/44406188/160500481-4b774dd1-59c0-4695-aefe-210f9775ddc3.png)



5.	Create a dashboard

	a.	From the **Power BI Service**, go to the group workspace.


	b.	Select the dataset and go to Settings.
	
	![image](https://user-images.githubusercontent.com/44406188/160500548-d7bfeba8-250e-4b6d-8059-c7599a9e5880.png)


	c.	On **Data source credentials** Section, click on **Edit credentials** and define the **Privacy Level** to **Organizational**, then **Sign-in**.
	
	![image](https://user-images.githubusercontent.com/44406188/160500584-f1b7db76-87b8-41c6-afc4-d9da22ac7d9e.png)
	
	![image](https://user-images.githubusercontent.com/44406188/160500604-f01dc6f4-57f2-4d07-977b-cd74caa54dff.png)


	d.	Go back to the group workspace and click on the report.

	e.	Click on (**…**) *More Options*, then **pin to a dashboard**.
	
	![image](https://user-images.githubusercontent.com/44406188/160500653-354b45a2-ded8-46fd-aae6-158c38e9aca8.png)


	f.	Select **New Dashboard** and give it a name. Ex.: *Maturity Assessment Dashboard*. Then click on **Pin Live**.
	
	![image](https://user-images.githubusercontent.com/44406188/160500674-05dbb6b3-21e3-4ba5-bfc6-e96bca6695a3.png)


6.	Final step! embed the report into your application.

	a.	Edit the **Power Platform Assessment App** (canvas), either on: 

	   i.	 [Power Apps embed in Teams](https://docs.microsoft.com/en-us/powerapps/teams/manage-your-apps) if using Dataverse for Teams

	OR

	ii.	https://make.powerapps.com if using Microsoft Dataverse.

	b.	Navigate to the **Analytics** Screen at the bottom of the **Tree view** (scroll down).
	
	![image](https://user-images.githubusercontent.com/44406188/160500712-a33051a4-e7ec-4d21-89a5-ae8f5924f022.png)


	c.	Click on **Choose the workspace…you want to connect to**.
	
	![image](https://user-images.githubusercontent.com/44406188/160500736-dce5f240-895a-4a25-9568-75d4858fef7b.png)


	d.	Select the **workspace**, **Dashboard** and **Tile**.
	
	![image](https://user-images.githubusercontent.com/44406188/160500752-7f54a7a7-a6dd-4f44-87eb-5bc4b37e8139.png)

