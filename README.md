#Demonstration of the Telstra SMS API

A sample application to illustrate how you might use the Telstra API to send an SMS to someone named Frank, asking him to open a door for you. 

The application is written in Ruby, making use of the Sinatra framework. 

For simplicity the message is hardcoded, but go ahead and modify it to suit your needs!

This application assumes you have:

* At Ruby 2 installed - [Ruby Site](https://www.ruby-lang.org/en/)
* Bundler - [Bundler site](http://bundler.io/)
* **Recommended:** A ruby environment manager (like RVM or chruby) - [RVM Site](https://rvm.io/)

To get the application running:

1. Pull down the source from this repo.
2. `cd letmein`
3. `bundle install`
4. `ruby myapp.rb`
5. Point your browser to `http://localhost:4567/<recipient's number>` to send a message to Frank!