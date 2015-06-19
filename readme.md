## Mongo Concepts + Console Exercise 

For tonight's assignment, we'd like you to answer a few questions and define a couple terms as well as write the queries necessary to perform the following tasks. You can either fork and clone this readme or create a new one with your solutions.
You will be using the terminal and the mongo shell for this assignment as well as notes/google to answer some of the questions


## Part I - Conceptual Review 

Define these terms and answer these questions in 1-3 sentences (some will require a bit of googling)

### Terms

* Database
* Collection
* Document
* Cursor 
* Field 
* CRUD
* Relational Database
* Non-Relational Database
* CAP Theorem
* Schema

### Questions

* Do MongoDB databases have schemas?
* What are typical uses for MongoDB?
* What is Mongoose?
* What is a Mongoose Model?

## Part II - Challenges 
Write the queries necessary to perform the following tasks

1. Write the terminal command to start the mongo server
2. Write the terminal command to enter a mongo shell
1. Show all databases
1. Use the `library` database
1. Show all the collections inside the `library` database
1. Using the insert method Add an author with the name of "John", age of 37 
2. Using the insert method Add another author with the name of "Jane", age of 42 and give her a property of books which is an empty array.
3. Use `findOne` to select an author with an age greater than or equal to 42. Change that authors age to 33, then use the save method to persist the change.
1. Find all of the authors
1. Find an author with the name of John
2. Find all of the authors but limit the search to one
3. Find an author whose name is not equal to "John" using the `$ne` operator
1. Update an author who has a name of "John" and change his name to "James" (without using the set method)
1. Update an author named "James" and using the set operator, set his name back to John and age to 37.
2. Delete an author whose name is "John"
13. Delete all of the authors
1. Create an author whose name is "John" and has an empty array of books
2. Update John and Using the `$push` operator add the string "Of Mice and Men" into the books array.
2. Update John and using the `$push` and `$each` operators add the strings "Grapes of Wrath", "The Pearl", "East of Eden", "50 Shades of Gray" into the books array.
17. Sorry - John Steinbeck didn't write 50 Shades of Gray, using the `$pull` operator, remove that book from the array.
18. Finally, using the `$in` operator, update an author who has a book "Of Mice and Men" and "The Pearl" in the books array and change their name to "John Steinbeck"




