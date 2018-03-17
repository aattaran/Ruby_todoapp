# README

This README would normally document whatever steps are necessary to get the
application up and running.

MVC= model veiw controller

CRUD = CREATE READ UPDATE DELETE
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

to create todo list:

.new -> create a new object fo the class and .save saves it
.all -> you can veiw it

.create -> can create it

.find 2 -> finds id=2

.iten2.description

.first

.last

.destroy

 validates :name, presence: true
 
 item5.errors
 
 item5.errors.full_message
 
 item5.errors.any?
 
 resources :todos -> gives all the paths for the CRUD for todos
 
 for a ne todo:
 initiate a Todo instance variable
 
 @todo1 = Todo.new
 instance variable
 
 flash
 
 I can add messages to flash which is a hash. ythen I can display the contents of the messages 
 that are in flash
 
 Todo.find(params[:id])