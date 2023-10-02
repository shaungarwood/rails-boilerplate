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
1. `cp .env.example .env.development && cp .env.example .env.test`
2. `docker-compose up -d`
3. `bundle exec rails db:create`
