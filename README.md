# llm-chatbot-with-docker
Here is a demo with llama2 model, and docker to running local chatbot like to chatgpt

## Requirements

You need has docker and docker-compose

## Installation

step by step.

```bash
  git clone https://github.com/aliexerleo/llm-chatbot-with-docker.git
  cd llm-chatbot-with-docker/
  docker-compose up -d
  docker-compose exec ollama ollama pull llama2
  or 
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

## Authors

- [@aliexerleo](https://github.com/aliexerleo)
