Teamcity Build Agent
====================

This is a teamcity build agent docker image.

## Install

``` console
docker pull lvitaly/tmagent
```

## Run example

``` console
docker run -d --name=teamcity-agent-1 --link teamcity:teamcity -e TEAMCITY_SERVER=http://teamcity:8111 lvitaly/tmagent
```