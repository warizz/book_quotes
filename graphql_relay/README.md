# GraphQL x Relay
Implement GraphQL to your server just to make it work is easy.
But when it comes to doing it right, it is another story.

This is my journey to use GraphQL with Relay.

## my playground for this learning
[hitchhike-client](https://github.com/warizz/hitchhike-client)  
[hitchhike-api](https://github.com/warizz/hitchhike-api)

## on setting up your mind for Relay
[Relay Modern - Lee Byron aka @leeb at @ReactEurope 2017](https://www.youtube.com/watch?v=OdsMz7h_Li0&t=881s)

## on setting up project for Relay
If you're ```create-react-app``` guy, you may struggle when ```relay-modern``` [guide](https://facebook.github.io/relay/docs/relay-modern.html) have to make you set up your ```webpack``` x ```babel``` config. This video will help.   
[Getting Started with Relay Modern, React & GraphQL (Full Tutorial)](https://www.youtube.com/watch?v=XeALXh37WeU)

## on pagination
This may be another struggle you'll meet.
Relay has caching, you fetch data and it will be stored in cache.
When you mutate an item in list (like insert/update/delete) you have to update data in the cache manually.
By updating you have to know ```connection/edges/node```.

[Understanding pagination: REST, GraphQL, and Relay](https://dev-blog.apollodata.com/understanding-pagination-rest-graphql-and-relay-b10f835549e7)

[Explaining GraphQL Connections](https://dev-blog.apollodata.com/explaining-graphql-connections-c48b7c3d6976)

[Pagination](http://graphql.org/learn/pagination/)

[Relay Cursor Connections Specification](https://facebook.github.io/relay/graphql/connections.htm)
