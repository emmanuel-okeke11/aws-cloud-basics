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
