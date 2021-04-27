### CLASS 17


# AWS S3 And Lambada



### What’s the difference between a FIFO and a standard queue?

- FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.



### How can the server be assured a message was properly received?

- The reciepnt must emit a recieved event so then the server can remove the message from the queue.



### What classic design pattern is best represented by event driven programming?

- The Obserevr pattern.


### How do you test an event driven system?

- Using jest as a node library and writing tests that check for out puts.


## TERMS:


``` server instances ```

- Its a virtual machine in amazon web services running in  operating sistems.



``` containers  ```

- Containers provide a standard way to package your application's code, configurations, and dependencies into a single object. Containers share an operating system installed on the server and run as resource-isolated processes, ensuring quick, reliable, and consistent deployments, regardless of environment.


``` cloud services ```

- offers a broad set of global cloud-based products including compute, storage, databases, analytics, networking, mobile, developer tools, management tools, IoT, security and enterprise applications. These services help organizations move faster, lower IT costs, and scale.


``` cloud architecture ```

- Cloud computing architecture refers to the components and subcomponents required for cloud computing. These components typically consist of a front end platform, back end platforms, a cloud-based delivery, and a network. Combined, these components make up cloud computing architecture


``` AWS ```

- Amazon Web Services

``` EC2/Beanstalk vs Heroku ```

- Similar cloud based platform.
