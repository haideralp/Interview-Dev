What is Development (Dev) Environment (env) ?

A development environment is a practically workspace for developers to make changes without breaking anything in a live environment. It is the go to place for developers as they deploy changes.
### Benefits of Development environment:
1. Increased colloboration between teams with share responsibilities
2. Improved productivity due to automation of tasks
3. More efficient and streamlines process for developers saving time as they can stay update 4. with latest practices and threats.
4. Provides a creater sense of transpareny on the project so keeping workflow easy to use.

5.   What is  Virtualisation and What are the layers of virtualisation ?

Virtualisation means the practice use to generate a simulated environment as opposed to physical one. It often includes computer-generated versions of hardware, operating systems, storage devices and more. You can then parition single computer or server into several virtual machines. Each virtual machine can then interact independently and run different operating systems or applications while sharing the resources of a single host machine.

By creating multiple resources from a single computer or server, virtualisation improves scalability and workloads while resulting in the use of fewer overall servers, less energy consumption, and less infrastructure costs and maintenance.

1.  What are the layers of Virtualisation ?
    -
2.  What is VPC ?
    - this is virtual enviroment created 

3.  How did you make your app highly scalable and available ?
  Sparta example: Node App
    - HS was achieved by setting autoscales groups for the app. Used average CPU utilisaton of 40% as a metric to spin up more 
     instances. Target tracking policy was implemented. 
   
    - HA was achieved by spinning more VMs in case of shutting VMs or any unhealhy. 

4.  How did you secure your app ?

    - Security app was maintained in the following ways
      
      - Load balancer - added specific rules to listen to certain ports / Security group utilised. 
      - Databases - DBs instances were made private subnet for EC2 instacnes so were not internet facing


3 layer of security

IAM rolde -access and identity user (permission and secret keys) - least prieveldged access on need to know basis. 
NACL (network access control list)
subnet level 
VPC - is an isolated space.
Create groups (adds permision to that group attached accounts)

what is nacl and security group ?

nacl on subnet level
secruity works on instance level. 


Accident Damage Prevention:

s3 - enable versioning to prevent accidental damage
ec2 - setting on enable non deletion option so anyone tries will need to disable this.

mfa - on an account able -send code 

tech
what is is.
benefits
and have a example ready.