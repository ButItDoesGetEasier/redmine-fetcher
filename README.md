Running Instructions:

1. Install Tika-Python
   - Install Java 7+
   - Run "pip install -r requirements.txt"
 2. Ensure that REST API is enabled for the Redmine project. Note of your API key or username and password. See https://www.redmine.org/projects/redmine/wiki/Rest_api for more information.
 3. Run the "redmine_fetch.py" file
 4. Enter the Redmine URL used by the organization, or leave it blank for the default
 5. Enter credentials. If the project to fetch is Redmine, any credential will do as it is a public project.
 6. Enter project ID of project to fetch
 7. Choose which tracker to fetch or if all issues will be fetched
 8. The files would be saved under db/ with the database and table name of the tracker or "complete" if all issues were fetched

Notes:

1. The "db_methods.py" file can be used to check the contents of an existing database
2. If fetching was stopped, it can be run again and only unfetched issues would be added
