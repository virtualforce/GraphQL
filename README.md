# GraphQL
GraphQL is the library by facebook to provide easy access to data. it is the replacement of REST APIs. It is the declarative wasy to access data unlike imperative way like REST. we just told graphql what we want and it is the headache of Graphql how to reterive data.GraphQL is an application layer query language from Facebook. With GraphQL, you can define your backend as a well-defined graph-based schema. Then client applications can query your dataset as they are needed.

<img src="./img/ysnmIMhqRU.png" style="width: 100%;" />

#### GraphQL is the specification, there exist many reference implementation 
  * graphQL js mainted by facebook (https://github.com/graphql/graphql-js) 

### Ruby Libraries

* [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of Facebook's GraphQL.
* [graphql-relay-ruby](https://github.com/rmosolgo/graphql-relay-ruby) - Relay helpers for GraphQL & Ruby.
* [graphql-parser](https://github.com/Shopify/graphql-parser) - A small ruby gem wrapping the libgraphqlparser C library for parsing GraphQL.
* [graphql-client](https://github.com/github/graphql-client) - A Ruby library for declaring, composing and executing GraphQL queries.
* [graphql-batch](https://github.com/Shopify/graphql-batch) - A query batching executor for the graphql gem.

### PHP Libraries

* [graphql-php](https://github.com/webonyx/graphql-php) - A PHP port of GraphQL reference implementation.
* [graphql-relay-php](https://github.com/ivome/graphql-relay-php) - Relay helpers for GraphQL & PHP.
* [laravel-graphql](https://github.com/Folkloreatelier/laravel-graphql) - Facebook GraphQL for Laravel 5.
* [laravel-graphql-relay](https://github.com/nuwave/laravel-graphql-relay) - A Laravel library to help construct a server supporting react-relay.
* [graphql-mapper](https://github.com/4rthem/graphql-mapper) - This library allows to build a GraphQL schema based on your model.


## read more for reference implementation
https://github.com/chentsulin/awesome-graphql/edit/master/README.md

# Query Structure
  {
    latestPost {
      title,
      summary
    }
  }
# Query result
  {
    "data": {
      "latestPost": {
        "title": "New Feature: Tracking Error Status with Kadira",
        "summary": "Lot of users asked us to add a feature to set status for errors in the Kadira Error Manager. Now, we've that functionality."
      }
    }
  }
# read more on how to use graphql
https://learngraphql.com/basics/introduction
