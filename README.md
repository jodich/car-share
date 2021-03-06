# Share Parking Spaces

Build an app that lets users share parking spaces.

Users can assign their cars to any space.

#### Relationships
Cars belong to a user.

Spaces have many cars and cars have many spaces.

#### Deliverables
- Rails CRUD app. At least one nested route: /spaces/:id/cars
- When you create cars, associate them with a user and a space.
- Users can login

#### Further
- Add bootstrap to your app

- Add the ability to associate an existing car to an existing space.

- Add the ability to associate an existing space to an existing car.

- Add other nested routes to your app: 
```
/spaces/:id/users
/users/:id/spaces
```

### Not tired of pokemon yet?
Build a full CRUD pokedex.

#### This pokedex data model will be different:
- Pokemon have many types and types belong to many pokemon.

- Pokemon belong to a user.

#### Further
- Add the ability for a user to capture a pokemon.
- Edit the seeds.rb file to seed the DB with pokemon and types: https://github.com/wdi-sg/pokedex-rails/blob/master/db/seeds.rb
- Add bootstrap to your app.
- Change the model so that pokemon also belong to many users.
- Add other nested routes:
```
/users/:id/pokemon
/pokemon/:id/users
```
