# studentMarksheet
A simple REST API using Fastify and Node.js for a student marksheet system.

No database connectivity is used, and the data is stored in the memory, which gets erased when the server is restarted.

The data consists of: Student Name, Student ID, Marks of 5 subjects.

The data can be viewed, added, updated or deleted using endpoints.

The endpoints are:

/report

/add

/update

/delete/:id

The required npm packages are:

fastify

fastify-swagger
