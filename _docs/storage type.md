---
title: type of storage
permalink: /docs/my-page/
---


Azure Storage




""can you imagine application wihout storage?""




Azure storage is the Microsoft cloud storage solution for modern data storage solution.


Core storage services

	- Azure Blob
	- Azure File
	- Azure Table
	- Azure Queue
	- Azure Disk

Selecting storage account base on your requirement 

Storage account use cases: 

	Azure Blobs:
	
		- Use when your application support streaming and random access scenarios
		
		-  if you want to be able to access your application data from anywhere.
		
		- If you want to build enterprise data lake on azure platform & perform bis data analytics.
		
		
	Azure Files:
		
		- In case of the "lift and shift" application to cloud.
		
		- If you use file share or replace the on-premises file servers.
		
		- Want to access any tool or data from the multiple VMs.
	
	Azure Tables:
	
		- To store the structured NoSQL data in cloud.
		
		- If you want to storage the flexible database then table storage is the goof option.
	
	
	Azure Queues:
	
		- Queues allow for the asynchronous message queuing between application components.
	
	Azure Disks:
	
		- If you want to data to be persistently stored and accessed from an attached virtual hard disk.
		- It will helpful during the life and shift.
	
	

	Deep dive Azure Blob storage
	
	Features:
		- It's Microsoft object storage solution for the cloud.
		- You can store the images and Documents to browse.
		- In azure blob storage you can store the files for the distributed access.
		- You can also stores the videos and audios in blob storage.
		- You can also utilize the blob storage for the backup and restore solutions so it will use to the any disaster recovery.
	
	
	How to access the blob storage?
		- You can access the content of the blob storage from anywhere over the HTTPS & HTTPS protocol.
		- You application or users can access the blob over;
			i. URL's
			ii. Azure Storage REST API's
			iii. Azure CLI
			iv. Azure storage client library (i.e. .Net, Node.js, Pythone,PHP and Ruby)
	
	Type of Blobs
	
		- Blocks blob
			- Blocks blob use to store Text and Binary data. 
			- It is made up of the blocks and data it can be manage individually.
	
	
		- Append Blobs
			- Appen blob is also made up of the blocks blob but it's used the for the append operations.
			- EX- To store the system logs so that the every time log can get recorded in the file with the append way.
			       To sore the application logs or else automatization logs.
			
		- Page Blobs
			- In page blobs you can store the random access files up to 8TB.
			- Page blobs you can store the VHD file and use that file as disk to the Azure VM.
		
	 
	


Geo-Redundant Storage (GRS)

Geo-Zone Redundant Storage (GZRS)

Read-Only GRS (RA-GRS)

Read-Only GZRS (RA-GZRS)






























![image](https://user-images.githubusercontent.com/44284581/121773490-f1acca80-cb99-11eb-9a71-cddf1dd8b003.png)
