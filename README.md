## What is AMQP?

AMQP (Advanced Message Queuing Protocol) is an open standard application layer protocol for message-oriented middleware. It defines a binary, peer-to-peer protocol for reliable, secure, and interoperable messaging between systems. AMQP provides features like message orientation, queuing, routing (including point-to-point and publish/subscribe), reliability, and security.

## Explanation of `guest:guest@localhost:5672`

* **First `guest`**: the username used to authenticate with the AMQP broker (RabbitMQ by default).
* **Second `guest`**: the corresponding password for that user.
* **`localhost:5672`**: the network address and port of the AMQP broker. Here, `localhost` means the broker is running on the same machine, and `5672` is the default port on which RabbitMQ listens for AMQP connections.
