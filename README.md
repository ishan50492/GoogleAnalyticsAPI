# GoogleAnalyticsAPI
Accessing data from Google Analytics API


Steps:

1. Enable the API

Create a project or open existing project in the Google Analytics console. Once you have opened the project, go to the corresponding API for example, Google Analytics API. Now, enable the API.

Create credentials

Open the Credentials page.
Click Create credentials and select OAuth client ID
For the Application type select Other.
Name the client ID quickstart and click Create.
From the Credentials page click into the newly created client ID, and click Download JSON and save it as client_secrets.json; you will need it later in the tutorial.

2.Install the dependencies: 

  a.pip3 install --upgrade google-api-python-client
  b.pip3 install --upgrade oauth2client

3.Manually supply the VIEWID for a particular client along with the desired start and end dates.

4.Run the script in order to get the desired output.

