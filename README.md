## Database composer

This repo is used to create a random dataset for training our Machine Learning model.

I could not find an example dataset with the fields I need. So I am using a few datasets to create the one I want.

### Application

I need to create "users", "tasks" and "completed_tasks" tables in PostgreSQL.

Users table will be fulfilled with this API: https://randomuser.me/api/

For "tasks" table, I will write some functions in this python script.

For "completed_tasks" table, /data/jira_data.csv includes some create and complete dates that I will use.

## How to use

Create `database.ini` file in the main directory.

Put the content in it:

```
[postgresql]
host=localhost
database=project-genie-training
user=postgres
password=postgres
```
