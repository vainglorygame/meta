Overview
===

  * apigrabber: microservice to fetch data from API
  * processor: microservice to insert data into database
  * cruncher: microservice to calculate statistics
  * analyzer: machine learning tool
  * bridge: microservice for communication between frontend and backend
  * vainsocial: web frontend
  * discordbot: Discord frontend
  * vainglorygame.github.io: documentation repository
  * docs: more documentation
  * vaindock: Docker containers for services, databases and everything else

Setup
===

`git clone --recursive https://github.com/vainglorygame/meta`

Enter `vaindock/` and [follow the instructions there](https://github.com/vainglorygame/vaindock/blob/develop/Readme.MD).

Updating
===

`git submodule update --recursive --remote`
