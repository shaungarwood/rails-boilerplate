# Shaun's Rails Boilerplate

Just to save me a little time for coding homework

1. docker compose for postgres
2. environment files for docker and database.yml
3. gems:
    1. draper (decorater)
    2. strong_migrations (cause I'll make foolish migration choices)
    3. dotenv-rails
    4. factorybot
    5. rspec
    6. rubocop

To get started:
```
cp .env.example .env.development && cp .env.example .env.test
docker-compose up -d
bundle exec rails db:create
```
