# Ch 2.

## Lesson difficultly

### 🙂 Easy

## Introduction

To balance out the previous, hard lesson, this one will be easy.

To generate the next stage of the app the command is the following, but do not run this!

`python3 -m fastapi_template --name fastapp --api-type rest --db none --orm none --ci none --quiet --gunicorn`

We're going manually add this one because it is so simple.

Specifically, we're going to swap out Uvicorn with Gunicorn when we run in production.

Gunicorn is more mature and more widely used in production as opposed to uvicorn, what FastAPI comes with out of the box.

## Detect non development prod

The first time we're going to do is for the application to detect non prod

confirm a reload

.env edit

reload now should not occur

Add gunicorn

note differences

Add gunicorn runner

confirm no reload and works

add .env to reload

confirm reload now works

Edited

- `poetry.lock`
- `__main__.py`
- `pyproject.toml`

Added
`gunicorn_runner.py`
