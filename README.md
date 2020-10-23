# User Profile
This is a repository created for complete integration of React with API. More details are present in readme.

# Problem Statement

```
1. Create a react application using CRA with react version 16.x satisfying the following criteria:

  a. Use https://jsonplaceholder.typicode.com/users to fetch user details.
  b. Use https://jsonplaceholder.typicode.com/posts to fetch user blog posts.
  c. Create a login screen and let user login using the email id and username as password retrieved from 1st API call. (Be Sure to add basic validations for email field)
  d. Once the user is logged in display two pages:
      i) To display the list of all the users and
      ii) To display the list of all the blog post by any user
  e. There should be an option of filtering the user based on names and filtering the blogs by author name and title.
  f. Once clicked on a particular blog post open the blog with an option to go back to previous page.
  g. Your application should have following urls:
      i) /login
      ii) /home (to display the user list and blog post menu)
      iii) /users
      iv) /blogs
      v) /blogs/<blogId> (Here blogId is dynamic and will change based on the clicked blog)
  h. Add logout functionality as well.
```

NOTE:
1. The 1st API does not return any password, therefore use the ‘username’ field for password
2. Use functional component and hooks.
3. Once you are done with your changes deploy your application on github pages, you can follow the below tutorial for deploying to github pages:
https://dev.to/yuribenjamin/how-to-deploy-react-app-in-github-pages-2a1f
