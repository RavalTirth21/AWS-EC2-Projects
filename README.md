# 🚀 AWS EC2 Practical Projects

This repository contains two major EC2-based projects demonstrating real-world AWS skills:

1. **EC2 Auto Scaling with Load Balancer & CloudWatch Alarms**
2. **Full-Stack EC2 Deployment with EBS, Snapshots, AMI, and Launch Templates**

Each project includes step-by-step implementation with screenshots and outcomes.

---

## 📘 Project 1: EC2 Auto Scaling with Load Balancer & CloudWatch Alarms

### 🧰 Services Used

- Amazon EC2
- Auto Scaling Group (ASG)
- Application Load Balancer (ALB)
- Target Groups
- CloudWatch Alarms

### 🔧 Objective

This project demonstrates how to:
- Create and configure an Auto Scaling Group
- Attach an Application Load Balancer (ALB)
- Set Target Tracking Scaling Policies
- Configure CloudWatch Alarms to monitor CPU usage
- Stress test EC2 to trigger scaling automatically

### 🧑‍💻 Steps with Screenshots

1. **EC2 Instances Dashboard**  - `01-EC2-Instances-Dashboard.png`
2. **Create Target Group**  - `02-TargetGroup.png`
3. **Create Load Balancer**  - `03-LoadBalancer.png`
4. **Configure Auto Scaling Group**  - `04-AutoScaling.png`
5. **Target Tracking Scaling Policy**  - `05-Target_Tracking_Policy.png`
6. **Launch Auto Scaling Instance**  - `06-AutoScaling_Instance.png`
7. **Trigger Auto Scaling by CPU Stress**  - `07-AutoScaling-Trigger-By-CPU-Stress.png`
8. **CloudWatch CPU Utilization Alarms**  - `08-CloudWatch-CPU-Utilization-AutoScaling-Alarms.png`
9. **InAlarm State Triggered**  - `09-CloudWatch-CPU-Alarms-InAlarm-State.png`
10. **Alarm Graph Showing CPU Spike**  - `10-CPUUtilization-Alarm-Graph-InAlarm.png`
11. **New EC2 Instance Launched Automatically**  - `11-AutoScaling-TargetTracking-InstanceLaunch.png`

### ✅ Outcome

- Auto Scaling works based on real-time CPU usage
- Load Balancer ensures high availability
- CloudWatch monitors and triggers scaling effectively

---

## 📘 Project 2: Full-Stack EC2 Deployment with EBS, Snapshots, AMI & Launch Templates

### 🧰 Services Used

- Amazon EC2
- Amazon EBS
- Snapshots
- AMIs
- Launch Templates
- Key Pairs
- Security Groups

### 🔧 Objective

This project covers:
- EBS volume creation, mounting, unmounting
- Snapshot and restoration
- EC2 instance management
- AMI and launch template configuration

### 🧑‍💻 Steps with Screenshots

1. **Create Security Group**  - `01-SecurityGroupCreation.png`
2. **Create Key Pair**  - `02-KeyPair.png`
3. **Add User Data Script**  - `03-UserData.png`
4. **Launch EC2 Instance**  - `04-InstanceCreated.png`
5. **Allocate Elastic IP**  - `05-Elastic-IP-Allocated.png`
6. **Connect via SSH**  - `06-SSH-Configured.png`
7. **Create EBS Volume**  - `07-EBS-Volume-Created.png`
8. **Attach Volume to Instance**  - `08-Volume-Attach-Instance.png`
9. **Mount Volume (Temporary)**  - `09-ec2-mount-volume-once.png`
10. **Add to `/etc/fstab` for Auto Mount**  - `10-add-ebs-volume-to-fstab.png`
11. **Create Snapshot**  - `11-Snapshot-EBS-Volume.png`
12. **Unmount Volume**  - `12-Unmount-EBS-Volume.png`
13. **Delete Volume**  - `13-Deleted-EBS-Volume.png`
14. **Create Volume from Snapshot**  - `14-Volume-From-Snapshot.png`
15. **Attach Restored Volume**  - `15-Attach-Snapshot-Volume.png`
16. **Mount Restored Volume**  - `16-Mount-Snapshot-Volume.png`
17. **Create EC2 Launch Template**  - `17-LaunchTemplate-Creation.png`
18. **Create AMI from EC2**  - `18-AMI-Created.png`

### ✅ Outcome

- Full EC2 lifecycle managed via AWS Console
- Data restored using snapshots
- AMI created for future scalable deployment

