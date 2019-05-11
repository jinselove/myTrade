myTrade
==========
This repository is used as my Machine learning / Deep learning playground with applications on cryptocurrency and stock trading. This README file is structured as follows: 

- [Getting Started](#Getting-Started)
- [Acknowledge](#Acknowledge)
- [References](#references)

## Getting-Started

### Install 

- Requirements:

> - [Docker](https://www.docker.com)

> - [Docker-compose](https://docs.docker.com/compose/)


- Build 

> - ``cd build/ && sudo make`` (more informations about Makefile commands in the [References] Section (#references))

## Acknowledge
The initial motivation of building this repository is from this [Medium Post on How to make profits in cryptocurrency trading with machine learning](https://medium.com/smileinnovation/how-to-make-profits-in-cryptocurrency-trading-with-machine-learning-edb7ea33cee4). And some of the source codes from [cryptocurrency-trading](https://github.com/smileinnovation/cryptocurrency-trading) are used in some of the modules. 


## References

_Makefile commands available_:

|   **commands name**   | **description**                    |
|:---------------------:|:---------------------------------- |
|        `make`         | 1. down each service               |
|                       | 2. build basic project             |
|                       | 3. run project                     |
|                       |                                    |
|    `make build_up`    | 1. build basic project             |
|                       | 2. run project                     |
|                       |                                    |
|     `make build`      | build basic project.               |
|                       |                                    |
|       `make up`       | run project                        |
|                       |                                    |
|      `make down`      | down project                       |
|                       |                                    |
|       `make ps`       | list container                     |
|                       |                                    |
|      `make logs`      | display all platform logs          |
