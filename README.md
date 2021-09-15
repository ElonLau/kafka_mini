# kafka mini project

- Building A Streaming Fraud Detection System With Kafka And
Python
- In this tutorial, we will get our hands dirty and create our first streaming application
backed by Apache Kafka using a Python client. We will try and make it as close as possible
to a real-world Kafka application.
What we'll build is a real-time fraud detection system. We'll do so from scratch. We will
generate a stream of transactions and you will write a Python script to process those stream
of transactions to detect which ones are potential fraud.
- Are you excited?

# What's next?

That's it — we now have a working fraud detection pipeline:
● A local Kafka cluster that acts as a centralised streaming platform.
● A transaction generator which produces transactions to the cluster.
● A fraud detector which processes transactions, detects potentially fraudulous ones
and produces the results in two separate topics.
You might be wondering — what's next?
There are many ways in which this system could be improved or extended. Here are just a
few ideas:
● Implement a better fraud detection algorithm
● Send alerts or reports about fraudulent transactions somewhere: email, notifications,
a Slack bot — anything!
