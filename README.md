# Finals Lab Task 6 MOngoDBCRUD

In this activity we need to create database, insert documents, Query / Find Documents, Update Documents, Text Search, Delete Documents.

## Create database
Connect to a running mongo instance, use a database named `mongo_practice`.
use mongo_practice

## QUERY OR FIND DOCUMENTS

-	Get all documents

<img src="images/pic 1.png" alt="Alt Text" width="600">

- Get all documents with `writer` set to "Quentin Tarantino"

<img src="images/pic 2.png" alt="Alt Text" width="600">

- Get all documents where `actors` include "Brad Pitt"

<img src="images/pic 3.png" alt="Alt Text" width="600">

- Get all documents with `franchise` set to "The Hobbit"

<img src="images/pic 4.png" alt="Alt Text" width="600">

- Get all movies released in the 90s

<img src="images/pic 5.png" alt="Alt Text" width="600">

- Get all movies released before the year 2000 or after 2010

<img src="images/pic 6.png" alt="Alt Text" width="600">


## Update Documents

- Add a synopsis to "The Hobbit: An Unexpected Journey" : "A reluctant hobbit, Bilbo Baggins, sets out to the Lonely Mountain with a spirited group of dwarves to reclaim their mountain home - and the gold within it - from the dragon Smaug."

<img src="images/pic 1.1.png" alt="Alt Text" width="800">

-	Add a synopsis to "The Hobbit: The Desolation of Smaug" : "The dwarves, along with Bilbo Baggins and Gandalf the Grey, continue their quest to reclaim Erebor, their homeland, from Smaug. Bilbo Baggins is in possession of a mysterious and magical ring."

<img src="images/pic 1.2.png" alt="Alt Text" width="800">

- Add an actor named "Samuel L. Jackson" to the movie "Pulp Fiction"

<img src="images/pic 1.3.png" alt="Alt Text" width="600">

<img src="images/pic 1.3.1.png" alt="Alt Text" width="600">


## Text Search

- Find all movies that have a synopsis that contains the word "Bilbo"

<img src="images/pic 1.4.png" alt="Alt Text" width="600">

- Find all movies that have a synopsis that contains the word "Gandalf"

<img src="images/pic 1.5.png" alt="Alt Text" width="600">

- Find all movies that have a synopsis that contains the word "Bilbo" and not the word "Gandalf"

<img src="images/pic 1.6.png" alt="Alt Text" width="600">

- Find all movies that have a synopsis that contains the word "dwarves" or "hobbit"

<img src="images/pic 1.7.png" alt="Alt Text" width="600">

- Find all movies that have a synopsis that contains the word "gold" and "dragon"

<img src="images/pic 1.8.png" alt="Alt Text" width="600">


## Delete Documents

- Delete the movie "Pee Wee Herman's Big Adventure"

<img src="images/pic 1.9.png" alt="Alt Text" width="600">

- Delete the movie "Avatar"

<img src="images/pic 2.0.png" alt="Alt Text" width="600">
