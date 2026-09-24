# ShopEasy Cloud Cost Estimate

## 1. Objective

Estimate the major cloud cost components required to run
ShopEasy and identify ways to control infrastructure costs.

This is a planning estimate, not an actual AWS bill.

---

## 2. Assumptions

Current expected traffic:
10,000 users per day

Future expected traffic:
100,000 users per day

The application may experience higher traffic during
sales and promotional events.

---

## 3. Main Cloud Services

### Website / Frontend
AWS S3

Purpose:
Host the ShopEasy static website.

Cost factors:
- Amount of data stored
- Number of requests
- Data transferred

---

### Backend / API
AWS EC2

Purpose:
Run the ShopEasy backend application.

Cost factors:
- Number of EC2 instances
- Instance size
- Running hours
- Traffic

---

### Database
AWS RDS

Purpose:
Store users, products and orders.

Cost factors:
- Database instance size
- Storage
- Backups
- Data transfer

---

### Product Storage
AWS S3

Purpose:
Store product images and other files.

Cost factors:
- Storage size
- Number of requests
- Data transfer

---

### Monitoring
AWS CloudWatch

Purpose:
Monitor application and infrastructure health.

Cost factors:
- Metrics
- Logs
- Alerts
- Log storage

---

## 4. Cost Optimization Plan

ShopEasy should control costs by:

- Using only the required EC2 capacity
- Scaling infrastructure based on traffic
- Removing unused resources
- Monitoring storage growth
- Reviewing CloudWatch logs regularly
- Using caching/CDN when traffic increases
- Choosing infrastructure capacity based on actual usage

---

## 5. PM Cost Decisions

Before increasing infrastructure capacity, the PM should
consider:

- Current traffic
- Expected growth
- Performance requirements
- Business importance of the feature
- Infrastructure cost
- Expected customer impact

The goal is to balance performance, reliability and cost.

---

## 6. Future Cost Review

As ShopEasy grows, cloud costs should be reviewed regularly.

The team should compare:

Actual usage
      ↓
Infrastructure cost
      ↓
Performance
      ↓
Business requirements

This helps the team make informed infrastructure decisions.