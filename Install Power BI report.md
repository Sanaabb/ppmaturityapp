# Deploy Power BI Report

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

	b.	Select the downloaded template: *"Maturity Assessment Report.pbit"*. and paste the environment URL, then **Load**.
**Note:** Paste only the root URL without the prefix “https://”. Example: orgfxxxxxx.crm.dynamics.com

	c.	Sign-in with your organizational credentials, then **Connect**.

	d.	Save the report and click on **Publish**. Select the group workspace.

5.	Create a dashboard

	a.	From the **Power BI Service**, go to the group workspace.

	b.	Select the dataset and go to Settings.

	c.	On **Data source Credentials** Section, click on **Edit credentials** and define the **Privacy Level** to **Organizational**, then **Sign-in**.

	d.	Go back to the group workspace and click on the report.

	e.	Click on (**…**) *More Options*, then **pin to a dashboard**.

	f.	Select **New Dashboard** and give it a name. Ex.: *Maturity Assessment Dashboard*. Then click on **Pin Live**.

6.	Final step! embed the report into your application.

	a.	Edit the **Power Platform Assessment App** (canvas), either on: 

	   i.	 [Power Apps embed in Teams](https://docs.microsoft.com/en-us/powerapps/teams/manage-your-apps) if using Dataverse for Teams

	OR

	ii.	https://make.powerapps.com if using Microsoft Dataverse.

	b.	Navigate to the **Analytics** Screen at the bottom of the **Tree view** (scroll down).

	c.	Click on **Choose the workspace…you want to connect to**.

	d.	Select the **workspace**, **Dashboard** and **Tile**.
