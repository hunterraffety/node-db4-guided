# Requirements

A client has hired you to track zoo animals.
For each animal, you must track that their name, species, and all zoos in which they have resided (including zoo name and address).

Determine the database tables necessary to track this information.

Label any relationships between table.

## whatever this stuff is above.

## a good data model

- captures all the data the system needs
- captures only the data the system will needs (abstraction goodness)
- reflect reality
- is flexible enough to evolve with the system
- guarantees data integrity
- is driven by the way data will be used

## components

- entities -> tables
- attributes -> columns
- relationships -> foreign keys

## mapping to rest concepts

- resource -> entity -> table
- properties > attributes -> columns
- subroutes (/users/:id/values) -> relationships -> foreign keys

## workflow

- identify entities (draw a square)
- identify relationships (draw lines ----->)
- identify attributes (bullet list of columns)

## relationships

- one to one - not so common
- one to many - super common
- many to many - fake

## mantras

- pick two entries at a time
- many to many -> third table
- one to many -> foreign key
- foreign key -> many sides
- many to many table can have extra information
