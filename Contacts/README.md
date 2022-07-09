# README

This README would normally document whatever steps are necessary to get the
application up and running.

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
#terms to remember
1. CRUD- create read update and delete
2. 
# Steps

1. make the project (rails new Contacts)
2. generate the controller with action index (rails g controller home index)
3. Change the root path add (root 'home#index')
4. Creeated the about page manally
   1. created the about.html.erb in views/home
   2. created the controller method for about in  home_controller
   3. Added the route for about page (get 'home/about')
5. Added the bootstrap in application.html.erd for UI
6. Create the partial for header
   1. Created the file in views with starting with "_" (_header.html.erb)
   2. use render in application.html.erb to create the response for header (<%= render 'home/header' %>)
   3. Use boot strap to load the nav bar
7. Used the link_to to Add links to navbar(<%= link_to "about us", home_about_path, class:"hellO">)
8. Used the CRUD to deploy the elements directly to database and schema.
9. Used and installed the devise gem
   1. Added the required line of code in config/environments/production(for herouko) and development.rd(forlocal server)
   2. Followed the documentation and got all the view and models
   3. Used the user_signed_in? to add condition in session
   

