# database

## use knex under cli
It's have some problem when use knex migration with dotenv. the knex cli can not parse `.env` file correctly. so, i add a new npm script for solve this issue.

always use the `npm run knex ..` instead of `knex ...`

## create database
```mysql
create database `awesome_comments` default charset utf8mb4 collate utf8mb4_unicode_ci;

```
