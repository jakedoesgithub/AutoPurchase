<h1> AutoPurchase </h1>
A python program to check for when an item is in stock then send an alert to let you know. WebStoreCamper is
the class that will allow you to create your own version for whatever site you want. All you have to do
is define a method that checks if an item is in stock (personally I use beautiful soup to do this and 
check for the existance of the Add to Cart button). 

In order to send alerts you will need a Twillio account. There is a free trial that gives you like $10 to
spend and you can use that for a long time. 

You will need to create a file called env.py in which you will define variables you want to keep hidden.
Examples include:
SID and TOKEN for your Twillio sid and auth_token respectivly.
various cell phone numbers
username and password for bestbuy, newegg, etc
credit card info

I've left the imports and the static variables imported from the env.py file at the top of main.py
so it shouldn't be hard to just copy the variable names I've used and fill in your own information.
I'll try to remember to write up a sample env.py called sample_env.py when I am finished to make it
easier on whoever decides to use this.
