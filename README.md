# Cobras

Practice for the tech assessment by building a full stack app that handles get and post requests.

# Setup Instructions

1. FORK! this repo
2. Clone the fork to your local machine
3. Make branch
4. Open pull request to upstream master

# Project Instructions

1. Create an express server
1. Add GET request route (/api/cobras) that responds similar to below:
[
{id: 1, name: 'bob', db:'sql', frontend: 'jquery'},
{id: 2, name: 'alice', db:'noSql', frontend: 'angular'},
...
]
1. POST request route (/api/cobras
1. Create a database connection to a noSQL db (Mongo at mLab recommended)
1. Create a database connection to a SQL db (SQLite recommended)
1. Create the following frontends
  1. Vanilla HTML / jquery
  1. Backbone
  1. angular
  1. React
1. Each frontend should
  1. Let the user select the database from which they want to pull (sql or noSql)
  1. Assign the frontend's type as the 'frontend' property for an object's being submitted
  1. Render any cobra objects on the database while indicating which db it came from
