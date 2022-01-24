# Alert Status Workflow

    Introduction
   
This document addresses the alerts as follow up workflows to status responses based on customized business rules. For a particular response or condition, an alert is raised. An alert is designed to attract your attention to unusual or unwanted issues so that you are aware of potential problems as soon as possible. Then, the cause of the issue can be investigated, and hopefully, resolved. 

>Purpose of the Document
>>This document provides detailed information on the different alert statuses and the requested behavior, and the setting up of an alert.
The description of this process is intended for implementers, administrators, consultants, or whoever feels the need to understand the alerting process to set up a notification in the system based on responses. 

<ol>
 <li>Terms and Definitions
  <ol>
   <li>Term</li>
</ol>
    
Definition
Alert
Business rule based on a response or condition. For instance, response = A or response < B.
Alert System / Alerting
Being able to identify a business condition and notify a designated person within the Company of the existence of such condition and the need for it to be responded to.
Associate
The position that a person occupies in a company such as a manager or a customer representative.

Functional Description
The systems measure the interaction between an alert and an associate. When an action is processed by the system, business rules are applied to said data to alert the associate of certain circumstances. For instance, when a response is equal to A.

When an alert comes in, it sets off a notification to a person associated with that business unit; it could be a manager or group of employees. This notification can be delivered by email, SMS, or other configured ways. 
Depending on the business rules, that notification needs to be responded to in a configured period of time. For instance, if it is a “Close the Loop” situation, the business rule may be configured to take a particular action within a 48hs period.  

This process is solution-oriented. When a certain response or condition is provided, an instant alert is triggered so that action can take place ASAP if needed. To accomplish it, two workflows should be taken into consideration (Refer to sections 2.1. and 2.2. for more information). 

Alert Status
The alert workflow has a set of statuses that depict its position in the process; these statuses may vary upon the business rules configured. The alert workflow is the process of raising, responding, and closing the alert.
That is to say, the workflow can be modified if needed; for this action, proper privileges have to be granted to the person making the modifications.

Status
Description
Open
When an alert gets triggered and is active.
In Progress
When an alert is assigned to an associate.
Escalated
The alarm was in the Open status for an unacceptable amount of time and so has been escalated. 
Under Review
The alarm is being reviewed by an associate. 
Resolved
When an alert was under the Escalated status and is now solved.
Closed
When an alert is solved. It closes the interaction.



The following is the most commonly used scenario of an alert status workflow:


 
Set Up Alert Workflow
Taking into account that when an alert is received, an action is triggered, a Company can follow the steps described below to set up an alert:

Define the condition that triggers the alert. 
Define actions to take place. For instance, set the action as under review status.
Define triggers. When will the action take place?
Associate. [optional] The person or role that is notified when needed. 
Alert type settings. 


----------------------- End of document -----------------------
