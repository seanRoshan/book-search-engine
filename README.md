# Book Search Engine


## Description

The Book search engine is an application that is employing MERN (MongoDB, Express, React, Node) Stack and GraphQL. It allows users to Signup, login, logout, search books via Google Book Search API and save their favorite books. They can also see the list of their favorite books and can delete any of the books from the list if they do not like them anymore.

## Deployed Application 

[Book Search Engine](https://infinite-bastion-30683.herokuapp.com)<br />

![Google_search_screenshot](https://user-images.githubusercontent.com/16109054/190893135-15f3361d-3baf-4bb1-9c3a-a020ce443860.jpeg)


## How to start

In the project directory, you can run:

### `npm i -D concurrently`
### `npm run install`
### `npm run develop`

Both client and server applications will run concurrently in the development mode.<br />

Use GraphQL at [http://localhost:3001/graphql](http://localhost:3001/graphql)<br />
Open [http://localhost:3000](http://localhost:3000) to view the app in the browser.

## Project Structure

- [**client**](client)
    - [**build**](client/build)
        - [**static**](client/build/static)
            - [**css**](client/build/static/css)
            - [**js**](client/build/static/js)
    - [**public**](client/public)
    - [**src**](client/src)
        - [**components**](client/src/components)
        - [**pages**](client/src/pages)
        - [**utils**](client/src/utils)
- [**server**](server)
    - [**config**](server/config)
    - [**controllers**](server/controllers)
    - [**models**](server/models)
    - [**routes**](server/routes)
        - [**api**](server/routes/api)
    - [**schemas**](server/schemas)
    - [**utils**](server/utils)
