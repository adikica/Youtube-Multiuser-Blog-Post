# Youtube-Multiuser-Blog-Post
## Tutorial : Si te ndertojme nje Blog 
## [shiko video tutorial ne youtube ](https://www.youtube.com/@adikica/videos)
## Nevoiten njohuri ne HTML,CSS,JAVASCRIPT ...cdo njohuri tjeter eshte plus per ju
## Vështiresia Fillestarë

## .env file
* * DBPASS=
* * DBUSER=
* * DBNAME=

## Database : MYSQL

## Server  : NodeJs 
## dependencies : npm i express mysql2 jsonwebtoken dotenv multer bcryptjs cors sequelize  
## devDependencies  npm i nodemon -D

## Klient : NextJs ose ReactJs  npx create-next-app@latest  ose  npx create-react-app 
## module : next,next-sitemap,react,react-dom,react-quill...
## Code Editor : Visual Studio Code

## Server Routes
## Shembull Home Route: https://api.webiyne.al 
## ne rastin tone  http://localhost:5000

## Klient Routes
## Shembull Home Route: https://webiyne.al 
## Ne rastin tone  http://localhost:3000

##  C R U D  Create, read, update and delete 

## Server
## User Routes
| #     | api         | pershkrimi |
|------ | ----------- | ----------- |
| 1 | post **/api/users/** | krijojme perdorues te ri |
| 2 | get **/api/users/:id** | kthejme nje perdorues bazuar ne id |
| 3 | put **/api/users/** | perditesojme te dhenat e nje perdoruesi |
| 4 | delete **/api/users/:id** | heqim nje perdorues |

## Kategori Routes
| #     | api         | pershkrimi |
| 1 | **/api/category/** | krijojme nje kategori te re |

## Post Routes
| #     | api         | description |
|------ | ----------- | ----------- |
| 1 | post **/api/post/** | krijojme nje postim te ri |
| 2 | get **/api/post/**  | kthejme 10 postimet e fundit |
| 3 | get **/api/post/:postId** | kthejme nje postim bazuar ne id |
| 4 | delete **/api/post/:postId** | fshijme nje postim bazuar ne id|
| 5 | put **/api/post/:postId** | perditesojme nje postim bazuar ne id |


## Klient
## User Routes
| #     | url        | pershkrimi |
|------ | ----------- | ----------- |
| 1 | post **/users/register** | krijojme perdorues te ri |
| 1 | post **/users/login** | identifikojme perdoruesin |
| 1 | post **/users/profile** | profili i perdoruesit |



## Struktura e aplikacionit "PERAFERSISHT" mund te ndryshoje duke e perditesuar ate

	Backend/

        +-- .env
		+-- package.json
		+-- app.js
		+-- controllers
		¦   +-- user-Controller
		¦   +-- blog-Controller
		¦   +-- category-Controller
		+-- models
		¦   +-- index.js
		¦   +-- User
		¦   +-- Blog
		¦   +-- Category
		¦   +-- Likes
		¦   +-- Comments
		+-- routes
		¦   +-- postRoutes
		¦   +-- categoryRoutes
		¦   +-- userRoutes
		¦   +-- apiRoutes.js        
		+-- midleware
		¦   +-- multer.js
		¦   +-- jwt.js
		+-- config
			 +-- dbConfig.js


	Frontend/
		+-- package.json
		+-- next-config.js
		+-- components
        ¦   +-- Layout.jsx  
        ¦   +-- Header.jsx 
        ¦   +-- footer.jsx 
		+-- lib
		¦   +-- fetcher.js
		¦   +-- withAuth.js
		+-- pages
		¦   +-- _app.js
		¦   +-- _document.js
		¦   +-- index.jsx
        ¦   +-- blog 
            ¦   +-- index.jsx 
            ¦   +-- create.jsx 
            ¦   +-- [id].jsx
        ¦   +-- user 
            ¦   +-- register.jsx
            ¦   +-- login.jsx 
            ¦   +-- profile.jsx        
		+-- public
		¦   +-- robots.txt
		¦   +-- sitemap.xml
		+-- styles
			 +-- global.css
             +-- Home.module.css
 

## Skema e Database ..... mund ta ndryshojme gjate rruges

![image](https://user-images.githubusercontent.com/74735042/193402151-77b2707a-be64-42c2-9c54-419d6d5f099d.png)
