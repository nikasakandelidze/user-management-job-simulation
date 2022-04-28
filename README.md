# User management API ( Job simulation )
In this project you will have to complete several tasks ranking from:
- Easy( debugging existing code and fixing some simple bug )
- Hard( Implemented whole use-case of some feature: Design API, design Database structure, design a usecase architecture of components,
Test it ).

# General project info
This project is a user management system(backend API), just like any user management mechanism present in nearly all
the platforms nowadays.
So completing this project, will without a doubt give you production/real work level knowledge of
user management systems.

!!! There projects are all about giving you real work like experience, so follow setup guide to get to work the project locally
and dive into understanding, learning different libraries/technologies used, reviewing some components of the code, etc!!!

# Overview of Features/requirements to complete/implement from scratch 
### Already existing( but not necessarily completed ) features ( might need refactoring, bug-fix or a full implementation )
- add a new User with specified fields
- filter user list using different filtering mechanisms,
- Get info of a user with specified id
- update info of a user with specified id
- Associate new role with a user
### Possible features to implement from scratch
- Add layered architecture for better decomposition and readability
- Add validations to all the features/services
- Ability to add new role to the list of possible roles for users ( like: ADMIN, CLIENT)
- Ability to filter/list roles, using a defined filter properties in the issue
- Ability associate any existing user with any number of roles

All the Nitty-gritty details of all these features are explained in the corresponding opened issues on the Github.

# Technologies used
- [Python](https://docs.python.org/3/): Python programming language
- [FastAPI](https://fastapi.tiangolo.com/): Modern reactive/asynchronous framework for implement REST API-s, kind of a nodejs runtime but for python
- [PostgresSQL](https://www.postgresql.org/docs/current/index.html): Very popular and battle tested Relational type of database
- [SQLAlchemy](https://docs.sqlalchemy.org/en/14/tutorial/): Very( probably most ) popular Database driver/connector/ORM library for python and Relational db-s.
- [Alembic](https://alembic.sqlalchemy.org/en/latest/): Popular database migration tool, which is battle tested by the community and used in production environments.
- [Docker](https://docs.docker.com/get-started/): Containerization mechanism to easily test, deploy and orchestrate application units.