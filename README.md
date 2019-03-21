# PaaS ProberS Web Application (GCP App Engine)
This is the PaaS ProberS web application that was deployed on GCP App Engine using [this link](https://djangg.appspot.com/).

## Build/Run Instructions
1. In the root directory of this repository, run the command 'python manage.py runserver' to run the web application on localhost.
2. Go to [localhost](http://127.0.0.1:8000/) to view the web application.
3. For access the database contents, use the [Django admin page](http://127.0.0.1:8000/admin/pages/).

**Important Note:** Because this application stores data on a Cloud SQL instance in GCP, the data you submit will not be saved on your machine, even though the application is running on localhost.
