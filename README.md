# Client-Architecture-with-RDMS-project

1. Creation and configuration of 2 Linux instances

First, two Linux EC2 instances; "Mysql Client" and "Mysql Server" were created on AWS 

![EC2 instances](https://github.com/oghare01/Client-Architecture-with-RDMS-project/assets/141191975/7fda984b-90a7-47fa-a187-3f779e94dffe)

2. Install Mysql Server software

Mysql server software was installed on the "Myql Server" EC2 instance ash shown in the picture below 

![mysql server intsalled on Server instance](https://github.com/oghare01/Client-Architecture-with-RDMS-project/assets/141191975/d16ead91-45b4-408b-8bd4-73c3ca3fc1cf)

3. Install Mysql Client

On the Mysql client EC2 instance, Mysql client software was installed. This is shown in the following diagram 

![mysql server intsalled on Client instance](https://github.com/oghare01/Client-Architecture-with-RDMS-project/assets/141191975/bd9b35b4-e650-4796-9794-b9a91c7083ea)

4. Enable connection to the server instance
   
On the Mysql Server instance, the security inbound rule allowing traffic from the Mysql Client server was created. This was done by inputing the private IP address of the Client server in the Mysql traffic type

![inbound rules modification](https://github.com/oghare01/Client-Architecture-with-RDMS-project/assets/141191975/fce07f8e-4dd1-4207-b561-06705182b8dd)

5. Furthermore, to enable connect to Mysql server, the configuration file was modified by changing the bind ip address to 0.0.0.0
This step is shown below

![bind address modifies on server side](https://github.com/oghare01/Client-Architecture-with-RDMS-project/assets/141191975/f70b8bec-3d33-47dd-821a-25cb19976f9d)

6. Finally, the Mysql client was connected to Mysql Server and tested. The result obtained showed that the process worked just fine

![sql server conected and working!](https://github.com/oghare01/Client-Architecture-with-RDMS-project/assets/141191975/f0930c5f-1abb-4ac9-bbd8-6ba640a5658e)
