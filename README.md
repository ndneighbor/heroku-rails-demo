# README

This is a sample Rails application used to show off Railway's One Click Heroku Deploys

## Developing Locally

For a non-Railway development flow make sure that `redis`, `psql`, `foreman` is installed on your machine.

To run the application locally run

```
bundle install
```

then

```
foreman start -f Procfile.dev
```

## Developing on Railway

When deploying on Railway, Rails will not be able to find pSQL or Redis. Be sure to add the requisite services.
