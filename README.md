# Coursana4

A project managment application build on ruby, and rails. 

## Dependencies
- Ruby v2.4.10
- Rails v4.2.8
- Milia v1.2.0 resource: [https://github.com/jekuno/milia/tree/rails4-support](https://github.com/jekuno/milia/tree/rails4-support)
- Devise v3.4.0 resource: [https://github.com/heartcombo/devise/tree/v3.4.0](https://github.com/heartcombo/devise/tree/v3.4.0)

## Installation (Local)

Ensure that a local instance of Postgres is running with the correct database referenced in your database.yml file<br/>

clone the repository: 

```
https://github.com/adamtlee/coursana4.git
```

TODO: [Milia Gem modification details here] 

Install the Gem dependencies: 

```
bundle install
```

Run the existing migrations: 

```
bundle exec rake db:migrate
```

