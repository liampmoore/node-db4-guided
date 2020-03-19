# Data Modeling Notes

## Requirements

A client has hired you to build an API for managing `zoos` and the `animals` kept at each `zoo`. The API will be used for `zoos` in the _United States of America_, no need to worry about addresses in other countries.

For the `zoos` the client wants to record:

- name.
- address.

For the `animals` the client wants to record:

- name.
- species.
- list of all the zoos where they have resided.

Determine the database tables necessary to track this information.
Label any relationships between table.


## A good data model

- A game of abstraction, removing all the properties you don't care about
- Capture ALL relevant information
- Capture ONLY relevant information
- Reflect reality
- Is flexible, can evolve with the system
- Guarantee data integrity, without sacrificing too much performance

## Components

- Entities (noons) ---> resources in REST ---> tables
- Properties --> columns
- Relationships --> foreign keys

## Workflow

- Identify entities (noons) ---> resources in REST ---> tables
- Identify properties --> columns
- Identify relationships --> foreign keys

## Relationships

- One to one: rare
- One to many: very commin
- Many to many is a trick


## Mantra
- Every table should have a primary key
- Work on two or three entities at a time
- 