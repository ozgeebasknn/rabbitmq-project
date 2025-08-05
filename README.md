📨 Simple RabbitMQ Messaging System with Node.js
This is a basic project that demonstrates how to implement a messaging system using RabbitMQ and Node.js. It includes a publisher that sends messages to a queue and a consumer that receives and processes those messages.

🎯 Purpose
The main goal of this project is to help understand the core working mechanism of RabbitMQ. A list of sample users is defined in a data.json file, and the publisher sends each user ID as a message to a queue. The consumer listens to the queue and matches the incoming ID with user information.
🚀 Installation & Run
Make sure RabbitMQ is installed and running locally.

Clone this repository:
git clone https://github.com/ozgeebasknn/rabbitmq-project.git
cd rabbitmq-project

Install the dependencies:
npm install amqplib

Start the publisher in one terminal:
node publisher.js

Start the consumer in another terminal:
node consumer.js
