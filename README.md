## NoSQL-Challenge-Social-Network-API

1. [ Description. ](#desc)
2. [ Web Address. ](#web-address)
3. [ Usage tips. ](#usage)
4. [ Features. ](#features)
5. [ Licenses. ](#licenses)
6. [ Install Command. ](#commandInstall)
7. [ Test Command. ](#commandTest)

### For license description, click on the badge to get more information.
[![License](https://img.shields.io/badge/License-MIT%20-blue.svg)](https://opensource.org/licenses/mit)

<a name="desc"></a>
## 1. Description

This is a back end web application that was built using MongoDB, Mongoose and express js to showcase a no sql network api.

<a name="web-address"></a>
## 2. How to Get There

### Open your favorite code editor (uses git) and run (MongoDB installation is required):

npm i
npm start


<a name="usage"></a>
## 3. Usage Tips

If you want to run locally perform the following:

If you are still interested in running the application you would need to do the following:
* install MongoDb version 4.4.4 as minimum.
* npm i
* npm start

Insomnia path are:

* User related *

Create user: 
http://localhost:3001/api/users/

json sample:

{
  "username": "john",
  "email": "john@gmail.com"
}


Get all users: 
http://localhost:3001/api/users

Get users by ID, Update user by ID, Delete user by ID:
http://localhost:3001/api/users/<userId>

Add a new friend, Remove friend:
http://localhost:3001/api/users/<recipient userId>/friends/<friend user Id>

* Thoughts related *

New thought:
http://localhost:3001/api/thoughts/

json sample:

{
  "thoughtText": "Here's a cool thought -- reaction #2",
  "username": "john",
  "userId": "6302c9d5229c785ede6e842c"
}

Get all thoughts:
http://localhost:3001/api/thoughts/

Get thought by Id, Update thought by id, Delete thought by Id:
http://localhost:3001/api/thoughts/<thoughtId>

Add a reaction to a thought by id:
http://localhost:3001/api/thoughts/<thoughtId>/reactions
  
Delete a reaction from thought by id's:
http://localhost:3001/api/thoughts/<thoughtId>/reactions/<reactionId>

#### Walkthrough Video

[Click here to see the demo video!](https://clipchamp.com/watch/aCZkgc8RfX8)

Insomnia-Screenshot:

![Insomnia-Screenshot](https://user-images.githubusercontent.com/33476304/185820068-71e3ac54-77bb-4ca4-9917-f68e825255b2.png)


<a name="features"></a>
## 4. Features

Application is running fully in the back end, all features are associated with insomnia. Please revisit usage tips for more information.

<a name="licenses"></a>
## 5. Licenses

mit

<a name="commandInstall"></a>
## 6. Install Command

### Database dependency is --> MongoDB 4.4.4  
### npm install command will install javascript dependencies

npm i

<a name="commandTest"></a>
## 7. Test Command

No test commands available, if you would like any, please let me know.
