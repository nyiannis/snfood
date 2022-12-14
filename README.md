# snfood
Create for docker environment for development.

URLS:
MainSite: https://snfood.dev

SMTP DEV: http://localhost:9002
MyPHP Admin: http://snfood:9004

Configuration local environment hosts:

- Update hosts file:
  127.0.0.1 snfood.dev;

Initial docker yml for the first time:
- Run in terminal : docker-compose up -d --build

Configuration WP:
- Connect to https://vivestia.dev
- Configure wordpress base on the UI.

Stop in terminal : docker-compose down

Install/Configuration WP-CLI
View :
- docker-compose run --rm wp user list
  Install Plugins:
- docker-compose run --rm wp plugin install wordpress-seo
  Activate:
- docker-compose run --rm wp plugin activate wordpress-seo
