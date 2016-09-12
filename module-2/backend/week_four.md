## Week Four Recap

### Instructions
Fork this repository. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

* What is a cookie?
  * A cookie is temporarily saved hash-like object (key-value pair) that stores some information about a session
* What’s the difference between a session and a cookie?
  * A session is a cookie hash, that stores multiple cookies for a user session, expires when the browser closes
* What’s a flash and when do you want to use flashes?
  * A flash is a message that displays on the screen and then self-destructs, these are used to confirm that an action happened, ex: "Account created!", "Item deleted!"
* Why do people say “HTTP is stateless”?
  * This is beacuse it does not inherently preserve anything between HTTP requests, this is why we use cookies and sessions
* What’s authentication? Explain.
  * Authentication is determining whether or not a user is who they "say they are", this is done using accounts that require some username and password to validate
* What’s the difference between authentication and authorization?
  * Authorization cannot happen without Authentication, Authorization is determining whether or not a certain user has access to certain things on the site, ex: regular user, or admin?
* What’s a before filter?
  * 
* How do we keep track of a user once they’ve logged in?
* When do you want to namespace a resource? When do you want to nest a resource? What's the differences between those two approaches?
* At a high level, what tools can you use to implement authorization? How would you use them?
* What's an enum, and what advantages does it offer? What data type needs to be in your database to use an enum? Where do you declare an enum?
* What are some strategies you can use to keep your views DRY?
