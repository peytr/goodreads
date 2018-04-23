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

Next Steps
- Create show page to show individual books
- Add link to each book for show page
- Move description and pages from index and display in show page




Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
