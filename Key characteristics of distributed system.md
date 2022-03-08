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
reliability is achived through **redundancy**
Remove *single point of failures*.

## Availability
