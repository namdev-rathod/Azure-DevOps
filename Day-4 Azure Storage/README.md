# 📘 **Day-4: Azure Storage Services**

1. **Azure Blob Storage**

   * Object storage for unstructured data (images, videos, backups)
   * Tiers: Hot, Cool, Archive
   * Access via REST API, SDKs, or Azure Portal

2. **Azure Files**

   * Managed file shares (SMB/NFS)
   * Mountable from Windows, Linux, macOS
   * Like AWS EFS

3. **Azure Disks**

   * Managed disks for VMs (OS and data disks)
   * Types: Standard HDD, Standard SSD, Premium SSD, Ultra Disk

4. **Azure Storage Accounts**

   * Logical container for all storage types
   * Supports replication options (LRS, ZRS, GRS, RA-GRS)

5. **Azure Queue Storage**

   * Message queue for asynchronous communication between apps
   * Simple messaging system, like SQS

6. **Azure Table Storage**

   * NoSQL key-value store
   * Schema-less, lightweight for structured data

7. **Azure Backup & Azure Site Recovery (optional)**

   * Backup: Protect VMs, files, SQL databases
   * Site Recovery: DR solution for failover

8. **Hands-On Practice**

   * Create a storage account
   * Create Blob container and upload a file
   * Create File share and mount it to a VM
   * Attach Managed Disk to VM
   * Explore replication types (LRS vs GRS)
   * Create a simple Queue and add messages

---