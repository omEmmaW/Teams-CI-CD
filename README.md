# Teams-CI-CD

# Notes

## CD

1. Change npm ci to npm install to avoid package-lock.json problem
2. The AZURE_SERVICE_PRINCIPAL_NAME is the client id instead of the display name
3. For private repos, you can only create repository secret. For public repos, you can create environment and then add secret inside
4. If "scheduler" package problem, then just npm install scheduler, and then install the scheduler package again inside of the tabs folder

## CI

# Work Logs

---------CD testing----------------

try to use workflow after correct login in accounts

try for deleting all of environment secrets to see if it's their issue

try for creating repository secret

updated variables to test if error resolve

updated secret to client id

change name to client id, secrets to secrets

---------CD working now---------

---------CI testing-----------------

created dev branch and task 1 branch, testing CI

---------CI working now----------

cicd testing task_2

---------Provision testing---------

used az login for service principal
