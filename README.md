# RSS-Aggregator
This server acts as an RSS aggregator, built with Go and utilizing a Postgres database. Users can be created, and these users can create and manage their own RSS feeds. They have the ability to follow or unfollow RSS feeds at their discretion. Additionally, users can retrieve the latest posts or articles from the RSS feeds they are following.

### Getting Started

To get started with this project, follow these steps:

1. Fork this repository

1. Clone this repository to your local machine:

```bash
git clone https://github.com/ehteshamtarq/RSS-Aggregator.git
```

2. Configure the database connection. Add the PostgresSQL in the .env file(DB_URL)


3. Start the backend server:

```bash
go run .
```
4. Add the port number on the http.listen&Server line in main.go as ":3000"

5. Access the application in your web browser at [http://localhost:3000](http://localhost:3000).

7. You can access Postman api docs at [https://documenter.getpostman.com/view/33486149/2sA3Bj9ZxX](https://documenter.getpostman.com/view/33486149/2sA3Bj9ZxX)

## Deployment
[Live](https://rss-aggregator-7kbj.onrender.com)
