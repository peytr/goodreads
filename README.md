# README

Coder Academy Term-2 Rails Exercise

Good Reads - Book Database

This README would normally document whatever steps are necessary to get the
application up and running, however in this case I am documenting the steps taken to create the site.

__Steps taken__
- rails new goodreads
- rails g model Books cover:string title:string author:string pages:integer
- started recording steps in this readme
- added first book "Elon Musk" via rails console
- added description column to table via terminal rails g migrate AddDescriptionToBooks description:text
- added description to book one
- added two more books via rails console
- rails g controller books
- created index.html.erb
- configured root route books#index
- added index method to books controller
- added boostrap cdn to application.html.erb
- formatting the index view
- index view shows all books, title, author, cover, link to see book
- show view for individual book, title, author, cover, description, pages and link back to root
- PART 1 COMPLETED