# Key characteristics of distributed systems

1. Scalability
2. Reliability
3. Availability
4. Efficiency
5. Serviceability or maintainability

## Scalability

System ability to **grow and manage** increased demand.

Reasons for scaling: *increased volume of data, increased amount of work or transactions*

*Horizontal scaling and Vertical scaling*

### Horizontal scaling 
Add **more servers** to the pool of resources.
Easier to scale dynamically.

### Vertical scaling
Add **more power** (CPU, RAM, Storage, etc..) to an existing server.<br>
Involves downtime, and comes with upper limit.

###### Examples
*Horizontal scaling* - MongoDB, Cassandra.<br>
*Vertical scaling* - Mysql. (Easy way to scale from switching from smaller to bigger machines)

## Reliability 
Probability a system will fail in a given duration; P(sf).
Keeps delivering its services even when one or more software or hardwared components fail.<br>
reliability is achived through **redundancy**.<br>
Remove *single point of failures*.

## Availability
**Time** a system remains operational to perform its required function in a given period of time. <br>
Measured in **percentage of time**.<br>

Availability takes into account: *maintainability, repair time, spares availability, and other considerations.*<br>  

### Realiability vs Availability
If a system is **reliable**, it is **available**.<br>
However, If a system is **available**. It is **not necessarily** reliable.<br>

It is possible to achieve high **availability** even with an unreliable product by minimizing repair time and ensuring that spares are always available when needed.<br>

*Example*:<br>
Let’s take the example of an online retail store that has 99.99% availability for the
first two years after its launch. However, the system was launched without any
information security testing. The customers are happy with the system, but they
don’t realize that it isn’t very reliable as it is vulnerable to likely risks. In the third
year, the system experiences a series of information security incidents that suddenly
result in extremely low availability for extended periods of time. This results in
reputational and financial damage to the customers.


## Efficiency
Two measures of efficiency:
1. Latency - Response time or delay to obtain the first item
2. Throughput (Bandwidth) - Number of items delivered in a given unit time. (eg. second)

## Serviceability or Manageability
Simplicity and speed with which a system can be repaired or maintained. 
Consider: Ease of diagnosing and understanding problems when they occur. easy of making updates or modifications.

Early detection can avoid system downtime.


