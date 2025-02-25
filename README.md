![Imgur](https://i.imgur.com/yq7noDD.png)
![](https://i.imgur.com/lW48lzR.png)
![Issues](https://img.shields.io/github/issues/jakeschultz89/Project-3-Backend)![Forks](https://img.shields.io/github/forks/jakeschultz89/Project-3-Backend)![License](https://img.shields.io/github/license/jakeschultz89/Project-3-Backend)![Repo-Size](https://img.shields.io/github/repo-size/jakeschultz89/Project-3-Backend)![Contributors](https://img.shields.io/github/contributors/jakeschultz89/Project-3-Backend)



Fake-X-Backend is the backend of a full space-x starlink tracker 

## Collaborators

 ```sh
 https://github.com/jakeschultz89
 https://github.com/brandonhall96
 https://github.com/vinnyvilasboa
 https://github.com/behemoth0132
 ```

- Run mongoDB  
- Run your server
- ✨Magic ✨

## Features

- Use the seed .js file to add the static data we included in order to view it in mongoDB
- The data used in the seed will reflect to the front end. 
- The magic is just getting started please scroll to the end to see the link for the front end!



## Tech

Fake-X uses a number of technologies to work properly:

- [mongoDB] - The database for modern applications
- [Mongoose] - an Object Data Modeling (ODM) library for MongoDB and Node. js
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework


## Installation

Fake-X requires [Node.js](https://nodejs.org/) to run.

You first need to clone the repository
```
git clone https://github.com/jakeschultz89/Project-3-Backend.git
```

Install the dependencies and devDependencies and start the server.

```sh
npm i
npm start
```

For .env... use whatever values you would like for the items included in the .env file below

```sh
MONGO_URI=""
JWT_SECRET=""
```
Next... Go to your terminal and 
```sh 
Run the command (mongod) first
```
```sh
Then follow up with the (mongo) command in a seperate terminal window
```

## Code Snippets to be Proud of 

![](https://i.imgur.com/ES6BDXv.png)
> The above code snippet is something we are very proud of due to the fact that we went through alot of trial and error to get this to work. The purpose of the above function is to update a specific ```astro``` that has already been created, initially we used the ```update``` method and that didnt work because it only updated the first ```astro``` in the database instead of the one we tried to pull and update by the i.d.. Once we changed it to ```findByIDAndUpdate``` it fixed all of our problems but we defninently had to troubleshoot this for a few days but thankfully with some needed help we got it to work.

## Schema Idea
![](https://i.imgur.com/25wp8LI.jpg)
> Above is our thinking behind our schema's and how they connect the User schema is self explanitory it collects the information input by the user and saves it to the database, this schema connects to the ```Astros Scehma``` meaning a user can create an astro and conduct other things such as update and delete them. The other schemas are stactic data that we seeded into our databse from the Space-X-API ```https://github.com/r-spacex/SpaceX-API/tree/master/docs/v4``` 



Verify the deployment by navigating to your server address in
your preferred browser.

```sh
http://localhost:8080
```

> our backend is also deployed on heroku at ```https://afternoon-lowlands-89410.herokuapp.com/```

> In order to see the full app please view our front end ```https://github.com/brandonhall96/react-project-3```
> you will find additional information there concerning this app.






   [Mongoose]: <https://mongoosejs.com/>
   [node.js]: <http://nodejs.org>
   [express]: <http://expressjs.com>
   [mongoDB]: <https://www.mongodb.com/>



