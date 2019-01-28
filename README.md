# Programming Challenge

Hello, intrepid hacker! We have prepared a few challenges for you to complete
in your own time.

To get started, fork this repository. Commit your solutions and then when you are ready, share your version of the repository with us.

Feel free to use any libraries you like, (eg. pytest)

## Exercise 1: Login tests

Use Selenium Webdriver to write some login tests for this demo website: https://the-internet.herokuapp.com/login

- Include a test for lockout after three failed logins (the test is expected to fail because the feature isn't implemented)


## Exercise 2: Get messages 

Using Selenium Webdriver, implement a function get_messages, that returns the messages shown on 
https://the-internet.herokuapp.com/dynamic_content with url of their associated avatars.


## Exercise 3: Twitter

The purpose of this exercise is to test your understanding of the Page Object Model.

Use Selenium Webdriver to implement the following methods for Twitter. 
Pay attention to how you structure your classes and methods.

```python
def get_num_tweets(...):
    ...

def get_followers(...):
    ...
  
def get_direct_messages(...):
    ...

def new_tweet(...):
    ...
```

If you don't have a twitter account to test with, you can use our dummy Twitter account:
test@ambaconsultants.com / Bogus1234

