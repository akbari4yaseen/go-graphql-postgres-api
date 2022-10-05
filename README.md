# Go GraphQL Postgres Api

> Go with GraphQL + Postgres api project

Screenshot

![Screenshoot](?raw=true)

[Live Demo]()

## Built With

- GO
- GraphQL
- Postgres

To get a local copy up and running follow these simple example steps.

### Prerequisites

```bash
git clone https://github.com/akbari4yaseen/go-graphql-postgres-api.git
```

## Getting Started

First, execute the postgres.sql, next, set the Postgres connection string, then run the development server:

```bash

go run main.go
```

Use Postman or another Graphql PlayGround [http://localhost:4010/graphql](http://localhost:4010/graphql)

### JSON

```raw
{
 "query": "{users(name:\"yaseen\"){id, name, age, profession, friendly}}"
}
```

### GraphQL

```raw
{
 {
  users(name: "alex") {
    id
    name
    age
    profession
    friendly
  }
}
}
```

👤 **Yaseen Akbari**

- GitHub: [@githubhandle](https://github.com/akbari4yaseen)
- Twitter: [@twitterhandle](https://twitter.com/AkbariYaseen)
- LinkedIn: [LinkedIn](https://linkedin.com/in/yaseen-akbari)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!
