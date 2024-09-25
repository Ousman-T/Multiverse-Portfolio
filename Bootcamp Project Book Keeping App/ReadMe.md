# Book Keeping Application
____
A backend application designed to keep track of a user's reading. The application supports full CRUD operations where a user can create, view, update, and remove books that they've read. The application also has various different endpoints meant to handle different operations. Data is persisted via PostgreSQL database.

## Users
____
Readers
____
# Key Features
____
+ CRUD operations on data
+ Persisted data 
+ Specific endpoints for specific operations
____
# Personal Contributions 
____
**S** - At the completion of bootcamp, we were tasked with creating a backend application in order to show competencies amongst learned material. The project's topic was up to us to decide. Being that I'm a reader, figured it would be cool to make a backend app that keeps track of my reading. This would be helpful for me as I often read great books, remember the content, but forget the name. <br>
**T** - I decided to create the project using Java, as that was the second language I learned during bootcamp. I used SpringBoot for the backend in order to handle routing, schemas, and HTTP requests. I opted to use PostgreSQL for my database, as it was very intutive to work with SpringBoot. I set up tables for users and books and used primary and foreign keys to associate the two. This project was worked on independently and I primarily used Git for version control. <br>
**A** - I worked on the project independently and was able to create a flushed out backend server, attached to a database with CRUD functionality. Getting the relations set up between tables was an initial blocker as this was my first time working with a relational database for a personal project.  Another blocker was getting routing proper with SpringBoot, as this was the first project I've built using technologies outside of the JavaScript umbrella. <br>
**R** - The completed application showcased the many concepts studied during the backend module of bootcamp. The app fulfilled it's purpose to the extent of showcasing the studying and effort that went into learning these new concepts and creating applications using them. Overall I learned that working in new languages are simply opportunities to grow and become a better programmer.

# Competencies
____
### JF 3.2 - Can explain the principles and uses of relational and non-relational databases.
When working on this project, one of the first design decisions I had to make was how should I store data. I've been privy to working with non-relational databases in the past. However, when analyzing what I was trying to design I figured a relational database would suite my purposes better. Being that manipulating and fetching the data under certain conditions would be easier with a relational, and one of the main principles behind my application required the relation between books and readers. <br>
### JF 3.4 Can Create a logical and maintainable codebase
This project was my first Java project, so when working on it best practices were emphasized and followed to the best of my ability. Particularly with the structuring of directories. Housing certain functions next to related functions. Separating logic and understanding the communication between services has to be the most eye-opening aspect of working on this project.

### Code and Resources
____
**Link to Youtube Video walking through project**: https://www.youtube.com/watch?v=vY3tXN2M-Kg <br>
**Link to project repository**: https://github.com/Ousman-T/Book-Keeping-App