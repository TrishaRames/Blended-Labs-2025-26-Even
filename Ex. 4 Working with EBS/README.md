# Lab 4 – Working with Amazon Elastic Block Store (EBS)

## Author

* **Name**: Trisha R
* **Register Number**: 212224100061
* **Date of Submission**: 05-11-2026

---

## Objective

The objective of this experiment is to understand how Amazon Elastic Block Store (EBS) provides persistent block-level storage for EC2 instances. This lab focuses on creating and attaching an EBS volume, formatting and mounting it on an EC2 instance, storing data, and verifying data persistence after instance reboot.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing EC2 instance (Amazon Linux 2 preferred)
* Basic knowledge of Linux commands

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Amazon EBS
* SSH Client (Terminal / PuTTY)

---

## Tasks Performed

### Task 1: Explore Amazon EBS

Explore the Amazon EBS service through the EC2 dashboard. Observe different volume types such as General Purpose SSD (gp2/gp3), Provisioned IOPS SSD, Throughput Optimized HDD, and Cold HDD.

---

### Task 2: Create an EBS Volume

Create a new EBS volume in the same Availability Zone as the EC2 instance. Choose an appropriate size and volume type.

---

### Task 3: Attach EBS Volume to EC2 Instance

Attach the created EBS volume to the running EC2 instance as an additional block device.

---

### Task 4: Format the EBS Volume

Connect to the EC2 instance using SSH and format the attached volume with a file system (for example, ext4).

---

### Task 5: Mount the EBS Volume

Mount the formatted volume to a directory in the EC2 instance (for example, /data or /mnt/ebs).

---

### Task 6: Store Data in EBS Volume

Create files and directories inside the mounted EBS volume and store sample data.

---

### Task 7: Verify Data Persistence

Reboot the EC2 instance and verify that the data stored in the EBS volume is still available after reboot.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1. The EC2 Dashboard was accessed through the AWS Management Console to explore the Amazon EBS volume types.
2. A new EBS volume was created by selecting the volume type, size, and the same Availability Zone as the EC2 instance.
3. The created EBS volume was attached to the running EC2 instance as an additional block device.
4. The attached volume was formatted using the ext4 file system and mounted to a directory in the EC2 instance.
5. Sample data was stored in the mounted volume, and after rebooting the instance, data persistence was veri


---

## Output Screenshots (Attach 3)

### Screenshot 1: EBS Volume Created

<img width="1912" height="1016" alt="Screenshot 2026-11-04 135050" src="https://github.com/user-attachments/assets/68a5e95e-70fc-4a3a-9597-6c87397ceeee" />


---

### Screenshot 2: EBS Volume Attached to EC2

<img width="1897" height="992" alt="Screenshot 2026-11-04 134554" src="https://github.com/user-attachments/assets/44bfa068-0bd0-4eef-ad72-29c8bcfe186c" />

---

### Screenshot 3: Mounted Volume with Data

<img width="946" height="881" alt="Screenshot 2026-11-04 135231" src="https://github.com/user-attachments/assets/bab93137-4db2-48dc-819c-685183390e86" />


---

## Result / Conclusion

This experiment demonstrated how Amazon EBS provides persistent storage for EC2 instances. By creating, attaching, formatting, and mounting an EBS volume, and by verifying data after reboot, the concept of durable block storage in the cloud was clearly understood.
