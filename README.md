An application called IPLookup,  to perform outbound REST Message to the application which uses the ipinfo.io public web service.

Preparation - View API Documentation
Visit the ipinfo.io and browse the documentation to see what is passed to the API and what is returned.

Create the IPLookup Application
Use the Application Navigator in the main ServiceNow browser window to open System Applications > Studio.
Click the Create Application button.
Click the Create button for the Start from scratch option.
Configure the new application:
        Name: IPLookup
        Scope: this value is automatically populated
Click the Create button.
When prompted to confirm application creation, click the OK button.
When the application creation is completed, click the Back to list button.
Click the link to the IPLookup application to open it for editing.
Create an Outbound REST Message
Create a REST Message.
In Studio, click the Create Application File button.
In the Filter… field enter the text REST OR select Outbound Integrations from the categories in the left hand pane.
Select REST Message in the middle pane as the file type then click the Create button.
Configure the REST Message:
        Name: IPInfo
        Description: Information about IP addresses
        Endpoint: https://ipinfo.io/
        Authentication type: No authentication
IPInfo message

Click the Submit button to save the REST message.

NOTE: The ipinfo.io public web service does not require authentication.
