# Social-Media-App

This is a social media app that I created using the MERN stack. Here is a demo video while I deploy the code: https://clipchamp.com/watch/TsF3Rcht1SU 

 This is a full stack application for which I have made the back end API using Node.JS
 and Express.JS connecting it to a mongoDB database which is serving a React.js front 
 end app which I have also made. It has the ability to register new users with a profile
 image, keeping a user logged in even when the tab is closed, liking/unliking posts and
 adding/removing friends while being able to view everyones posts and create new ones.
                
The authentication is handled by bcrypt for the authentication and JWT token for the
session information and session persistence once the user has been authenticated till
the browser is closed. The user data and images are stored locally with the help of 
react drop zone and multer - a npm package I have coded different routes for actions
on users, actions on posts and authentication actions.
               
The User route takes care of adding and removing friends and updating all friend lists
and getting the user profile information for the main feed and the users page. Similarly,
the posts route deals with post creation and likes and authentication deals with login,
registering and session persistence even when the tab is closed.
                  

![snapbook_homepage_light](https://user-images.githubusercontent.com/79290729/214505235-167fd294-f4f2-41da-bbcf-9f371a9c1c68.png)

![snapbook_homepage](https://user-images.githubusercontent.com/79290729/214505276-80b1c872-1ecd-46f8-9e7f-1e5742876e45.png)

![snapbook_register](https://user-images.githubusercontent.com/79290729/214505303-e13e82de-2f8c-4dfe-8b84-892270773788.png)

![snapbook_login](https://user-images.githubusercontent.com/79290729/214505328-cc4bfc05-4595-410c-82e9-9de0413e4c3f.png)
