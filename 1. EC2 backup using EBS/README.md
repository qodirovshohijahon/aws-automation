**Task one**

**How can you automate EC2 backup using EBS?**

**Use the following steps in order to automate EC2 backup using EBS:**

- :one: Get the list of instances and connect to AWS through API to list the Amazon EBS volumes that are attached locally to the instance.
- :two: List the snapshots of each volume, and assign a retention period of the snapshot. Later on, create a snapshot of each volume.
- :three: Make sure to remove the snapshot if it is older than the retention period.