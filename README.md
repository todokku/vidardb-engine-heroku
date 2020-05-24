# VidarDB Engine on Heroku

Heroku helps you build apps backed by VidarDB.

Deploy VidarDB Engine on Heroku and get an SQL endpoint in under 30 seconds :clock1:

Read more at [vidardb](https://www.vidardb.com) and the [docs](https://www.vidardb.com/docs). 


## Quickstart

### 1. Deploy to Heroku 
Deploy to Heroku for VidarDB:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/vidardb/vidardb-engine-heroku)


### 2. Open Hasura Console

Once the deployment is complete, click on the `View` button as marked above.
This will take you to the Hasura Console, where you can create a table and make
your first GraphQL query. 

![Hasura Console](https://graphql-engine-cdn.hasura.io/heroku-repo/assets/hasura_console.png)

### 3. Create a table

Navigate to `Data -> Create table` on the console and create a table called
`profile` with the following columns:

| name   | type                     |
|--------|--------------------------|
| `id`   | Integer (auto-increment) |
| `name` | Text                     |

Choose `id` as the Primary key and click the `Create` button.


### 4. Insert sample data

Once the table is create, go to the `Insert Row` tab and insert some sample
rows:
```

```

### 5. Try out VidarDB

Switch to the `VidarDB` tab on top and execute the following sql query:


## Support & Troubleshooting

Feel free to talk to us on [Discord](https://www.vidardb.com/docs) about anything
and everything. You can also contact us using one of the following channels: 

* Talk to us on our [website chat](https://www.vidardb.com).

## Next steps

- [Updating to the latest version](https://www.vidardb.com/docs/faq/)

## Further reading

- [Guides/Tutorials/Resources](https://www.vidardb.com/docs)
