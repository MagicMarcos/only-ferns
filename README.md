# DreamOn

<p> An for uploading your plants! Only.plants. AI is used to ensure pictures without plants cannot be uploaded.</p>
<p> See it live at <a href="https://onlyferns.herokuapp.com">DreamOn</a> </p>

## How It's Made:

### Utilized: 
     
       JavaScript
       Node: server / back-end
       Express:server / back-end
       EJS: templating
       CSS: styling
       Bootstrap 5: styling
       MongoDB: database
       Microsoft Azure AI Computer Vision: determines scholarships status 
       Heroku: hosting
       Cloudinary: image hosting 
    
    
### Reflections and Description: 
<p>This project was a bit tongue in cheek, however, it was a great experience to work with Azure AI and cloudinary.</p> 
<p>Users are able to sign up / log in and upload images of their plants, and we use AI to ensure only plant photos can be uploaded<p/>
<p>Additionally, users can comment on and like plant posts.<p/>


### Lessons Learned:
<p>This project was a wonderful group effort, where we got to learn how to best work within a group and distribute labor.</p>

### Optimizations
<p>Styling can always be better and updated.</p>
<p>Upcoming features: </p>
    
       Accessibilty features like, high contrast and zoom in options
       More costumizability for costumers
       Using passport for better auth experience  
       Adding mongoose for better schemas 
       Updating code to use MVC design pattern  
  

### Errors and Bugs 
<p>If something behaves unexpectedly, it is likely a bug. Create an issue and report it <a href="https://github.com/MagicMarcos/only-ferns/issues">here</a>  </p>

## Team 
### Design (UX/UI)
     <a href="https://github.com/MagicMarcos">Marcos Cardoso</a> (me)
     <a href="https://github.com/natashatorres">Natasha Torres</a>
     <a href="https://github.com/betheld">Bethel Dawed</a>
     <a href="https://github.com/sharob94">Shana Robinson</a>
### Front End 
     <a href="https://github.com/MagicMarcos">Marcos Cardoso</a> (me)
     <a href="https://github.com/Enrique2656">Duane Rymarowicz</a>
     <a href="https://github.com/NDNey">David Ney</a>
     <a href="https://github.com/natashatorres">Natasha Torres</a>
### Back End
     <a href="https://github.com/Enrique2656">Duane Rymarowicz</a>
     <a href="https://github.com/NDNey">David Ney</a>
     <a href="https://github.com/MagicMarcos">Marcos Cardoso</a> (me)
     
## Previews
![Home Page](https://res.cloudinary.com/codechella/image/upload/v1639340730/of-home_div2g3.png)

![Feed Page](https://res.cloudinary.com/codechella/image/upload/v1639340735/only-ferns-feed_z62vfh.png)

![login Page](https://res.cloudinary.com/codechella/image/upload/v1639340724/of-login_j2zdrl.png)


## HOW TO RUN THIS LOCALLY

`npm install`

---

### Things to add

- Create a `.env` file and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`
  - MS_COMPUTER_VISION_SUBSCRIPTION_KEY = `your azure computer vision subscription key`
  - MS_COMPUTER_VISION_ENDPOINT = `your azure computer vision endpoint`

---

### Run

`npm start`
