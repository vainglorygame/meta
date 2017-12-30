Overview
===

  * apigrabber: microservice to fetch data from API
  * processor: microservice to insert data into database
  * cruncher: microservice to calculate statistics
  * analyzer: microservice to calculate TrueSkill
  * bridge: microservice for communication between frontend and backend
  * telesucker: microservice to fetch Telemetry data
  * shrinker: microservice to process Telemetry data
  * orm: shared database models and mappings

Setup
===

`git clone --recursive https://github.com/vainglorygame/meta`

Updating
===

`git submodule update --recursive --remote`
