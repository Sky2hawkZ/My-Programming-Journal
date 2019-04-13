# Notes

## What is CRUD

Within computer programming, the acronym CRUD stands for create, read, update and delete. These are the four basic functions of persistent storage. Also, each letter in the acronym can refer to all functions executed in relational database applications and mapped to a standard HTTP method, SQL statement or DDS operation.

It can also describe user-interface conventions that allow viewing, searching and modifying information through computer-based forms and reports. In essence, entities are read, created, updated and deleted. Those same entities can be modified by taking the data from a service and changing the setting properties before sending the data back to the service for an update. Plus, CRUD is data-oriented and the standardized use of HTTP action verbs.

## Common Crud Operations

| CRUD (Operation) | SQL    | HTTP           | RESTful   | Method Name             |
| ---------------- | ------ | -------------- | --------- | ----------------------- |
| Create           | INSERT | PUT/POST       | POST      | createServiceObjectName |
| Read(Retrive)    | SELECT | GET            | GET       | getServiceObjectName    |
| Update(Modify)   | UPDATE | PUT/POST/PATCH | PUT/PATCH | updateServiceObjectName |
| delete(Destroy)  | DELETE | DELETE         | DELETE    | deleteServiceObjectName |

Other variations of CRUD include:

* BREAD (Browse, Read, Edit, Add, Delete)
* DAVE (Delete, Add, View, Edit)
* CRAP (Create, Replicate, Append, Process)