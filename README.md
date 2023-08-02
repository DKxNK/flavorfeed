
# Flavorfeed

Our platform is a comprehensive solution for food enthusiasts all over the world. Leveraging the power of Spring Boot and React, our application enables users to share their food experiences, discover new eateries, and connect with other food lovers. Our aim is to create a global community that appreciates culinary arts and supports local businesses.


## Table of contents

- [Authors](#authors)
- [Features](#features)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Configure](#configure)
- [Run Project Locally](#run-project-locally)
- [Learn More](#learn-more)
## Authors

- [DKxNK](https://github.com/DKxNK)
- [Maleesha-Shavindi](https://github.com/Maleesha-Shavindi)
- [Mr-RiVi](https://github.com/Mr-RiVi)
- [SLxMAJOR](https://github.com/SLxMAJOR)




## Features

- Allow users to create, edit, and delete posts containing photos and descriptions.  
- Allow users to view their own profiles and profiles of other users.  
- Allow users to follow other users and see their followers.  
- Allow users to like and comment on other users' posts.  
- Allow users to receive notifications when their posts are - liked or commented on. 
- Allow users to authenticate via OAuth.


## Folder Structure

```bash
flavorfeed/
|-- back-end/
|    |-- flavorfeed/
|        |-- src/
|            |-- main/
|                |-- java/
|                |-- resources/
|                    |-- .env
|                    |-- application.properties
|-- front-end/
|    |-- node_modules/
|    |-- public/
|    |   |-- index.html
|    |   |-- favicon.ico
|    |-- src/
|        |-- assets/
|        |-- components/
|        |-- pages/ 
|        |-- routes/
|        |-- App.js
|        |-- index.js
|    |-- package.json
|    |-- README.md
```
## Installation

#### ***Back-end***
1. Clone the repository:

```bash
  git clone https://github.com/Mr-RiVi/flavorfeed-springboot.git
```

2. Run to backend:

```bash
  open .java file and run Java
```

#### ***Front-end***
4. Change Directry:

```bash
  cd front-end
```
5. Project Installation:

```bash
  yarn install(Recommended) OR npm install
```
6. Install dependencies:

```bash
  yarn add(Recommended) OR npm install
```

## Configure

#### ***Back-end***
1. Create a new file `.env` in back-end folder:

```bash
  MONGO_DATABASE="DB_name"
  MONGO_USER="Your_user_name"
  MONGO_PASSWORD="Your_cluster_password"
  MONGO_CLUSTER="Your_cluster"
```
```bash
Example
    MONGO_CLUSTER -"test.23kfhf0.mongodb.net"
```

2. Change Server Port:

```bash
  server.port=3000
```
- *server port have inside `application.properties` file. If you need to change port you can change.*
## Run Project Locally

#### ***Back-end***
```bash
  open any file have a .java extension and run Java
````
#### ***Front-end***
```bash
  cd front-end
```
```bash
  yarn start OR npm start
```


## Learn More

You can learn more in the [Create React App documentation](https://create-react-app.dev/docs/getting-started/)

To learn React, check out the [React documentation](https://react.dev/)
