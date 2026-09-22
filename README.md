Exp_05: Risk-assessment
Name: MOogethshivan G G 
Reg No: 212225040259
AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL
Objective
To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events and identifying important audit information such as user identity, event name, event time, AWS service, region, and operation status.

Requirements
AWS Account

Web Browser

Internet Connection

Amazon S3 access

AWS CloudTrail

PART A — ACCESS AWS CLOUDTRAIL
Step 1: Login to AWS

Open the AWS Management Console.

Sign in using your AWS account.

In the AWS search bar, type CloudTrail.

Select AWS CloudTrail.

<img width="806" height="413" alt="image" src="https://github.com/user-attachments/assets/46232258-dc44-4573-83d1-8d3775ca54aa" />

Step 2: Open Event History
In the CloudTrail navigation menu, select Event history.

CloudTrail displays recent AWS activity.

Review the available events.

The Event History page may display information such as:

Event time

Username

Event name

Event source

Resource type

Resource name

<img width="820" height="407" alt="image" src="https://github.com/user-attachments/assets/bf4561b4-ccbc-4900-9d8c-f6d4805a9af7" />

PART B — ANALYZE A CLOUDTRAIL EVENT
Step 3: Select an Event
From the Event History list, select an S3-related event.

Click the event to open its details.

Examine the event information and the event record/JSON.

For this experiment, a CreateBucket event can be used.

Step 4: Analyze the CreateBucket Event
The CreateBucket event indicates that an Amazon S3 bucket creation operation occurred.

Record the following information:

Meaning of Important Fields

<img width="815" height="357" alt="image" src="https://github.com/user-attachments/assets/6c2e14c8-1b4a-4aaa-9c91-ecbbf36f1c81" />
<img width="821" height="408" alt="image" src="https://github.com/user-attachments/assets/eedd5cdc-5c3f-4d28-ad3c-d8ffe0f9af6b" />

PART C — IDENTIFY ANOTHER CLOUDTRAIL EVENT
Step 5: Select Another Event
Return to CloudTrail → Event history.

Select another event.

Open its details.

Record the important fields.

For example, an event such as:

AutomatedDefaultVpcCreation

may be present.

This event is associated with Amazon EC2.

Step 6: Analyze the Second Event
Record:

<img width="832" height="678" alt="image" src="https://github.com/user-attachments/assets/06552445-3175-4748-99c4-31bda1e24698" />
<img width="808" height="402" alt="image" src="https://github.com/user-attachments/assets/a29ffd87-66bc-4d3b-8d5d-d2933be00c50" />

PART D — COMPARE THE EVENTS
Step 7: Prepare the Audit Comparison
Compare the two CloudTrail events.

<img width="830" height="417" alt="image" src="https://github.com/user-attachments/assets/6216deb0-51fc-41e2-95d2-31380366ccc8" />

PART E — SECURITY AUDIT ANALYSIS
Step 8: Identify Who, What, When and Where
For each event, identify:

WHO?
Who or which identity performed/generated the activity?

WHAT?
What AWS operation was performed?

WHEN?
At what date and time did the activity occur?

WHERE?
In which AWS Region did the activity occur?

RESULT?
Was the operation successful or did it generate an error?

Step 9: Prepare the Final Audit Table
Students should prepare a final table similar to the following:

<img width="832" height="275" alt="image" src="https://github.com/user-attachments/assets/142068ac-c6f0-4ebb-ad4a-dca82be84d4a" />

PART F — SCREENSHOTS TO SUBMIT
Students should capture the following screenshots:

AWS CloudTrail Dashboard

CloudTrail Event History

CreateBucket Event Details

Second CloudTrail Event Details

Final Audit/Observation Table

RESULT
The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. Different AWS events were examined based on event time, user identity, event name, event source, AWS Region, read-only status, and error status. The experiment demonstrated how AWS CloudTrail provides an audit trail for monitoring, accountability, and investigation of cloud activities.
