https://services.github.com/on-demand/intro-to-github/explore-github-repository
https://guides.github.com/activities/hello-world/
https://github.com/

https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/
====================================================================================================
install Git-2.18.0-32-bit and TortoiseGit-2.6.0.0-32bit in local machine

1.login into git hub

https://github.com/login

user:saravanaprabuA
saravanaprabu.a@gmail.com
pwd: NAMO@123siva

2.Create New Repository called : MongoRestBootIntegration

3.open MongoRestBootIntegration folder in windows

4.right click -> Create Git Repository here

5.select the folders and files to add -> right click TortoiseGit -> add


----------------------------------------------------
https://github.com/saravanaprabuA/SpringBootIntegration.git

git remote add origin remote repository https://github.com/saravanaprabuA/SpringBootIntegration.git
=======================================================

install Git-2.18.0-32-bit and TortoiseGit-2.6.0.0-32bit
https://github.com/saravanaprabuA
Create new Repository : SpringBootRest 
repo url:https://github.com/saravanaprabuA/SpringBootRest.git

in windows go to F:\saran\Techonology\SpringBoot\springboot-batch\springboot-batch

right click -> Create Git Repository here
select the folders and files to add -> right click TortoiseGit -> add
select the folders and files to commit and push -> right click Git commit -> master

in the commit window -> manage Remot : set the repo url and master

============================================================================
REST MONGO DB SPRING BOOT INTEGRATION

https://www.callicoder.com/spring-boot-mongodb-angular-js-rest-api-tutorial/

https://github.com/callicoder/spring-boot-mongodb-angular-todo-app

https://start.spring.io/

select dependencies - web, mongoDB

mongod --dbpath C:\Program Files\MongoDB\data --storageEngine=mmapv1

mongod --storageEngine=mmapv1

mongo

> use todoapp
switched to db todoapp
> show dbs
local  0.078GB
> db
todoapp
>


#===================================
application.properties

spring.data.mongodb.database=test
spring.data.mongodb.host=localhost
spring.data.mongodb.port=27017
=======================================
Run mongoDB:


C:\Program Files\MongoDB\Server\3.2\bin\mongod

sample from: https://www.petrikainulainen.net/programming/spring-framework/creating-a-rest-api-with-spring-boot-and-mongodb/
=======================================
MongoRestBootIntegration:

Create: POST

http://localhost:8080/api/todo

{"title": "Title", "description":"Description"}
=======================================
Find All: GET
=======================================
http://localhost:8080/api/todo
=======================================
FindById: GET

http://localhost:8080/api/todo/5b6248da2f3e09b02742136b
=======================================
Update: PUT

http://localhost:8080/api/todo/5b6248da2f3e09b02742136b

{
	"id":"5b6248da2f3e09b02742136b",
	"title": "Updated Title", 
	"description":"Updated Description"
}
=======================================
Delete: DELETE

http://localhost:8080/api/todo/5b6248da2f3e09b02742136b
====================================
Mongo DB Qurery: NoSQLBooster

db.todo.find({})
