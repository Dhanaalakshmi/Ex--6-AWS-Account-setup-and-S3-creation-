# Ex--6-AWS-Account-setup-and-S3-creation


## Introduction
In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

## Objectives
Create a Bucket in Amazon S3.
Add Objects (files and folders) to the bucket.
Access, move, download, and delete the objects.
Delete the Bucket.

### Step 1: Choose S3 Service
Choose the S3 service from the list of services provided by AWS.

### Step 2: Create a Unique Bucket
After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.


For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

### Step 3: Upload Files to the Bucket
Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., https://s3-ap-southeast-2.amazonaws.com/...) to share it.

### Step 4: Upload a Folder
You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

### Step 5: Delete the Bucket
To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

## Output:
<img width="1403" height="650" alt="Screenshot 2025-10-05 191036" src="https://github.com/user-attachments/assets/930c0989-0807-4d81-b107-8035e9d18adb" />
<img width="1479" height="736" alt="Screenshot 2025-10-05 191053" src="https://github.com/user-attachments/assets/82f02bb6-3a01-4eb0-b9ba-fde0de349cdc" />
<img width="1506" height="739" alt="Screenshot 2025-10-05 191109" src="https://github.com/user-attachments/assets/bbb5259a-74f1-4a4b-a61d-0eaa46ef022f" />
<img width="1487" height="743" alt="Screenshot 2025-10-05 191125" src="https://github.com/user-attachments/assets/a789a78b-ab94-4b39-86f1-801e3ee6ac4c" />

## Result:

Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) instance has been successfully created and launched in AWS.

