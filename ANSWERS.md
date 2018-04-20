<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
    Middleware is software that acts as a bridge between an operating system or database and applications, especially on a network.

Sessions are places to store data that you want access to across requrests. Each user that visits your site has a unique session. You can use sessions to store and access user data as they browse your application. Sessions are integral to web application development because they allow the application to store state. Based on what action a user took on Page A, we can show a different Page B. Without them, applications would be stateless and not very useful.

bcrypt is a password hashing software that helps prevent hackers from obtaining user passwords on a website.

JWT is a means of expressing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signatures(JWS) and/or encrypted using JSON Web Encryption(JWE).

2.  What does bcrypt do in order to prevent attacks? bcrypt hashes passwords and stores them in the database so that hackers can't obtain the stored passwords. Without bcrypt a database would store user passwords in plain text and a hacker would be able to get their hands on a user's password which would then allow them access to the application.

3.  What are the three parts of the JSON Web Token?
    a JSON Web Token defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.
