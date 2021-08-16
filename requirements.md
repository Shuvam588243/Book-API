## BOOK MANAGEMENT API

This is a simple Book Management API Designed using the following Technologies
	
 - Express
 - NodeJS
<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

 - Vanilla JS
 
There are mainly three things that we are going to manage in the given API
 - Books
 - Author
 - Publications
-----------------
**Books**
	The requirements for the book schema is :
 - ISBN : An unique number for each book
 - title : Title of the Book
 - pub_date : Publication Date of the Book
 - language : Language of the Book
 - page_num - Total Pages of the Book
 - author[] - An array of author for the Book (Can have multiple Authors)
 - category[] - The Category the Book belongs (Can belong to multiple   	Categories)

	The Routes required for Managing the Books are as follows
	
	**GET ROUTES**
 - [x] To get all the books
 - [ ] To get a specific books by using ISBN
 - [ ] To get a list of book based on Category
 - [ ] To get a list of book based on Languages

	**POST ROUTES**
 - [ ] To Add new Books
 
	**PUT ROUTES**
 - [ ] To Update Books

	**DELETE ROUTES**
 - [ ] To delete Book

-----------------
**Authors**
	The requirements for the book schema is :
 - id - An unique id for each author
 - name - Name of the Author
 - books[] - An array of books written by the author

	The Routes required for Managing the Books are as follows
	
	**GET ROUTES**
 - [x] To get all the authors
 - [ ] To get a specific authors by using Author id

	**POST ROUTES**
 - [ ] To add new Authors
 
	**PUT ROUTES**
 - [ ] To update authors

	**DELETE ROUTES**
 - [ ] To delete authors

-----------------
**Publications**
	The requirements for the book schema is :
 - id - An unique id for each publication
 - name - Name of the Publication
 - books[] - An array of books written by the author

	The Routes required for Managing the Books are as follows
	
	**GET ROUTES**
 - [x] To get all the Publications
 - [ ] To get a specific Publication by Id
 - [ ] To get a specific Publication by Book ISBN

	**POST ROUTES**
 - [ ] To add new Publication
 
	**PUT ROUTES**
 - [ ] To update a Publication

	**DELETE ROUTES**
 - [ ] To delete a Publication


