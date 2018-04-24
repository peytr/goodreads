# README

This README would normally document whatever steps are necessary to get the
application up and running.

__Steps taken:__
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
- took a while to sort out link_to!? confirm with instructors, guides.rubyonrails 1.2 link_to @patient causes error, patient works?
- index view shows all books, title, author, cover, link to see book
- show view for individual book, title, author, cover, description, pages and link back to root
- PART 1 COMPLETED

Next Steps
- add gems as listed, follow docs, commit after each
- Booststrap gem not listed but install
- use seed to add more books
- style as required, similar to instarails_shrine tuesday


# Good Reads - Rails Challenge
* Ruby version
2.5.1
* System dependencies
TBA
* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
