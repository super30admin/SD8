# SD8


**Designing an API Rate Limiter

**What to be designed?**

1. Imagine a service which receives large number of requests, but it can only serve a limited number of requests per second.To overcome this, we need some kind of throttling or rate limiting mechanism that allows only a certain number of requests, so our service can respond to all of them.
2. In short, rate limiter limits the number of events an entity (user,device,IP) can perform in a particular time window.For example,
    a. A user can send only one message per second.
    b. A user is allowed three failed credit card transactions per day.
    c. A single IP can create only twenty accounts per day.
3. Thus a rate limiter should cap the number of requests a sender can issue in a specific time window.After the cap is reached, requests are blocked.


**TO DO : Follow the below framweork to design System. Mandatory upload of hand drawn photos of design.**

**Capacity Estimation and Constraints**

What will your estimations of scale? As a system design student you should be able to make intelligent assumptions based on real life systems. 

**System APIs**

**Database Design**

**Basic System Design and Algorithm**

**Data Partitioning and Replication**

**Caching**

**Load Balancing**

**Handling Edge cases in given system**
    