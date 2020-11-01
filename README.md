# github-upload
# The whole Project consist of majorly four components on a Mule pallet 
•	HTTP Listener – It act as the Rest endpoint which will be exposed as an API. 
•	A validator – It will check that the query parameter should not be blank. 
•	Data weaver – It will transform the input string parameter and pass it into the SOAP webservice payload. It will also fetch the result from the SOAP response feed it to the logger.
•	Webservice consumer – it is going to act a SOAP webservice consumer which call the desired method which you need to call. 
•	Logger – It helps logging the message back as the API response 
Below if the High Level Workflow of the problem 
