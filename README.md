# Secrets Project

Live version: https://serene-tundra-35329.herokuapp.com/

<h2>Update<h2>
I have currently disabled Google authentication on live version until I find a solution to the following problem:
When making a callback request with OAuth 2.0 using node the link starts with http://, Google OAuth 2.0 expects https:// therefore 
you'll get an unmatched URI error. I am trying to find a solution and it will be back up soon. Meanwhile, login using normal credentials.

A web application that allows users to submit secrets anonymously.

I've used EJS for partials, templates and simple loops to display information.
Besides, app logic was created using express, nodejs and javascript and stored with MongoDB using mongoose.

I've implemented many encryption methods along the development including:
Facebook and Google authentications, bcrypt, hashing and salting to learn more about authentication and security.

### Landing page
![1](https://user-images.githubusercontent.com/34137527/187512690-4088eb7b-7616-4b97-a9e8-e06eb284d35f.PNG)

### Login and register pages
![2](https://user-images.githubusercontent.com/34137527/187512736-5b01901f-92d9-46ae-a0b8-8ae0fcfab1c6.PNG)
![3](https://user-images.githubusercontent.com/34137527/187512740-b0e2259a-bc65-49a9-8cc7-4e2fe96ea9a2.PNG)

### Secrets page rendered after successful authentication
![4](https://user-images.githubusercontent.com/34137527/187512828-dd344ea3-ba2a-43f6-acfb-8cf43b04a73e.PNG)

### Submit a secret page
![5](https://user-images.githubusercontent.com/34137527/187512867-58360e72-3787-4475-81fe-a7e437206e12.PNG)
