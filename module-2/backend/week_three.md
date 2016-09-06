## Week Three Recap

### Instructions
Fork this repository. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

1. What are the 3 main features in an ERD?
  * Entities (objects), Relationships (verbs), Functional Dependency (cardinality)
2. Create an ERD for the following database: Restaurants, Customers, Items, Ingredients, Beverages, Orders, Vendors.
  * Did drawing
3. What is the entry at the command line to create a new rails app?
  * rails new
4. What do Models generally inherit from in rails?
  * ActiveRecord::Base
5. What do Controllers generally inherit from in a rails project?
  * ApplicationController
6. How would I create a route if I wanted to see a specific horse in my routes fitle assuming I'm sticking to standard conventions and that I didn't want other CRUD functionality?
  * get '/horses/:id' 'horses#show'
  * resources :horses, only: [:show] 
7. What rake task is useful when looking at routes, and what information does it give you?
  * rake routes, this gives you the prefix, verb, path, and controller/action info for all routes currently in the project
8. What is an example of a route helper? When would you use them?
  * model_path(model), I could use them in a link_to that models show page
9. What's the difference between what `_url` and `_path` return when combined with a routes prefix?
  * 
10. What are strong params and why are the necessary?
11. What role does `form_for` play in helping us create our forms?
12. How does `form_for` know where to submit the user's input?
13. Create a form using a `form_for` helper to create a new `Horse`. 
14. Why do we want to validate our models?
