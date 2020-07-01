# AWS

A cluster is a group of machines instances or nodes on which the services can be deployed. On amazon those machines are called Amazon Elastic Compute Cloud EC2. It  provides secure, resizable compute capacity in the cloud and is designed to make web-scale cloud computing easier for developers. To know more about EC2, click [here](https://aws.amazon.com/ec2/).

![1](imgs/1.jpg)

1. **Node Pool**: Pool of nodes and complete configurations for that node. Node Pools can be more than one. First node pool will always be Master node pool.
2. **Node Pool**: Name of the Nodepool.
3. **Machine Type**: Instance type determines the hardware (CPU, memory, storage, and networking capacity) of the host computer used for the instance.To know more about machine type, click [here](https://aws.amazon.com/ec2/instance-types/).
4. **Node Count**: Number of nodes in the node pool.
5. **Node Pool Role**: Role of node pool i.e. Master or Slave. (First Node Pool will always be master)
6. **Subnet**: Subnet to associate with the node depending on network.
7. **Security Group**: Security Group to associate with the node depending on network.

![1](imgs/2.jpg)

1. **Key Type**: Key to SSH into nodes, can be new or existing.
2. **Enter Key Name**: In case New Key Type is selected.
   After that click **Generate and Download** to get a new key.
   > **Note:** Save the key file in a safe place .Key is one-time download and cannot be downloaded again. 
3. **AMI ID**: Amazon Machine Image ID that will be used for nodes. AMI provides the information required to launch an instance.
4. **AMI Username**: Username for the image. 

![3](imgs/3.jpg)

1. **Volume Type**: Storage disk type i.e. SSD ,HDD etc. 

   > **Note:** EBS (Elastic Block Store) is a block level storage which can be mounted to the machines or instances and can then be used as any raw block device.

2. **Volume Size**: Size of the disk in GB.

3. **IOPS**: IOPS for the disk.

4. **Docker Data Volume**: To add docker data volume.

5. **Down Arrow Button**: To fetch latest AMIs.
