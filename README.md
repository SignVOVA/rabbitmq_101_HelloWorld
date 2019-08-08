# RabbitMQ 101 - Hello World!

RabbitMQ is a message broker: it accepts and forwards messages. You can think about it as a post office: when you put the mail that you want posting in a post box, you can be sure that Mr. or Ms. Mailperson will eventually deliver the mail to your recipient. In this analogy, RabbitMQ is a post box, a post office and a postman.

The major difference between RabbitMQ and the post office is that it doesn't deal with paper, instead it accepts, stores and forwards binary blobs of data ‒ messages.

RabbitMQ, and messaging in general, uses some jargon.

## Getting Started

* Producing means nothing more than sending. A program that sends messages is a producer :

### Prerequisites

Download and run RabbitMQ locally:
https://www.rabbitmq.com/download.html

```
RabbitMQ libraries

RabbitMQ speaks multiple protocols. This tutorial uses AMQP 0-9-1, which is an open, general-purpose protocol for messaging. There are a number of clients for RabbitMQ in many different languages. In this tutorial series we're going to use Pika 1.0.0, which is the Python client recommended by the RabbitMQ team. To install it you can use the pip package management tool:
```

`pip install pika --upgrade`

## Built With

* [Pycharm CE](https://www.jetbrains.com/toolbox/app/) - The Python IDE
* [RabbitMQ Tutorials](https://www.rabbitmq.com/getstarted.html) - These tutorials cover the basics of creating messaging applications using RabbitMQ