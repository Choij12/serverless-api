# serverless-api

## Problem Domain:
- Create a serverless REST API
- Create a single resource REST API using a domain model of your choosing, constructed using AWS Cloud Services

## Routes & Inputs & Outputs: 

- POST - /people - Given a JSON body, inserts a record into the database
returns an object representing one record, by its id (##)
- GET - /people - returns an array of objects representing the records in the database
/people/## - returns an object representing one record, by its id (##)
- PUT - /people/## - Given a JSON body and an ID (##), updates a record in the database
returns an object representing one record, by its id (##)
- DELETE - /people/## - Given an id (##) removes the matching record from the database
returns an empty object

## UML 

![](UML.png)
