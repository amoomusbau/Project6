**LAUNCH AN EC2 INSTANCE THAT WILL SERVE AS “WEB SERVER”**

**instances lunched with attached volume**

**![instances](./images/instanceslunched.PNG)**

**Use gdisk utility to create a single partition on each of the 3 disks**

**using the command sudo gdisk /dev/xvdf**

**![partitioncreated](./createdpartition.PNG)**

**using lsblk to confirm the details**

**![alldata](./images/alldetails.PNG)**

** Using pvcreate utility to mark each of 3 disks as physical volumes (PVs) to be used by LVM**

**![physicalvolume](./images/physicalvolume.PNG)**

**Verify that your VG has been created successfully by running sudo vgs**

**![verifycreated](./images/verifycreated.PNG)**

**using the command to update the webser sudo systemctl daemon-reload**

**![alt text](./images/updatingwebserver.PNG)**

**Prepare the Database Server**

**![databaseserver](./images/dfserverdbinstalled.PNG)**

**httpd running**

**![httpdrunning](./images/httpdrunning.PNG)**

**Red Hat Enterprise Linux Test page**

**![redhat](./images/redhatenterprise.PNG)**

**Step 4 — Install MySQL on your DB Server EC2**

**![mysqlinstalled](./images/mysqlinstalled.PNG)**

**Step 5 — Configure DB to work with WordPress**

**![databasecreated](./images/databasecreated.PNG)**

**WORDPRESS INSTALLED**

**![WORDPRESS](./images/wordpressinstalled.PNG)**




