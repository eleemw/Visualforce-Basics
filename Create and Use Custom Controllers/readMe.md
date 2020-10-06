# Create a Visualforce page displaying new cases
Create a Visualforce page that uses a custom controller to display a list of cases with the status of 'New'.

Challenge Requirements
* The page must be named **NewCaseList**
* The custom controller Apex class must be named NewCaseListController and include the following:
    * A publicly scoped method named **getNewCases**
    * Use the return type of **List<Case>**
    * Return a list of case records that includes the **ID** and **CaseNumber** fields
    * Filter the results returned to only have a status of **New**
* The NewCaseList Visualforce page must use an **apex:repeat** component, which is:
    * Bound to **newCases**
    * Refers to the var attribute as **case**
    * With the component tags, bind an **apex:outputLink** component to the **ID** of the case. This will cause the the page to direct the user to the detail page of the respective case record.