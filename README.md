# City of Brass
https://cityofbrass.io

## Config
**rename**: /config/application.example.yml to /config/application.yml and add proper settings

## Build
`docker-compose build`

## Seed
`docker-compose run cityofbrass rake db:setup`

## Run
`docker-compose up`

navigate to localhost:5000
	- login as user@example.com:password1
	- setup resident

## To change seed user from free to vip
navigate to localhost:5000/admins/login
* login as user@example.com:password1
* Admin menu >> User Admin >> click cogs for user@example.com
	* set status to vip

## Test
`docker-compose run cityofbrass rails test`
