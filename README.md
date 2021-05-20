# REACT_Project_BE

This project is a basic social media app
A user can log in and create a frofile
User can post an event with image and can see events or posts for other users 

**npm start**
Runs the app in the developement mode.
Open http://localhost:3001/#/ to view it in the browser.

**Testing the APIs**
You can use Postman to test all the endpoints

**Methods to create Api routes & url to make request to a specific route**

1. POST (http://localhost:3001/#/posts)

2. PUT (http://localhost:3001/#/posts/:id)
 _id: req.body.id,
            title: req.body.title,
            content: req.body.content,
            imagePath: imagePath,
            creator: req.userData.userId

3. GET (http://localhost:3001/#/posts/mypost)

4. GET (http://localhost:3001/#/posts)

5. GET (http://localhost:3001/#/posts/:id)

6. DELETE (http://localhost:3001/#/posts/:id)

7. POST (http://localhost:3001/#/user/signup)
    email: req.body.email,
            password: hash
            
8. POST (http://localhost:3001/#/user/login)

9. POST (http://localhost:3001/#/profile/create)

          username: req.body.username,
            bio: req.body.bio,
            imagePath: url + "/images/" + req.file.filename,
            creator: req.userData.userId
            
10. PUT (http://localhost:3001/#/profile/edit/:id)

          _id: req.body.id,
            username: req.body.username,
            bio: req.body.bio,
            imagePath:imagePath,
            creator: req.userData.userId

11. GET (http://localhost:3001/#/profile/profiles)

12.  GET (http://localhost:3001/#/profile/viewprofile)

13.   GET (http://localhost:3001/#/profile/bycreator/:id)

14.  GET (http://localhost:3001/#/profile/:id/mypost)

15.  GET (http://localhost:3001/#/profile/:id)

