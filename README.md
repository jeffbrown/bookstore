A simple demo in response to http://stackoverflow.com/questions/34266957/how-to-insert-data-on-grails-3-through-rest-api

To create a book:

    curl -X POST -H "Content-Type: application/json" -d '{"title":"Some Title", "author":"Some Author", "publicationDate":"2015-12-13T23:00:00Z"}' http://localhost:8080/books

To retrieve books in JSON:

    curl http://localhost:8080/books.json


To retrieve books in XML:

    curl http://localhost:8080/books.xml
