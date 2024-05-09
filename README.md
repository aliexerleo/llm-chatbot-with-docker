# llm-chatbot-with-docker
Here is a demo with llama2 model, and docker to running local chatbot like to chatgpt

## Requirements

You need has docker and docker-compose

## Installation

Step by step.

Quickly way.
```bash
  git clone https://github.com/aliexerleo/llm-chatbot-with-docker.git
  cd llm-chatbot-with-docker/
  docker-compose up -d
  docker-compose exec ollama ollama pull llama2
```

Another way.
```bash
  git clone https://github.com/aliexerleo/llm-chatbot-with-docker.git
  cd llm-chatbot-with-docker/
  docker-compose up -d
  docker exec -it conainter_name /bin/bash
  ollama run llama2
  >>> bye/
  exit
```

Now, you can check the browser in http://localhost:3000/

for stop the containers

```bash
  docker-compose down
```
## Basic Docker command line

# For MacOS
checking docker status
```bash
  docker info >/dev/null 2>&1 && echo "Docker is running" || echo "Docker is not running"
```
start docker service
```bash
  open /Applications/Docker.app
```
# For linux
checking docker status
```bash
  sudo systemctl status docker
```

start docker service
```bash
  sudo systemctl enable docker
  sudo systemctl start docker
```
# for all OS terminal
for show container running and all container information
```bash
  docker ps
```
for entry inside of a specific containers
```bash
  docker exec -it container_name /bin/bash
```
for up some containers with docker-compose
```bash
  docker-compose up -d
```
for stop some containers with docker-compose
```bash
  docker-compose down
```

## References

 - [Ollama website](https://ollama.com/)
 - [Ollama docs](https://github.com/ollama/ollama/blob/main/docs/modelfile.md#valid-parameters-and-values)
 - [Docker](https://www.docker.com/products/docker-desktop/?_gl=1*1s706q5*_ga*NDg0MTcyMzE5LjE3MTM5MjMxMDM.*_ga_XJWPQMJYHQ*MTcxNTI4NDA4NS4xMS4xLjE3MTUyODQzOTcuMzYuMC4w)
 - [Play with docker]( https://www.docker.com/play-with-docker/)


## Extras

- [Intro to NLP](https://www.youtube.com/watch?v=Tg1MjMIVArc)

- [Intro to NLP II](https://www.youtube.com/watch?v=RkYuH_K7Fx4&t=4s)

- [LLMs can doing](https://www.youtube.com/watch?v=uK3tDlzbcTI&t=72s)


## Authors

- [@aliexerleo](https://github.com/aliexerleo)
