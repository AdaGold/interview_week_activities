# News API

Build an API with Rails that will  


## Get Started
1. Create a new rails app in this directory using the following command:
```
$ rails new .
```

1. Setup the application to only be used as an API, instructions are here


## Guidelines
**Wave 1:** Setup the Database
- Plan the structure with an ERD. The application, at minimum, should have the following resources:
  - News articles
  - Authors
  - Categories
- Create Tables and models for your resources
- Set Relationships between resources in the model
- Make seed data and test that it all works as expected

**Wave 2:** Setup the API
API users should be able to query:
- All News articles
- A Specific News Article, by ID
- All News Articles by Category
- All News Articles by an Author

**Wave 3:** Deploy to Heroku!

**Wave 4:** Create documentation for your API
In the README (you can overwrite this one), highlight all the functionality of your API with examples on how to use it.

### Optional Enhancements

- Add the following resources to extend the functionality of your API. Allow users to sign up as a and favorite articles using a POST method.
  - Tags
  - Readers
  - Favorites

- Require users of your app to register for a token
