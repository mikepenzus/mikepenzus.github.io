## FreeSlots — Privacy Policy
FreeSlots use of information received from Google APIs will adhere to the Google API Services User Data Policy, including the Limited Use requirements.
the idea behind this workspace add-on is to be able to create a native apps script container bound project (attached to a google sheet) and use the doGet and doPost functions to receive & log incoming data as form of a webhook.

### your personal data
- does not leave the add-on window inside your workspace
 is not accessed by, used, stored or shared with anyone else (including the developer of this add-on) except you

### this add-on does
retrieve an OAuth token by means of the ScriptApp.getOAuthToken() function but only to make authenticated api requests to google apps script's rest apis
makes use of the properties services to store document and script related data (example: script id, script version number, url of the web app deployed etc.)
connects to external services using UrlFetchApp
uses 1 non-sensitive scope
and 3 sensitive scopes

### scopes
the add-on will make use of a following scopes -
https://www.googleapis.com/auth/spreadsheets.currentonly — this scope will be used to A) read the sheet id which will in-turn be used to create a container-bound apps script project using this endpoint B) store, update & retrieve document and script related data in the properties services
https://www.googleapis.com/auth/script.external_request — this scope will be used to A) make API requests to the apps script rest apis that will help create, update and deploy a container-bound apps script project and B) to fetch open-source code that can be used to update the newly created container-bound apps script project
https://www.googleapis.com/auth/script.projects — this scope will be used to create, update and deploy a container-bound apps script project using this endpoint
https://www.googleapis.com/auth/script.deployments — this scope will be used to deploy the script as a web-app using this endpoint, which will in turn be used as a webhook to receive and log incoming data from external services
a more detailed explanation of what these scopes make use of can be found in the images displayed here.

### contact
Michele Penzo - all modes of contact can be found here
email: mikeautobot88@gmail.com
