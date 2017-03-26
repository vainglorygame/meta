Overview
===

  * apigrabber: microservice to fetch data from API
  * processor: microservice to insert data into database
  * compiler: microservice to calculate simple statistics
  * analyzer: microservice to calculate using machine learning
  * cruncher: microservice to calculate service-wide statistics
  * preloader: microservice to prefetch matches for players that users are likely to view
  * updater: microservice for communication between frontend and backend
  * vainsocial: web frontend
  * discordbot: Discord frontend
  * minionlivesmatter: fun frontend
  * vainglorygame.github.io: out-of-date documentation repository
  * vaindock: Docker containers for services, databases and everything else

Setup
===

`git clone --recursive https://github.com/vainglorygame/meta`

Enter `vaindock/` and [follow the instructions there](https://github.com/vainglorygame/vaindock/blob/develop/Readme.MD).

Updating
===

`git submodule update --recursive --remote`
