# DockerHubの使い方

下記のようなDockerfileを記述

```
FROM ubuntu:16.04

RUN apt-get update -y && apt-get upgrade -y && apt-get install cowsay -y

CMD ["/usr/games/cowsay", "DockerHubとマングース"]
```
