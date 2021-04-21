<img src="./logo.png" alt="Logo - Laravel Circuit Breaker"  width="80%" height="80%">

![Licence](https://img.shields.io/badge/licence-MIT-blue)
![Package Stars](https://img.shields.io/badge/stars-%E2%98%85%E2%98%85%E2%98%85%E2%98%85%E2%98%85-yellow)

Everyweek a new Pattern + Article on www.medium.com/@anhaia.gabriel and www.medium.com/mestredev

# PHP 8 - Design Patterns

This repository was created to show the implementation of a variety of Design Patterns using PHP 8.
There is no dependency on a framework, and the examples are the most real as possible based on my own experiences solving real-life problems. Once you learn the design pattern and its concept, it will be effortless to apply it in any PHP project.

## Patterns

- Template Method [[Learn]](https://medium.com/mestredev/template-method-php-8-a357f3665a4b)
- Strategy [[Learn]](https://medium.com/mestredev/strategy-in-php-8-design-patterns-2044e5ef54ed)
- Adapter [[Learn]](https://medium.com/mestredev/adapter-php-8-75e00034ae48)
- Null Object

## Dependencies

- Docker

## Running the project

I strongly recommend that you follow the articles (links above) and run it with Docker. It will be much easier, and you need to install Docker on your computer, independent of the OS you are using.
With a few commands, you will run/test all the Design Patterns implemented through the course.

Build de container:

```# docker build -t design-patterns .``` or if you preffer ```# make build```

Run the following command in order to test the design patterns:

```# make help``` and then you will see the list of commands

You just need to run the command with the pattern you want to test, for example:

```# make strategy```
