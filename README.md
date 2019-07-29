# django-unchained



for this repo.

#### 0) Install python3, pip, virtualenv, django

- python 2.7 will be deprecated in a year, so we'll use v3.
- virtualenv is an environment which can have certain versions of pip packages.


#### 1) Crud for a `Business` model

- the model itself has `title`, `description`, `address` and `employees`.

- Use `drf` to create crud for that model.
- Use Postgres for database.
- Use `Postman` for testing the APIs and when they work flawlessly generate documentations with postman docs.

#### 2) Add a `BusinessEmployee` model

- the model itself has `business`(foreign-key), `employee`(foreign-key) and `is_owner` for now.
- Use `drf` to create crud for that model.
- creating a business should handle an array called employees which creates BusinessEmployee instances and Employee instances.
