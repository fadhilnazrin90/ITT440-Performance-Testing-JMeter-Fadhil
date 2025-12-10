# ITT440-Performance-Testing-JMeter-Fadhil

# Performance Testing using Apache JMeter (Load, Stress & Spike on test.k6.io)

**Name:** Mohd Fadhil Nazrin bin Akhiruddin  
**Student ID:** 2023207096  

# Video Presentation  
https://youtu.be/3JSC4uKGbPw?si=9m-31yZYXsyKzOPk

---

# Summary  
This project evaluates the performance of **test.k6.io** using **Apache JMeter** through three testing methods:

- **Load Test** (50 users, 20s ramp, 2min)
- **Stress Test** (200 users, 10s ramp, 2min)
- **Spike Test** (200 users instant, 2min)

Analysis includes **response time, throughput, sample count, error rate, and behaviour under traffic surge**.

---

# Findings

| Test | Result Summary |
|------|----------------|
| Load Test | Stable response under normal traffic |
| Stress Test | Application remained stable under heavy load |
| Spike Test | Spike caused highest latency, but system recovered |
| Overall | **0% error rate, scalable, stable performance** |

---

# Conclusion  
test.k6.io is reliable and performs well under normal and heavy conditions.  
JMeter successfully provided performance insights through **Load, Stress, and Spike testing**, proving that the application handles traffic efficiently.

