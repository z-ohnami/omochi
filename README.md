# README

## Memo

```
echo '2.4.3' > .ruby-version
bundle init
vim Gemfile
bundle install --path=.bundle
bundle exec rails new . --skip-coffee --skip-turbolinks --skip-sprockets
bundle binstubs bundler --force
vim Gemfile (webpacker, slim-rails, faker)
yarn add rails-ujs
yarn add postcss-smart-import
yarn add axios
bin/rake webpacker:install
rm -rf app/assets
mv app/javascript app/frontend
cd app/frontend
mkdir stylesheets
mkdir javascripts
mkdir images
touch images/.keep
touch stylesheets/.keep
touch javascripts/.keep
vim config/webpacker.yml
bin/rake webpacker:install:vue
bin/webpack
bin/rails s
```
