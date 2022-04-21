# Power Platform Maturity Framework

**Maturity Framework** is based on the [Capability Maturity Model (CMM),](https://en.wikipedia.org/wiki/Capability_Maturity_Model) which originally grew out of work at Carnegie Mellon University. The principle is that if you could measure yourself against a clear set of standards to identify where your practices and capabilities stand, you could take concrete steps to take it to the next level. The model defined a scale of 5 levels, representing the levels:

**Level 100 - Initial**

**Level 200 - Repeatable**

**Level 300 - Defined**

**Level 400 - Capable**

**Level 500 – Leading**

For more information about [Maturity Model for Microsoft 365 - Introduction | Microsoft Docs](https://docs.microsoft.com/en-us/microsoft-365/community/microsoft365-maturity-model--intro)

Working with some of our top customers, we've identified consistent themes, patterns, practices, and behaviors to support the progress of organizations implementing a complete digital transformation with Power Platform. The result of this work is the [Power CAT adoption maturity model](https://powerapps.microsoft.com/en-us/blog/power-cat-adoption-maturity-model-repeatable-patterns-for-successful-power-platform-adoption/).


# Power Platform Maturity Assessment App

Based on the Power CAT adoption maturity model, we built the Power Platform Maturity Assessment App.

The purpose of **the Power Platform Maturity Assessment App** is to help you take a holistic view of the Power Platform adoption status and gain an understanding of the current state versus the desired state.

The basic idea is to empower people working with Power Platform to:

-   Understand their capabilities on multiple dimensions in a clearly defined scale
-   Decide what level they want to reach for each dimension and within what timeframe
-   Improve their capabilities in a tangible way by taking them to the next level
-   Compare the evolution of the organization based on quantified surveys.

**Project Team** : Amélie Lair, Sanaa Bahou, Pierre Bourdial, Nicolas Kirrmann, Mehdi El Yassir, Frédéric Penalver.

![app tool](https://user-images.githubusercontent.com/44406188/153434477-89b91899-450d-419b-a9cb-eae8df8c04b4.png)


## Licensing requirements
Either : 
 
 - Microsoft Teams through an M365 subscription (excluding EDU A1) with [Dataverse for Teams](https://docs.microsoft.com/en-us/powerapps/teams/overview-data-platform) enabled.

OR

 - Power Apps per User plan or Power Apps per App plan.
 
 AND
 - Power BI Pro license or Power BI Premium, if you'll be using the Power BI dashboard
   that's available as part of the solution.

Contact your local Microsoft account representative for questions related to licensing as per your requirements. See also: [Licensing overview for Microsoft Power Platform](https://docs.microsoft.com/en-us/power-platform/admin/pricing-billing-skus)

## Download the solution package

![solution package](https://user-images.githubusercontent.com/44406188/163870719-f53f64db-36db-4461-b594-50b3ab10b437.png)


The solution package is available for download in this repository.
It contains :

1. **MaturityAssessmentTool_1_0_0_X_managed.zip** : a compressed file including:

 - 2 apps:
 
  	- **Power Apps Assessment Tool**: a canvas app to help you evaluate your organization’s maturity around Power Platform adoption.
  
  	- **Power Platform Assessment Admin Console**: a model-driven app to help manage the data tables of the assessment including the disciplines, checklists, scores, roles…
		 
 - 9 Tables: where data is stored including Admin, AllupScore, Automation, BusinessValue, FusionTeams, Nurture, Roles, Strategy and Support.
 
 - DataImportTool : an environment variable used to automate data load.
 
![image](https://user-images.githubusercontent.com/44406188/160388527-0b09347d-500c-4ed7-8583-f7e7dc0c042a.png)


2. **Maturity Assessment Report.pbit** : the Power BI template to use within the app.


![download github](https://user-images.githubusercontent.com/44406188/163870894-b6710cec-d62e-4f91-a188-0157a5a03650.png)



## Install the application

The procedure to install the Maturity Assessment App is described in the following sections. 2 options are possible according to the type of licenses you have:

 - [Option 1: Install the app using Microsoft Dataverse for Teams environment.](/Option1%3A%20Install%20with%20Dataverse%20for%20Teams.md)
 - [Option 2: Install the app using Microsoft Dataverse.](/Option2%3A%20Install%20with%20Microsoft%20Dataverse.md)
 
To know more about the difference between these 2 environments: [Dataverse for Teams vs. Dataverse](https://docs.microsoft.com/en-us/powerapps/teams/data-platform-compare).

## Deploy the Maturity Assessment Report (Power BI)

The procedure to install the report is described in the following section : [Deploy the Maturity Assessment Report](/Install%20Power%20BI%20report.md).

