# Fastapi template part 2

## Configuration 2.

To recap, configuration 1 was:

`$ fastapi_template -n fastapp --quiet --api-type rest --db none --orm none --ci none`

- `-n fastapp`: Project name
- `--quiet`: don't ask me questions for extra options
- `--api-type rest`: this is for a restful api (as opposed to graphql)
- `--db none`: don't add a database
- `--orm none`: don't add an ORM like sqlalchemy
- `--ci none`: don't add continuous integration like github actions

Now, we will add example routers

`$ fastapi_template -n fastapp --quiet --api-type rest --db none --orm none --ci none --routers`
`$ fastapi_template -n fastapp --quiet --api-type rest --db sqlite --orm none --ci none --routers`
`$ fastapi_template -n fastapp --quiet --api-type rest --db sqlite --orm none --ci none --routers`

# starter

python3 -m fastapi_template --name fastapp --api-type rest --db none --orm none --ci none --quiet

# gunicorn

--gunicorn
easy?

# visit test

# routers - break a test

--routers
medium?

# db - sqlite - mostly focus on pydantic settings

--db sqlite
easy

# orm

--orm sqlalchemy
hard

# dummy model

--dummy
hard

# migrations - add it yourself

--migrations
medium

# postgresql

--db postgresql
easy

# 9 ci github

--ci github
