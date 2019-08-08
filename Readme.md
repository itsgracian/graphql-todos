# GraphQLTodos
FullStack  Todo List APP  using GraphQL, Express, MongoDB and React Js (MERN Stack).

## Pre-requisites

### clone repo
```
clone this repo
```

### Install
```
yarn install 
```
#### or
```
npm install
```

### Start server 
server will run on PORT 3000
```
npm start or yarn start
```
### Play with GraphQL by adding todos and get all todos like this
```
query{
  Todos{
    id
    name
    description
  }
}
mutation {
  createTodos(name: "GraphQL", description:"GraphQl"){
    name
    description
  }
}
```

## Install Frontend App
```
- change directory to /client
- run npm install

```
## Frontend ScreenShoot

<img width="1440" alt="Screen Shot 2019-08-06 at 21 48 12" src="https://user-images.githubusercontent.com/27460888/62572409-f1539200-b893-11e9-8153-2597673e51ce.png">

<img width="1440" alt="Screen Shot 2019-08-08 at 10 59 44" src="https://user-images.githubusercontent.com/27460888/62689730-ab014e80-b9cb-11e9-9da9-11366db0a7c4.png">

## Backend ScreenShoot
<img width="1440" alt="Screen Shot 2019-08-02 at 20 04 42" src="https://user-images.githubusercontent.com/27460888/62389719-d665e280-b560-11e9-91dc-c14e1186ea2f.png">

## Author 
[gratien](https://github.com/itsgracian) :robot:

## Licence
MIT
