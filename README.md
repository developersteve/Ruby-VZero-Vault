# Vault Ruby demo using Sinatra 

This is a reall basic example of the Braintree Vault in Sinatra to create a customer and attach a payment method, being stored in the Braintree Vault. Once stored a token is returned that can be stored and transacted against as needed. 

## Technology

This demo uses

* Ruby 1.9.3 or higher
* The [Sinatra](http://www.sinatrarb.com/) web framework

## Demo

* Fill in the following credentials:
  * Number: `4111 1111 1111 1111`
  * CVV: `123`
  * Expiration date: `11/2020`
* Click submit

or you can sign in using your PayPal Sandbox account

## Running the demo locally

* Run `bundle` to install all dependencies
* Run `ruby app.rb` to start the app
* Visit `http://localhost:4567/` in your browser
* Proceed as above
