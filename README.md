# Amazon RDS CA Certificate 2019

This repo is intended for use until this issue is merged and published:
https://github.com/mysqljs/mysql/pull/2280

## Usage

```
const options = {
  host,
  user,
  password,
  database,
  ssl: {
    ca: require('mysql-amazon-rds-twenty-nineteen')
  }
}
```

