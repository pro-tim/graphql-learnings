My learnings from [GraphQL vs REST](https://hasura.io/learn/graphql/intro-graphql/graphql-vs-rest/)

The benefits of GraphQL over REST are:
1. No overfetching - fetch exactly what you need. With REST, you'll be getting the full data set whether you want it or not.
2. There's no need for multiple API calls - with GraphQL you can make ad-hoc queries as and when required and the data is returned based on the query.
3. Less comms with API devs - With GraphQL there isn't the need to ask your API devs to build a new API to fetch the exact data that you need.
4. Schema for better scheming - GraphQL APIs follow the data graphql model or schema. This kind of documentation allows for easier and better open source dev.

The benefits of REST over GraphQL are:
1. REST is the industry standard though that's changing
2. And because REST is the incumbent tech, API analytics are easier to get for REST. Again, that's changing with tooling like Hasura.
