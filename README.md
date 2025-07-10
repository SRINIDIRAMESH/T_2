# T2
**TASK 2 → CLOUD MONITORING AND ALERTS**

**COMPANY**: Codtech IT Solution
**NAME**: Srinidi R
**INTERN ID**: CITS0D437
**DOMAIN**: Cloud Computing
**DURATION**: 4 Weeks
**MENTOR**: Neela Santosh

---

**📄 DESCRIPTION**

This task involved configuring and monitoring cloud infrastructure using AWS CloudWatch. Key objectives included:

* Creating alarms for CPU utilization on EC2 instances.
* Observing instance performance through dashboards.
* Setting up metrics for Disk I/O and Network traffic.
* Ensuring alerting actions were enabled for effective response.

---

**🌟 FEATURES IMPLEMENTED**

* ✅ **CloudWatch Alarm**: A custom alarm (`HighCPUUtilizationAlarm`) was configured to monitor EC2 CPU usage. It triggers if CPU usage exceeds 80% for 5 minutes.
* ✅ **Monitoring Dashboard**: A CloudWatch dashboard (`task2`) was created, visualizing multiple metrics like CPU credit balance, network packets, and disk operations.
* ✅ **Instance Integration**: The EC2 instance named `MyMonitoringInstance` was actively monitored and integrated with alarms.
* ✅ **Alarm Action Enabled**: Verified that alarm actions are successfully enabled, ensuring alert notifications can be triggered.
* ✅ **Instance Health Checks**: Status checks passed (2/2), confirming the instance is running correctly and being monitored.

---

**🛠 TECHNOLOGIES USED**

* **Amazon EC2** – Hosting the monitored instance.
* **Amazon CloudWatch** – For metric collection, dashboards, and alarms.
* **AWS Console** – GUI-based setup for cloud monitoring tasks.
* **t2.micro Instance Type** – Used for demonstration and monitoring.

---

**🔗 HOW TO ACCESS THE FILE**

1. **CloudWatch Dashboard**:

   * Navigate to: `CloudWatch > Dashboards > task2`
   * View metrics such as:

     * CPUCreditBalance
     * DiskWriteOps
     * NetworkPacketsIn
     * NetworkIn

2. **EC2 Alarm**:

   * Navigate to: `CloudWatch > Alarms > HighCPUUtilizationAlarm`
   * Condition: CPUUtilization > 80% for 1 datapoint within 5 minutes.

3. **Monitored EC2 Instance**:

   * Navigate to: `EC2 > Instances`
   * Instance Name: **MyMonitoringInstance**
   * Instance ID: `i-06bb5f64ca3ea6850`
   * Status: Running (t2.micro)
   * Health Checks: ✅ 2/2 checks passed
   * Alarm Status: Linked and visible via “View alarms”

---

OUTPUT:
<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/960f7767-fd6d-4623-95f1-ab55b0b105d1" />

<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/913073de-d412-4706-a86e-a90b7943a98b" />

<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/c6e7e3d4-0a58-4b37-a310-01b113fd21a9" />
