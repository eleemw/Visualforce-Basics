# Create a Visualforce form which inserts a basic Contact record
Using the Visualforce apex:form component, create a page which will insert a Contact record based on First Name, Last Name and Email. After submitting the form, the user should be redirected to detail page of the new Contact record.
**Challenge Requirements**

* The page must be named **CreateContact**
* It must reference the **Contact** standard controller
* It must use a Visualforce **apex:form** component
* It must have three **apex:inputField** components bound to the following Contact fields:
     * **First Name**
     * **Last Name**
     * **Email**
* It must have an **apex:commandButton**  component that uses the save method from the standard controller