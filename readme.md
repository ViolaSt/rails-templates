These templates are based on [Le Wagon's Rails Templates](https://github.com/lewagon/rails-templates)

# Rails Templates

Quickly generate a rails app using a rails boilerplate

## Devise

Get a minimal rails 5 app ready to be deployed on Heroku with Bootstrap, Simple form, debugging gems and a Devise install with a genrated `User` model with an `avatar` attribute.


```bash
gem install rails -v 5.0.3 # Maybe you already have it :)
rails new \
  -T --database postgresql \
  -m https://raw.githubusercontent.com/rodloboz/rails-templates/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
