# Client-Architecture-with-RDMS-project

1. Creation and configuration of 2 Linux instances

First, two Linux instance; "Mysql Client" and "Mysql Server" were created on AWS 

![EC2 instances](https://github.com/oghare01/Client-Architecture-with-RDMS-project/assets/141191975/7fda984b-90a7-47fa-a187-3f779e94dffe)

On the Mysql Server instance, the security inbound rule allowing traffic from the Mysql Client server was created. This was done by inputing the private IP address of the Client server in the Mysql traffic setting

![inbound rules modification](https://github.com/oghare01/Client-Architecture-with-RDMS-project/assets/141191975/fce07f8e-4dd1-4207-b561-06705182b8dd)

