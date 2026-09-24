# ShopEasy Scalability Plan

## 1. Objective

ShopEasy should be able to handle growth in users and traffic
without major performance issues or service downtime.

Current expected traffic:
10,000 users per day

Future expected traffic:
100,000 users per day

The system should also handle sudden traffic spikes during
sales and promotional events.

---

## 2. Current Architecture

Website:
AWS S3

Backend:
AWS EC2

Database:
AWS RDS

Product Images / Files:
AWS S3

Monitoring:
AWS CloudWatch

---

## 3. Scalability Challenges

As traffic increases, ShopEasy may face:

- Higher backend requests
- Increased server CPU and memory usage
- More database connections
- Slower response times
- Higher traffic during sales
- Increased storage requirements

---

## 4. Backend Scalability

Current:
One EC2 instance handles application requests.

Future:
Use multiple EC2 instances behind a Load Balancer.

Benefits:

- Distributes traffic across servers
- Prevents one server from becoming overloaded
- Improves availability
- Supports horizontal scaling

---

## 5. Database Scalability

RDS will store:

- User data
- Product data
- Order data

As the number of users increases:

- Monitor database CPU and storage
- Increase database capacity when required
- Optimize frequently used queries
- Use read replicas when read traffic becomes high

---

## 6. Traffic Spike Management

During sales or promotions:

- Monitor traffic using CloudWatch
- Scale backend capacity when traffic increases
- Distribute requests across multiple servers
- Monitor database performance
- Set alerts for high CPU and traffic

---

## 7. Monitoring

AWS CloudWatch will monitor:

- EC2 CPU utilization
- Database performance
- Request/traffic metrics
- Application health
- Storage usage

Alerts should notify the team when important thresholds
are exceeded.

---

## 8. PM Success Criteria

The scalability plan should help ShopEasy:

- Handle increasing user traffic
- Maintain acceptable response times
- Reduce downtime risk
- Handle sudden traffic spikes
- Monitor system health
- Scale infrastructure based on demand

---

## 9. Future Improvements

As ShopEasy grows, the architecture can be extended with:

- Load Balancer
- Auto Scaling
- Database read replicas
- Caching
- CDN
- Improved monitoring and alerting
