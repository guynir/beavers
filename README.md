# beaverway-js
Beaver-way is a small Javascript library for defining behavior routing based on a given state.
 
# What is "behavior routing"?
Almost every application maintains a business logic which defines the user flow based on some state. For example, a controller or service handling user login, that define their behavior based on user input:
* If user is missing username or password fields, the user is instructed to specify the missing field.
* If user failed authentication - he or she are instructed to correct their credentials speicifications.
* If user specified a valid credentials - he or she are redirected to application's main page.
This definition of flow is a behvior routing - it is a route which results in some behavior, typically based on some state.

# Isn't that's about 99% of most applications' business logic ? Behaving based on a given state?
Yes Einstein! You've got it right. Most applications' business logic is definition of behavior based on some state. If you need to understand why one would need a 3rd party library for defining routing inside the application - read the next question.

# OK. So - why one would want or need to use a 3rd party library for in-application routing?
There are two main reasons why one would want to use a 3rd party library such as Beaver Way:
* First reason would be to glorify the author's name and get him published.
* Second reason would be to easily re-use the same behavior on different occasions under different state with "prototyping" approach (the last phrased will be explained shortly).

Lets look at a simple example:
Lets
