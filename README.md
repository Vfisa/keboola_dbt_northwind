Welcome to your new dbt keboola project!

### Using the starter project

Try running the following commands:
- `dbt debug -t keboola_northwind --profiles-dir .`
- `dbt run -t keboola_northwind --profiles-dir .`
- `dbt test -t keboola_northwind --profiles-dir .`


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices

```
tests:
          - relationships:
              to: ref('orders')
              field: order_no
```

