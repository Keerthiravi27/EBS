# EBS


# WORKING WITH EBS

# AIM:

In this lab environment, access to AWS services and service actions might be restricted to the ones that are needed to complete the lab instructions. You might encounter errors if you attempt to access other services or perform actions beyond the ones that are described in this lab.

# OBJECTIVE:

*Create an Amazon EBS volume *Attach and mount your volume to an EC2 instance *Create a snapshot of your volume *Create a new volume from your snapshot *Attach and mount the new volume to your EC2 instance

# Illustration:

STEP 1: In this step, you will create and attach an Amazon EBS volume to a new Amazon EC2 instance.You will see an existing volume that is being used by the Amazon EC2 instance. This volume has a size of 8 GiB, which makes it easy to distinguish from the volume you will create next, which will be 1 GiB in size. 
<img width="1873" height="837" alt="image" src="https://github.com/user-attachments/assets/865c0269-e39b-441d-84cc-e7e51965d216" />


STEP 2: In this step, you will connect to the Lab EC2 instance using Session Manager.You can now attach your new volume to the Amazon EC2 instance.
<img width="1031" height="768" alt="image" src="https://github.com/user-attachments/assets/9d09e10c-5e74-4401-92d1-09bc4c2e83bb" />


STEP 3: In this step, you will add the new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point.
<img width="1028" height="821" alt="image" src="https://github.com/user-attachments/assets/213a3072-f121-4802-803a-5ff26e962f7e" />


STEP 4: You can create any number of point-in-time, consistent snapshots from Amazon EBS volumes at any time. Amazon EBS snapshots are stored in Amazon S3 with high durability. New Amazon EBS volumes can be created out of snapshots for cloning or restoring backups. Amazon EBS snapshots can also be easily shared among AWS users or copied over AWS regions.
<img width="1028" height="821" alt="image" src="https://github.com/user-attachments/assets/cfdf77e4-7ab3-4e73-aa20-390995b18d40" />


STEP 5:

<img width="833" height="786" alt="image" src="https://github.com/user-attachments/assets/552fbe75-5f03-4fc2-91a7-6b3c90214d7a" />

<img width="713" height="510" alt="image" src="https://github.com/user-attachments/assets/a20e10a5-edc9-4d5e-b6b6-24621f9793fd" />


# RESULT: 

Successfully created, managed, and deleted an EBS bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon EBS.
