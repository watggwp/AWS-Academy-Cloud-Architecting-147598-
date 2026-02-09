# Module 10 – High Availability, Scaling & Cost Control

---

### Question 1  
Which statement about Amazon EC2 Auto Scaling is accurate?

- A. It can launch Amazon EC2 instances, but customers must terminate instances after they are no longer needed.
- **B. It can launch new Amazon EC2 instances based on a schedule.**
- C. It requires the customer to use Reserved Instances only.
- **D. It can launch Amazon EC2 instances in multiple Availability Zones.**

---

### Question 2  
A DevOps engineer detects that demand for an Auto Scaling group increases by a set amount on weekend days. Which scaling type is MOST appropriate?

- A. Predictive  
- **B. Scheduled**  
- C. Dynamic  
- D. Manual  

---

### Question 3  
An Auto Scaling group must maintain 50% average CPU utilization. Which scaling policy should be used?

- **A. Target tracking scaling**
- B. Simple scaling  
- C. Manual scaling  
- D. Step scaling  

---

### Question 4  
How can a user vertically scale an Amazon RDS database?

- **A. By changing the instance class or size**
- B. By adding read replicas  
- C. By sharding the database  
- D. By creating dedicated read and write nodes  

---

### Question 5  
How can an AWS customer horizontally scale an Amazon Aurora database?

- A. By creating Amazon CloudWatch alarms  
- **B. By adding Aurora Replica instances using Aurora Auto Scaling**
- C. By creating a scaling policy  
- D. By changing the instance type  

---

### Question 6  
How does Amazon DynamoDB perform automatic scaling?

- A. It adds and removes database instances  
- B. It adds read replicas  
- **C. It adjusts the provisioned throughput capacity**
- D. It changes the instance type  

---

### Question 7  
An application uses a custom TCP protocol on port 42000 and must balance connections. Which load balancer should be used?

- A. Gateway Load Balancer  
- **B. Network Load Balancer**
- C. Application Load Balancer  
- D. Classic Load Balancer  

---

### Question 8  
A company must build a highly available website using server-side scripts. Which solution provides the HIGHEST availability with the LEAST cost and complexity?

- A. Amazon S3 static website hosting  
- B. Multi-Region web servers with Route 53 failover  
- **C. Auto Scaling group with Application Load Balancer**
- D. Auto Scaling group with Network Load Balancer  

---

### Question 9  
Users in Region A must fail over to Region B if Region A becomes unhealthy. Which solution meets the requirement?

- **A. Use geolocation routing with failover records in Amazon Route 53**
- B. Use geoproximity routing with a Network Load Balancer  
- C. Use an Application Load Balancer with CloudWatch alarms  
- D. Use latency-based routing with CloudWatch alarms  

---

### Question 10  
A developer wants to stay within AWS Free Tier and avoid unexpected costs with the LEAST effort. What should they do?

- **A. Create an Amazon CloudWatch alarm to notify when billing exceeds $0**
- B. Use SCPs to restrict non-Free Tier services  
- C. Create a CloudWatch billing metric and limit it to $0  
- D. Manually check the billing dashboard every month  
