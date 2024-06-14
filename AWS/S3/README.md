# S3 (Simple Storage Service)

## Overview

Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This service is designed to store and retrieve any amount of data from anywhere on the web.

## Key Concepts

### 1. **Buckets**
   - Containers for storing objects.
   - Each bucket must have a unique name across all of AWS.
   - You can configure access control, versioning, and other properties at the bucket level.

### 2. **Objects**
   - The fundamental entities stored in S3.
   - Consists of the data itself and metadata about the data.
   - Each object is identified by a unique key within a bucket.

### 3. **Storage Classes**
   - Different tiers of storage designed for different use cases:
     - **S3 Standard**: For frequently accessed data.
     - **S3 Intelligent-Tiering**: For data with unknown or changing access patterns.
     - **S3 Standard-IA (Infrequent Access)**: For infrequently accessed data.
     - **S3 One Zone-IA**: For infrequently accessed data in a single Availability Zone.
     - **S3 Glacier**: For archival data with retrieval times ranging from minutes to hours.
     - **S3 Glacier Deep Archive**: For long-term archival with retrieval times of 12 hours.

### 4. **Versioning**
   - Enables you to keep multiple versions of an object in the same bucket.
   - Protects against accidental deletion and allows recovery of prior versions.

### 5. **Access Control**
   - **Bucket Policies**: JSON-based policies that apply to the entire bucket.
   - **IAM Policies**: Define permissions for users and roles accessing S3.
   - **Access Control Lists (ACLs)**: Define individual permissions for objects within a bucket.

### 6. **Encryption**
   - Protects data at rest using encryption.
   - **Server-Side Encryption (SSE)**:
     - **SSE-S3**: Keys managed by S3.
     - **SSE-KMS**: Keys managed by AWS Key Management Service.
     - **SSE-C**: Keys managed by the customer.
   - **Client-Side Encryption**: Data encrypted by the client before uploading to S3.

### 7. **Lifecycle Policies**
   - Automate the transition of objects between storage classes.
   - Define rules to archive or delete objects after a specified period.

### 8. **Data Transfer and Retrieval**
   - **S3 Transfer Acceleration**: Speeds up content transfers to and from S3.
   - **S3 Batch Operations**: Perform large-scale batch operations on S3 objects.
   - **Multipart Upload**: Upload large objects in parts for faster and more reliable uploads.

### 9. **Event Notifications**
   - Configure notifications for specific events such as object creation, deletion, or restoration.
   - Can trigger AWS Lambda functions, SNS topics, or SQS queues.
