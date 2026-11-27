# Day 05 – Create an AWS EBS Volume

## Objective
Create an Amazon EBS volume using the AWS Management Console with the specified configuration.

## AWS Configuration
- **Cloud Provider:** AWS
- **Service:** Amazon Elastic Block Store (EBS)
- **Region:** US East (N. Virginia) – `us-east-1`

## Requirements

| Configuration | Value |
|---|---|
| Volume Name | `datacenter-volume` |
| Volume Type | `gp3` |
| Volume Size | `2 GiB` |
| Region | `us-east-1` |

## Steps Performed
1. Logged into the AWS Management Console.
2. Navigated to the EC2 service.
3. Opened **Elastic Block Store → Volumes**.
4. Clicked **Create volume**.
5. Selected `gp3` as the volume type.
6. Configured the volume size to `2 GiB`.
7. Added the Name tag `datacenter-volume`.
8. Created the EBS volume.

## Outcome
Successfully created an EBS volume named `datacenter-volume` with `gp3` storage and a size of `2 GiB` in the `us-east-1` region.

## Key Learning
- Amazon EBS fundamentals.
- Creating EBS volumes.
- Understanding `gp3` volume type.
- AWS resource management using the AWS Management Console.

---
**Day 05 of my 100 Days of AWS journey.**
