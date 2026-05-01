# aws-cloud-basics
1) What is “Cloud” (definition)

In general, cloud computing is using computing resources (like servers, storage, databases, networking, etc.) that are provided and run by a provider over the internet, instead of running everything on your own hardware.

Key ideas:

• On-demand: you can get resources when you need them

• Elastic/scalable: scale up/down as demand changes

• Pay-as-you-go: you usually pay based on usage

• Managed: much of the infrastructure is handled by the provider
2) What is EC2 (Amazon Elastic Compute Cloud)

EC2 is AWS’s service for running virtual servers in the cloud.

With EC2, you can:

• Launch a virtual machine (“instance”) with chosen CPU, memory, storage, and networking

• Run applications, websites, APIs, scripts, etc.

• Control the OS (e.g., Ubuntu, Amazon Linux, Windows), install software, and configure the server

Core concept:

• You create an EC2 instance → AWS runs it → your application runs on it.
Quick link between them

• Cloud = the big environment where compute/storage/etc. are provided

• EC2 = one specific AWS service inside that cloud environment that provides compute (virtual servers)

Understanding flow (how to think about it)

1. You need computing power (server)

2. In AWS cloud, you don’t buy/maintain physical servers

3. You use EC2 to provision a virtual server instance

4. You deploy and run your application on that instance
5.
6. What is S3 (Amazon Simple Storage Service)?

S3 is AWS’s cloud storage service. It stores data as objects inside buckets.

Key terms

• Bucket: the top-level container (like a folder/collection, but with global naming rules).

• Object: the actual data you store (file/content) plus metadata.

• Object key / path: the “name” (often looks like folders, e.g., images/cat.jpg).

• Region: where your data is stored.
What S3 is used for

• Storing and serving files (images, videos, backups)

• Static website hosting (in some configurations)

• Data backup and archiving

• Big data lakes / storing datasets

• Application storage (uploads/downloads)
Common features (high level)

• Durable storage (designed for very high data durability)

• Access control: permissions via IAM policies, bucket policies, and ACLs (depending on setup)

• Versioning: keep old versions of objects

• Lifecycle policies: move data between storage classes or expire it

• Encryption: protect data at rest (and in transit via HTTPS)
Understanding flow (how to think about it)

1. You create a bucket (where data lives).

2. You upload a file → AWS stores it as an object in that bucket.

3. You set permissions (who can read/write).

4. Optional: enable versioning, lifecycle, and encryption.

5. Your applications/users can upload/download objects from S3.
