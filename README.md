# JS Interview Project 
Create an UI web application that retrieves and displays the user repositories and organisations in Github.

## Starting the project
You may choose to do this project in Vue, Angular, or use vanilla Javascript.

### Vue

In the ```vue``` folder is a fresh project created with Vue CLI.

```
cd vue
npm run serve
```

### Angular

In the ```angular``` folder is a fresh project created with Angular CLI using the SASS stylesheet option.

```
cd angular
ng serve
```

### Vanilla JS

In the ```vanilla``` folder you will find an index.html and index.js file. 
We are using ParcelJS as a web application bundler.
                                                                                                  

```
cd vanilla
parcel index.html
```

## UX/UI
Up to you, probably it should include an input to enter the username, one area to display the repositories of the user and another area to display the organisations

## Retrieving data
To make things easier we have committed a github-api.js file with the REST APIs needed to retrieve the information.

## Bonus (don't need to be in the below specific order)
* Use ES6 syntax including arrow functions, destructuring and async/await
* Adding a spinner when information is loading
* Deal with errors coming from the backend
* Some sort of Unit Test
* Some sort of Integration Test
* Having a nice UI using a components library (Bootstrap, Ant Design, Material UI or another?)
