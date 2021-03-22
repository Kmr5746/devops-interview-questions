# DevOps Interview Questions

:information_source: &nbsp;This repository contains interview questions on various DevOps and SRE related topics

:bar_chart: &nbsp;There are currently **503** questions

:books: &nbsp;To learn more about DevOps check the resources in [devops-resources](https://github.com/bregman-arie/devops-resources)

:thought_balloon: &nbsp;Different interviewers focus on different things. Some will focus on your resume while others might focus on scenario questions or specific technical questions. I tried to cover different types of questions for you to practice and test your skills

:pencil: &nbsp;You can add more questions & answers by submitting pull requests :) You can read more about it [here](CONTRIBUTING.md)

:cn: &nbsp;You can find a [中文](README-zh_CN.md) Chinese translation right [here](README-zh_CN.md)

****

<!-- ALL-TOPICS-LIST:START -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<center>
<table>
  <tr>
    <td align="center"><a href="#devops"><img src="images/devops.png" width="70px;" height="75px;" alt="DevOps" /><br /><b>DevOps</b></a><br /><sub><a href="#devops-beginner">Beginner :baby:</a></sub><br><sub><a href="#devops-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#jenkins"><img src="images/jenkins.png" width="80px;" height="85px;" alt="Jenkins"/><br /><b>Jenkins</b></a><br /><sub><a href="#jenkins-beginner">Beginner :baby:</a></sub><br><sub><a href="#jenkins-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#git"><img src="images/git.png" width="110px;" height="75px;" alt="Git"/><br /><b>Git</b></a><br /><sub><a href="#git-beginner">Beginner :baby:</a></sub><br><sub><a href="#git-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#ansible"><img src="images/ansible.png" width="65px;" height="75px;" alt="Ansible"/><br /><b>Ansible</b></a><br /><sub><a href="#ansible-beginner">Beginner :baby:</a></sub><br><sub><a href="#ansible-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#Network"><img src="images/network.png" width="80x;" height="75px;" alt="Network"/><br /><b>Network</b></a><br /><sub><a href="#network-beginner">Beginner :baby:</a></sub><br><sub><a href="#network-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#linux"><img src="images/linux.png" width="75x;" height="75px;" alt="Linux"/><br /><b>Linux</b></a><br /><sub><a href="#linux-beginner">Beginner :baby:</a></sub><br><sub><a href="#linux-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#terraform"><img src="images/terraform.png" width="75px;" height="75px;" alt="Terraform"/><br /><b>Terraform</b></a><br /><sub><a href="#terraform-beginner">Beginner :baby:</a></sub><br><sub><a href="#terraform-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#docker"><img src="images/docker.png" width="75px;" height="75px;" alt="Docker"/><br /><b>Docker</b></a><br /><sub><a href="#docker-beginner">Beginner :baby:</a></sub><br><sub><a href="#docker-advanced">Advanced :star:</a></sub></td>
  </tr>
  <tr>
    <td align="center"><a href="#coding"><img src="images/coding.png" width="75px;" height="75px;" alt="coding"/><br /><b>Coding</b></a><br /><sub><a href="#coding-beginner">Beginner :baby:</a></sub><br><sub><a href="#coding-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#python"><img src="images/python.png" width="80px;" height="75px;" alt="Python"/><br /><b>Python</b></a><br /><sub><a href="#python-beginner">Beginner :baby:</a></sub><br><sub><a href="#python-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#go"><img src="images/go.png" width="80px;" height="75px;" alt="Go"/><br /><b>Go</b></a><br /><sub><a href="#go-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#shell-scripting"><img src="images/bash.png" width="70px;" height="75px;" alt="Bash"/><br /><b>Shell Scripting</b></a><br /><sub><a href="#shell-scripting-beginner">Beginner :baby:</a></sub><br><sub><a href="#shell-scripting-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#kubernetes"><img src="images/kubernetes.png" width="75px;" height="75px;" alt="kubernetes"/><br /><b>Kubernetes</b></a><br /><sub><a href="#kubernetes-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#prometheus"><img src="images/prometheus.png" width="75px;" height="75px;" alt="Prometheus"/><br /><b>Prometheus</b></a><br /><sub><a href="#prometheus-beginner">Beginner :baby:</a></sub><br><sub><a href="#prometheus-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#mongo"><img src="images/mongo.png" width="75px;" height="75px;" alt="Mongo"/><br /><b>Mongo</b></a><br /><sub><a href="#mongo-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#sql"><img src="images/sql.png" width="75px;" height="75px;" alt="sql"/><br /><b>SQL</b></a><br /><sub><a href="#sql-beginner">Beginner :baby:</a></sub><br><sub><a href="#sql-advanced">Advanced :star:</a></sub></td>
  </tr>
  <tr>
    <td align="center"><a href="#cloud"><img src="images/cloud.png" width="110px;" height="75px;" alt="Cloud"/><br /><b>Cloud</b></a><br /><sub><a href="#cloud-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#aws"><img src="images/aws.png" width="110px;" height="75px;" alt="AWS"/><br /><b>AWS</b></a><br /><sub><a href="#aws-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#azure"><img src="images/azure.png" width="80px;" height="75px;" alt="azure"/><br /><b>Azure</b></a><br /><sub><a href="#azure-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#gcp"><img src="images/gcp.png" width="75px;" height="75px;" alt="gcp"/><br /><b>Google Cloud Platform</b></a><br /><sub><a href="#gcp-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#openstack"><img src="images/openstack.png" width="75px;" height="75px;" alt="openstack"/><br /><b>OpenStack</b></a><br /><sub><a href="#openstack-beginner">Beginner :baby:</a></sub><br><sub><a href="#openstack-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#security"><img src="images/security.png" width="75px;" height="75px;" alt="security"/><br /><b>Security</b></a><br /><sub><a href="#security-beginner">Beginner :baby:</a></sub><br><sub><a href="#security-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#puppet"><img src="images/puppet.png" width="75px;" height="75px;" alt="puppet"/><br /><b>Puppet</b></a><br /><sub><a href="#puppet-beginner">Beginner :baby:</a></sub><br><sub><a href="#puppet-advanced">Advanced :star:</a></sub></td>
    <td align="center"><a href="#openshift"><img src="images/openshift.png" width="75px;" height="75px;" alt="OpenShift"/><br /><b>OpenShift</b></a><br /><sub><a href="#openshift-beginner">Beginner :baby:</a></sub><br><sub></td>
  </tr>
  <tr>
    <td align="center"><a href="#monitoring"><img src="images/monitoring.png" width="75px;" height="75px;" alt="Monitoring"/><br /><b>Monitoring</b></a><br /><sub><a href="#monitoring-beginner">Beginner :baby:</a></sub><br><sub></td>
    <td align="center"><a href="#general"><img src="images/general.png" width="110px;" height="75px;" alt="General"/><br /><b>General</b></a></td>
    <td align="center"><a href="#scenarios"><img src="images/scenarios.png" width="110px;" height="75px;" alt="Scenarios"/><br /><b>Scenarios</b></a></td>
  </tr>
</table>
</center>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-TOPICS-LIST:END -->

##devops

<a name="devops-beginner"></a>
#### :baby: Beginner

<details>
<summary> Q)Tell me about your self?</summary><br><b>
Hi this is xxxxx I am having around 7 years of experience on technologies like linux and aws cloud computing.

I have around 3 years of exp in AWS and linux 

In cloud computing worked on services like ec2,s3 vpc, CloudWatch and  cloud formation, ansible, patching activities as a day to day activities, any tickets which comes to my service now bin and request for new Infrastructure server building and new software deployment. If we face any server issues like connecting issues or ping issues I will work on that to resolve and close tickets within the time frame based on SLA we will try to resolve, basically in our projects we work 24*7 on shift basis.
my day start with taking the shift hand over from previous shift members, understanding pending tickets and working on them, if any build request comes responding to them, in general we get service request and we try to complete them and submit to client and we attend everyday daily team calls with our team and also with client meetings based on requirement.
</b></details>

<details>
<summary>What is DevOps?</summary><br><b>

There are many good answers to this question. I like Amazon's description of DevOps:

"DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes. This speed enables organizations to better serve their customers and compete more effectively in the market."

You can find more details here: https://aws.amazon.com/devops/what-is-devops
</b></details>

<details>
<summary>What are the benefits of DevOps? What it can help us to achieve?</summary><br><b>

You should mention some or all of the following:

  * Collaboration
  * Improved delivery
  * Security
  * Speed
  * Scale
  * Reliability

Detailed answer can be found here: https://aws.amazon.com/devops/what-is-devops 
</b></details>

<details>
<summary>What are the anti-patterns of DevOps?</summary><br><b>
</b></details>

<details>
<summary>What is Continuous Integration?</summary><br><b>

A development practice where developers integrate code into a shared repository frequently. It can range from a couple of changes every day or a week to a couple of changes in one hour in larger scales.

Each piece of code (change/patch) is verified, to make the change is safe to merge. Today, it's a common practice to test the change using an automated build that makes sure the code can integrated. It can be one build which runs several tests in different levels (unit, functional, etc.) or several separate builds that all or some has to pass in order for the change to be merged into the repository.
</b></details>

<details>
<summary>What is Continuous Deployment?</summary><br><b>
</b></details>

<details>
<summary>What is Continuous Delivery?</summary><br><b>
</b></details>

<details>
<summary>What CI/CD best practices are you familiar with? Or what do you consider as CI/CD best practice?</summary><br><b>
</b></details>

<details>
<summary>What systems and/or tools are you using for the following?:

  * CI/CD
  * Provisioning infrastructure
  * Configuration Management
  * Monitoring & alerting - Prometheus, DataDog, Sensu, Grafana
  * Logging - ELK (Elastic Search, Logstash, Kibana), EFK (Elastic Search, Fluentd, Kibana)
  * Code review
  * Code coverage
  * Tests</summary><br><b>
  * CI/CD - Jenkins, Circle CI, Travis
  * Provisioning infrastructure - Terraform, CloudFormation
  * Configuration Management - Ansible, Puppet, Chef
  * Monitoring & alerting - Prometheus, Nagios
  * Logging - Logstash, Graylog, Fluentd
  * Code review - Gerrit, Review Board
  * Code coverage - Cobertura, Clover, JaCoCo
  * Tests - Robot, Serenity, Gauge
</b></details>

<details>
<summary>What are you taking into consideration when choosing a tool/technology?</summary><br><b>

In your answer you can mention one or more of the following:
  * mature vs. cutting edge
  * community size
  * architecture aspects - agent vs. agentless, master vs. masterless, etc.
</b></details>

<details>
<summary>Explain mutable vs. immutable infrastructure</summary><br><b>

In mutable infrastructure paradigm, changes applied on top of the existing infrastructure and over time
the infrastructure builds up a history of changes. Ansible, Puppet and Chef are examples to tools which
follow mutable infrastructure paradigm.

In immutable infrastructure paradigm, every change is actually new infrastructure. So a change
to a server will result in a new server instead of updating it. Terraform is an example of technology
which follows the immutable infrastructure paradigm.
</b></details>

<details>
<summary>What ways are you familiar with to deliver a software? What are the advantages and disadvantages of each method?</summary><br><b>

  * Archive - collect all your app files into one archive (e.g. tar) and deliver it to the user.
  * Package - depends on the OS, you can use your OS package format (e.g. in RHEL/Fefodra it's RPM) to deliver your software with a way to install, uninstall and update it using the standard packager commands
  * Images - Either VM or container images where your package is included with everything it needs in order to run successfully.
</b></details>

<details>
<summary>What is caching? How it works? Why is it important?</summary><br><b>
</b></details>

<details>
<summary>Explain stateless vs. stateful</summary><br><b>

Stateless applications don't store any data in the host which makes it ideal for horizontal scaling and microservices.
Stateful applications depend on the storage to save state and data, typically databases are stateful applications.
</b></details>

<details>
<summary>What is HTTP and how it works?</summary><br><b>
</b></details>

<details>
<summary>Describe the workflow of setting up some type of web server (Apache, IIS, Tomact, ...)</summary><br><b>
</b></details>

<details>
<summary>Explain "Open Source"</summary><br><b>
</b></details>

##### SRE

<details>
<summary>Compare SRE to DevOps</summary><br><b>
</b></details>

<details>
<summary>What SRE team is responsible for?</summary><br><b>

One can argue whether it's per company definition or a global one but at least according to a large companies, like Google for example, the SRE team is responsible for availability, latency, performance, efficiency, change management, monitoring, emergency response, and capacity planning of their services
</b></details>

<details>
<summary>What is an error budget?</summary><br><b>
</b></details>

<details>
<summary>What are MTTF (mean time to failure) and MTTR (mean time to repair)? What these metrics help us to evaluate?</summary><br><b>
</b></details>

<details>
<summary>What is a post-mortem meeting? Why is it important?</summary><br><b>
</b></details>

<details>
<summary>What is "infrastructure as code"? What implementation of IAC are you familiar with?</summary><br><b>
</b></details>


<a name="devops-advanced"></a>
#### :star: Advanced

<details>
<summary>Tell me how you perform plan capacity for your CI/CD resources (e.g. servers, storage, etc.)</summary><br><b>
</b></details>

<details>
<summary>How would you structure/implement CD for an application which depends on several other applications?</summary><br><b>
</b></details>

<details>
<summary>How do you measure your CI/CD quality? Are there any metrics you are using for measuring the quality?</summary><br><b>
</b></details>

<details>
<summary>What is a configuration drift? What problems is it causing?</summary><br><b>

Configuration drift happens when in an environment of servers with the exact same configuration and software, a certain server
or servers are being applied with updates or configuration which other servers don't get and over time these servers become
slightly different than all others.

This situation might lead to bugs which hard to identify and reproduce.
</b></details>

<details>
<summary>How to deal with a configuration drift?</summary><br><b>
</b></details>

<details>
<summary>Do you have experience with testing cross-projects changes? (aka cross-dependency)</summary><br><b>

Note: cross-dependency is when you have two or more changes to separate projects and you would like to test them in mutual build instead of testing each change separately.
</b></details>

<details>
<summary>Have you contributed to an open source project? Tell me about this experience</summary><br><b>
</b></details>

<details>
<summary>When you publish a project, you usually publish it with a license. What types of licenses are you familiar with and which one do you prefer to use?</summary><br><b>
</b></details>

## Jenkins

<a name="jenkins-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Jenkins? What have you used it for?</summary><br><b>
</b></details>

<details>
<summary>What are the advantages of Jenkins over its competitors? Can you compare it to one of the following systems?

  * Travis
  * Bamboo
  * Teamcity
  * CircleCI</summary><br><b>
</b></details>

<details>
<summary>Explain the following:

  * Job
  * Build
  * Plugin
  * Slave
  * Executor</summary><br><b>
</b></details>

<details>
<summary>What plugins have you used in Jenkins?</summary><br><b>
</b></details>

<details>
<summary>Explain CI/CD and how you implemented it in Jenkins</summary><br><b>
</b></details>

<details>
<summary>What type of jobs are there? Which types have you used?</summary><br><b>
</b></details>

<details>
<summary>How did you report build results to users? What ways are you familiar with for reporting results?</summary><br><b>
</b></details>

<details>
<summary>You need to run unit tests every time a change submitted to a given project. Describe in details how your pipeline would look like and what will be executed in each stage</summary><br><b>
</b></details>

<details>
<summary>How to secure Jenkins?</summary><br><b>
</b></details>

<details>
<summary>Can you describe some of Jenkins best practices?</summary><br><b>
</b></details>

<a name="jenkins-advanced"></a>
#### :star: Advanced

<details>
<summary>How to acquire multiple slaves for one specific build?</summary><br><b>
</b></details>

<details>
<summary>There are four teams in your organization. How to prioritize the builds of each team? So the jobs of team x will always run before team y for example</summary><br><b>
</b></details>

<details>
<summary>If you are managing a dozen of jobs, you can probably use the Jenkins UI. How do you manage the creation and deletion of hundreds of jobs every week/month?</summary><br><b>
</b></details>

<details>
<summary>What are some of Jenkins limitations?</summary><br><b>

  * Testing cross-dependencies (changes from multiple projects together)
  * Starting builds from any stage (although cloudbees implemented something called checkpoints)
</b></details>

<details>
<summary>How would you implement an option of a starting a build from a certain stage and not from the beginning?<summary><br><b>
</b></details>

##### Jenkins Dev

<details>
<summary>Do you have experience with developing a Jenkins plugin? Can you describe this experience?</summary><br><b>
</b></details>

<details>
<summary>Have you written Jenkins scripts? If yes, what for and how they work?</summary><br><b>
</b></details>

## Cloud 

<a name="cloud-beginner"></a>
#### :baby: Beginner

<details>
<summary>What are the advantages of cloud computing? Mention at least 3 advantages</summary><br><b>
</b></details>

<details>
<summary>What types of Cloud Computing are there?</summary><br><b>

IAAS
PAAS
SAAS
</b></details>

<details>
<summary>Explain each of the following Cloud Computing Deployments:

  * Public
  * Hybrid
  * Private</summary><br><b>
</b></details>


## AWS

<a name="aws-beginner"></a>
#### :baby: Beginner

##### Global Infrastructure

<details>
<summary>Explain the following

  * Availability zone
  * Region
  * Edge location</summary><br><b>
AWS regions are data centers hosted across different geographical locations worldwide, each region is completely independent of one another. 
Within each region,There are multiple isolated locations known as Availability Zones. Multiple availability zones insure high availability in case one of them goes down.

Edge locations are basically content delivery network which caches data and insures lower latency and faster delivery to the users in any location. They are located in major cities in the world.
</b></details>

<details>
<summary>What is IAM?</summary><br><b>
</b></details>

##### S3
 
<details>
<summary>Explain what is S3 and what is it used for</summary><br>
<b>
S3 stands for 3 S, Simple Storage Service.
S3 is a object storage service which is fast, scalable and durable. S3 enables customers to upload, download or store any file or object that is up to 5 TB in size. While having a maximum size of 5 GB per file (multipart upload if more than 5 GB in size).
</b>
</details>

<details>
<summary>What is a bucket?</summary><br><b>
An S3 bucket is a resource which is similar to folders in a file system and allows storing objects, which consist of data and its  meta data.
</b></details>

<details>
<summary>True or False? A bucket name must be globally unique</summary><br><b>
True
</b></details>

<details>
<summary>What objects in S3 consists of?
  * Another way to ask it: explain key, value, version id and meta data in context of objects</summary><br><b>
</b></details>

<details>
<summary>Explain data consistency</summary><br><b>
</b></details>

<details>
<summary>Can you host dynamic websites on S3?. What about static websites?</summary><br><b>
</b></details>

<details>
<summary>What security measures have you taken in context of S3?</summary><br><b>
</b></details>

<details>
<summary>What is a storage class? What storage classes are you familiar with?</summary><br><b>
</b></details>

##### EC2

<details>
<summary>What is EC2? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>What EC2 pricing models are there?</summary><br><b>
</b></details>

<details>
<summary>How to increase RAM for a given EC2 instance?</summary><br><b>

Stop the instance, the type of the instance to match the desired RAM and start the instance.
</b></details>

<details>
<summary>What is an AMI?</summary><br><b>
</b></details>

<details>
<summary>How many storage options are there for EC2 Instances?</summary><br><b>
</b></details>

<details>
<summary>What happens when an EC2 instance is stopped or terminated?</summary><br><b>
</b></details>

<details>
<summary>What are Security Groups?</summary><br><b>
</b></details>

<details>
<summary>How to migrate an instance to another availability zone?</summary><br><b>
</b></details>

<details>
<summary>What are spot instances?</summary><br><b>
</b></details>

##### CloudFront

<details>
<summary>Explain what is CloudFront and what is it used for</summary><br><b>
</b></details>

<details>
<summary>Explain the following
  * Origin
  * Edge location
  * Distribution</summary><br><b>
</b></details>

<details>
<summary>What delivery methods available for the user with CDN?</summary><br><b>
</b></details>

<details>
<summary>True or False?. Objects are cached for the life of TTL</summary><br><b>
</b></details>

##### Load Balancers

<details>
<summary>What types of load balancers are supported in EC2 and what are they used for?</summary><br><b>

  * Application LB - layer 7 traffic
  * Network LB - ultra-high performances or static IP address
  * Classic LB - low costs, good for test or dev environments
</b></details>

#### Databases

<details>
<summary>What is RDS?</summary><br><b>
</b></details>

<details>
<summary>What are some features or benefits of using RDS?</summary><br><b>

1. Multi AZ - great for Disaster Recovery
2. Read Replicas - for better performances
</b></details>

<details>
<summary>What is EBS?</summary><br><b>
</b></details>

<details>
<summary>What is VPC?</summary><br><b>
</b></details>

## Network

<a name="network-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Ethernet?</summary><br><b>
</b></details>

<details>
<summary>What is a MAC address? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>When this MAC address is used?: ff:ff:ff:ff:ff:ff</summary><br><b>
</b></details>

<details>
<summary>What is an IP address?</summary><br><b>
</b></details>

<details>
<summary>Explain subnet mask and given an example</summary><br><b>
</b></details>

<details>
<summary>What is a private IP address? What do we need it for?</summary><br><b>
</b></details>

<details>
<summary>Explain the OSI model. What layers there are? What each layer is responsible for?</summary><br><b>

Application: user end (HTTP is here)
Presentation: establishes context between application-layer entities (Encryption is here)
Session: establishes, manages and terminates the connections
Transport: transfers variable-length data sequences from a source to a destination host (TCP & UDP are here)
Network: transfers datagrams from one network to another (IP is here)
Data link: provides a link between two directly connected nodes (MAC is here)
Physical: the electrical and physical spec the data connection (Bits are here)
</b></details>

<details>
<summary>For each of the following determine to which OSI layer it belongs:

  * Error correction
  * Packets routing
  * Cables and electrical signals
  * MAC address
  * IP address
  * Sessions between applications
  * 3 way handshake</summary><br><b>
</b></details>

<details>
<summary>What delivery schemes are you familiar with?</summary><br><b>

Unitcast: One to one communication where there is one sender and one receiver.

Broadcast: Sending a message to everyone in the network. The address ff:ff:ff:ff:ff:ff is used for broadcasting.
           Two common protocols which use broadcast are ARP and DHCP.

Multicast: Sending a message to a group of subscribers. It can be one-to-many or many-to-many.
</b></details>

<details>
<summary>What is CSMA/CD? Is it used in modern ethernet networks?</summary><br><b>

CSMA/CD stands for Carrier Sense Multiple Access / Collision Detection.
Its primarily focus it to manage access to shared medium/bus where only one host can transmit at a given point of time.

CSMA/CD algorithm:

1. Before sending a frame, it checks whether another host already transmitting a frame.
2. If no one transmitting, it starts transmitting the frame.
3. If two hosts transmitted at the same time, we have a collision.
4. Both hosts stop sending the frame and they send to everyone a 'jam signal' notifying everyone that a collision occurred
5. They are waiting for a random time before sending again
6. Once each host waited for a random time, they try to send the frame again and so the
</b></details>

<details>
<summary>Describe the following network devices and the difference between them:

  * router
  * switch
  * hub</summary><br><b>
</b></details>

<details>
<summary>What is NAT?</summary><br><b>
</b></details>

<details>
<summary>What is a proxy? How it works? What do we need it for?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between TCP and UDP?</summary><br><b>
	
TCP establishes a connection between the client and the server to guarantee the order of the packages, on the other hand, UDP does not establish a connection between client and server and doesn't handle package order. This makes UDP more lightweight than TCP and a perfect candidate for streaming services.
</b></details>

<details>
<summary>Explain "default gateway"</summary><br><b>
</b></details>

<details>
<summary>How TCP works? What is the 3 way handshake?</summary><br><b>
</b></details>

<details>
<summary>What is ARP? How it works?</summary><br><b>
</b></details>

<details>
<summary>What is TTL?</summary><br><b>
</b></details>

<details>
<summary>What is DHCP? How it works?</summary><br><b>
</b></details>

<details>
<summary>What is SSL tunneling? How it works?</summary><br><b>
</b></details>

<details>
<summary>What is a socket? Where can you see the list of sockets in your system?</summary><br><b>
</b></details>

<details>
<summary>What is IPv6? Why should we consider using it if we have IPv4?</summary><br><b>
</b></details>

<details>
<summary>What is VLAN?</summary><br><b>
</b></details>

<details>
<summary>What is MTU?</summary><br><b>
</b></details>

<details>
<summary>True or False?. Ping is using UDP because it doesn't care about reliable connection</summary><br><b>
</b></details>

<details>
<summary>What is SDN?</summary><br><b>
</b></details>

<details>
<summary>What is ICMP? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>What is NAT? How it works?</summary><br><b>
</b></details>

<a name="network-advanced"></a>
#### :star: Advanced

<details>
<summary>Explain Spanning Tree Protocol (STP)</summary><br><b>
</b></details>

<details>
<summary>What is link aggregation? Why is it used?</summary><br><b>
</b></details>

<details>
<summary>What is Asymmetric Routing? How do deal with it?</summary><br><b>
</b></details>

<details>
<summary>What overlay (tunnel) protocols are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>What is GRE? How it works?</summary><br><b>
</b></details>

<details>
<summary>What is VXLAN? How it works?</summary><br><b>
</b></details>

<details>
<summary>What is SNAT?</summary><br><b>
</b></details>

<details>
<summary>Explain OSPF</summary><br><b>
</b></details>

<details>
<summary>Explain Spine & Leaf</summary><br><b>
</b></details>

<details>
<summary>Using Hamming code, what would be the code word for the following data word 100111010001101?</summary><br><b>

00110011110100011101
</b></details>

## Linux

<a name="linux-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is your experience with Linux? When you can set up an application on multiple operating systems, on which one would you prefer to set it up and why?</summary><br><b>
</b></details>

<details>
<summary>Explain what each of the following commands does and give an example on how to use it:

  * ls
  * rm 
  * rmdir (can you achieve the same result by using <code>rm</code>?)
  * grep
  * wc
  * curl
  * touch
  * man
  * nslookup or dig
  * df</summary><br><b>
</b></details>

<details>
<summary>Running the command <code>df</code> you get "command not found". What could be wrong and how to fix it?</summary><br><b>
</b></details>

<details>
<summary>How to make sure a service will start on a OS of your choice?</summary><br><b>
</b></details>

<details>
<summary>How do you schedule tasks periodically?</summary><br><b>

You can use the commands <code>cron</code> and <code>at</code>.
With cron, tasks are scheduled using the following format:

<minute> <hour> <day of month> <month> <day of week> <command to execute>

The tasks are stored in a cron file.
</b></details>

<details>
<summary>Have you scheduled tasks in the past? What kind of tasks?</summary><br><b>

Normally you will schedule batch jobs.

</b></details>

##### Permissions

<details>
<summary>How to change the permissions of a file?</summary><br><b>

Using the `chmod` command.

</b></details>

<details>
<summary>What does the following permissions mean?:

  * 777
  * 644
  * 750</summary><br><b>

777 - means you are lazy
644 - owner has read+write permissions and everyone else can only read
750 - owner can do anything, group can read and execute and others can do nothing
</b></details>

<details>
<summary>Explain what is setgid, setuid and sticky bit</summary><br><b>
</b></details>

<details>
<summary>You try to delete a file but it fails. Name at least three different reason as to why it could happen</summary><br><b>
</b></details>

<details>
<summary>What is systemd?</summary><br><b>
</b></details>

<details>
<summary>On a system which uses systemd, how would display the logs?</summary>

<code>journalctl</code>
</b></details>

##### Debugging

<details>
<summary>What are you using for troubleshooting and debugging <b>network</b> issues?</summary><br><b>

<code>dstat -t</code> is great for identifying network and disk issues.
<code>netstat -tnlaup</code> can be used to see which processes are running on which ports.
<code>lsof -i -P</code> can be used for the same purpose as netstat.
<code>ngrep -d any metafilter</code> for matching regex against payloads of packets.
<code>tcpdump</code> for capturing packets
<code>wireshark</code> same concept as tcpdump but with GUI (optional).
</b></details>

<details>
<summary>What are you using for troubleshooting and debugging <b>disk & file system</b> issues?</summary><br><b>

<code>dstat -t</code> is great for identifying network and disk issues.
<code>opensnoop</code> can be used to see which files are being opened on the system (in real time).
</b></details>

<details>
<summary>What are you using for troubleshooting and debugging <b>process</b> issues?</summary><br><b>

<code>strace</code> is great for understanding what your program does. It prints every system call your program executed.
</b></details>

<details>
<summary>What are you using for debugging CPU related issues?</summary><br><b>

<code>top</code> will show you how much CPU percentage each process consumes
<code>perf</code> is a great choice for sampling profiler and in general, figuring out what your CPU cycles are "wasted" on
<code>flamegraphs</code> is great for CPU consumption visualization (http://www.brendangregg.com/flamegraphs.html)
</b></details>

<details>
<summary>You get a call saying "my system is slow" - how would you deal with it?</summary><br><b>

1. Check with <code>top</code> if anything consumes your CPU or RAM.
2. Run <code>dstat -t</code> to check if it's related to disk or network.
3. Check I/O stats with <code>iostat</code>
</b></details>

<details>
<summary>How to debug binaries?</summary><br><b>
</b></details>

<details>
<summary>What is a Linux kernel module and how do you load a new module?</summary><br><b>
</b></details>

<details>
<summary>What is KVM?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between SSH and SSL?</summary><br><b>
</b></details>

<details>
<summary>What is SSH port forwarding?</summary><br><b>
</b></details>

<details>
<summary>Explain redirection</summary><br><b>
</b></details>

<details>
<summary>What are wildcards? Can you give an example of how to use them?</summary><br><b>
</b></details>

<details>
<summary>What do we grep for in each of the following commands?:

  * <code>grep '[0-9]\{1,3\}\.[0-9]\{1,3\}\.[0-9]\{1,3\}\.[0-9]\{1,3\}' some_file</code>
  * <code>grep -E "error|failure" some_file</code>
  * <code>grep '[0-9]$' some_file</code>
</summary><br><b>

1. An IP address
2. The word "error" or "failure"
3. Lines which end with a number
</b></details>

<details>
<summary>Tell me everything you know about Linux boot process</summary><br><b>
</b></details>

<details>
<summary>What is an exit code? What exit codes are you familiar with?</summary><br><b>

An exit code (or return code) represents the code returned by a child process to its
parent process.

0 is an exit code which represents success while anything higher than 1 represents error.
Each number has different meaning, based on how the application was developed.

I consider this as a good blog post to read more about it: https://shapeshed.com/unix-exit-codes
</b></details>

<details>
<summary>What is the difference between a soft link and hard link?</summary><br><b>

Hard link is the same file, using the same inode.
Soft link is a shortcut to another file, using a different inode.

Soft links can be created between different file systems while.
Hard link can be created only within the same file system.
</b></details>

<details>
<summary>What happens when you delete the original file in case of soft link and hard link?</summary><br><b>
</b></details>

<details>
<summary>What is a swap partition? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>You are trying to create a new file but you get "File system is full". You check with df for free space and you see you used only 20% of the space. What could be the problem?</summary><br><b>
</b></details>

<details>
<summary>What do you know about LVM?</summary><br><b>
</b></details>

<details>
<summary>Explain the following in regards to LVM:

  * PV
  * VG
  * LV</summary><br><b>
</b></details>

<details>
<summary>What is NFS? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>What RAID is used for? Can you explain the differences between RAID 0, 1, 5 and 10?</summary><br><b>
</b></details>

<details>
<summary>What is lazy umount?</summary><br><b>
</b></details>

<details>
<summary>Fix the following commands:

  * sed "s/1/2/g' /tmp/myFile
  * find . -iname \*.yaml -exec sed -i "s/1/2/g" {} ;</summary><br><b>
</b></details>

<details>
<summary>Explain what is stored in each of the following paths and if there is anything unique about it:</summary><br><b>

  * /tmp
  * /var/log
  * /bin
  * /proc
  * /usr/local
</b></details>

<details>
<summary>What is chroot?</summary><br><b>
</b></details>

##### Processes

<details>
<summary>How to run a process in the background and why to do that in the first place?</summary><br><b>

You can achieve that by specifying & at end of the command.
As to why, since some commands/processes can take a lot of time to finish
execution or run forever
</b></details>

<details>
<summary>How can you find how much memory a specific process consumes?</summary><br><b>
</b></details>

<details>
<summary>What signal is used when you run 'kill <process id>'?</summary><br><b>

The default signal is SIGTERM (15). This signal kills
process gracefully which means it allows it to save current
state configuration.
</b></details>

<details>
<summary>What signals are you familiar with?</summary><br><b>

SIGTERM - default signal for terminating a process
SIGHUP - common usage is for reloading configuration
SIGKILL - a signal which cannot caught or ignored

To view all available signals run `kill -l`
</b></details>

<details>
<summary>What is a trap?</summary><br><b>
</b></details>

<details>
<summary>What happens when you press ctrl + c?</summary><br><b>
</b></details>

<details>
<summary>What are daemons?</summary><br><b>
</b></details>

<details>
<summary>What are the possible states of a process in Linux?</summary><br><b>

Running
Waiting
Stopped
Terminated
Zombie
</b></details>

<details>
<summary>What is a zombie process? How do you get rid of it?</summary>
</b></details>

<details>
<summary>What is the init process?</summary><br><b>
</b></details>

<details>
<summary>How to change the priority of a process? Why would you want to do that?</summary><br><b>
</b></details>

<details>
<summary>Can you explain how network process/connection is established and how it's terminated?><br></b>
</b></details>

<details>
<summary>What are system calls? What system calls are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>What <code>strace</code> does?</summary><br><b>
</b></details>

<details>
<summary>Find all the files which end with '.yml' and replace the number 1 in 2 in each file</summary><br><b>

ind /some_dir -iname \*.yml -print0 | xargs -0 -r sed -i "s/1/2/g"
</b></details>

<details>
<summary>How to check how much free memory a system has? How to check memory consumption by each process?</summary><br><b>

You can use the commands <code>top</code> and <code>free</code>
</b></details>

<details>
<summary>How would you split a 50 lines file into 2 files of 25 lines each?</summary><br><b>

You can use the <code>split</code> command this way: <code>split -l 25 some_file</code>
</b></details>

<details>
<summary>What is a file descriptor? What file descriptors are you familiar with?</summary><br><b>
Kerberos
File descriptor, also known as file handler, is a unique number which identifies an open file in the operating system.

In Linux (and Unix) the first three file descriptors are:
  * 0 - the default data stream for input
  * 1 - the default data stream for output
  * 2 - the default data stream for output related to errors

This is a great article on the topic: https://www.computerhope.com/jargon/f/file-descriptor.htm
</b></details>

<details>
<summary>What's an inode?</summary><br><b>

For each file (and directory) in Linux there is an inode, a data structure which stores meta data
related to the file like its size, owner, permissions, etc.
</b></details>

<details>
<summary>How to list active connections?</summary><br><b>
</b></details>

<details>
<summary>What is NTP? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>Explain Kernel OOM</summary><br><b>
</b></details>

<details>
<summary>What is SELiunx?</summary><br><b>
</b></details>

<details>
<summary>What is Kerberos?</summary><br><b>
</b></details>

<details>
<summary>What is nftables?</summary><br><b>
</b></details>

<details>
<summary>What firewalld daemon is responsible for?</summary><br><b>
</b></details>

##### Network

<details>
<summary>What is a network namespace? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>How can you turn your Linux server into a router?</summary><br><b>
</b></details>

<details>
<summary>What is a virtual IP? In what situation would you use it?</summary><br><b>
</b></details>

<details>
<summary>Which port is used in each of the following protocols?:

  * SSH
  * HTTP
  * DNS
  * HTTPS</summary><br><b>
</b></details>

<details>
<summary>What is the routing table? How do you view it?</summary><br><b>
</b></details>

<details>
<summary>What are packet sniffers? Have you used one in the past? If yes, which packet sniffers have you used and for what purpose?</summary><br><b>
</b></details>

##### DNS

<details>
<summary>What is DNS? Why do we need it?</summary><br><b>
</b></details>

<details>
<summary>What the file <code>/etc/resolv.conf</code> is used for? What does it include?</summary><br><b>
</b></details>

<details>
<summary>What is a "A record"?</summary><br><b>
</b></details>

<details>
<summary>What is a PTR record?</summary><br><b>

While an A record points a domain name to an IP address, a PTR record does the opposite and resolves the IP address to a domain name.
</b></details>

<details>
<summary>What is a MX record?</summary><br><b>
</b></details>

<details>
<summary>Is DNS using TCP or UDP?</summary><br><b>
</b></details>

##### Packaging

<details>
<summary>Do you have experience with packaging? Can you explain how it works?</summary><br><b>
</b></details>

<details>
<summary>RPM: explain the spec format(what it should and can include)</summary><br><b>
</b></details>

<details>
<summary>How do you list the content of a package without actually installing it?</summary><br><b>
</b></details>

##### Applications and Services

<details>
<summary>What is a load balancer?</summary><br><b> 
</b></details>

<details>
<summary>What load balancer algorithms are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>What is a proxy?</summary><br><b> 
</b></details>

<details>
<summary>What is a reverse proxy?</summary><br><b> 
</b></details>

<details>
<summary>What can you find in /etc/services</summary><br><b>
</b></details>

<details>
<summary>You run <code>ssh 127.0.0.1</code> but it fails with "connection refused". What could be the problem?</summary><br><b>

1. SSH server is not installed
2. SSH server is not running
</b></details>

<details>
<summary>How to print the shared libraries required by a certain program? What is it useful for?</summary><br><b>
</b></details>

<a name="linux-advanced"></a>
#### :star: Advanced

<details>
<summary>What happens when you execute <code>ls</code>?. Provide a detailed answer</summary><br><b>
</b></details>

<details>
<summary>Can you describe how processes are being created?</summary><br><b>
</b></details>

<details>
<summary>What does the following block do?:

```
open("/my/file") = 5
read(5, "file content")
```
</summary><br><b>

These system calls are reading the file <code>/my/file</code> and 5 is the file descriptor number.
</b></details>

<details>
<summary>What is the difference between a process and a thread?</summary><br><b>
</b></details>

##### Network

<details>
<summary>When you run <code>ip a</code> you see there is a device called 'lo'. What is it and why do we need it?</summary><br><b>
</b></details>

<details>
<summary>What <code>traceroute</code> command does? How it works?</summary><br><b>
</b></details>

<details>
<summary>What is network bonding? What types are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>How to link two separate network namespaces so you can ping an interface on one namespace from the second one?</summary><br><b>
</b></details>

<details>
<summary>What are cgroups? In what scenario would you use them?</summary><br><b>
</b></details>

<details>
<summary>How to create a file of a certain size?</summary><br><b>

There are a couple of ways to do that:
  
  * dd if=/dev/urandom of=new_file.txt bs=2MB count=1
  * truncate -s 2M new_file.txt
  * fallocate -l 2097152 new_file.txt
</b></details>

<details>
<summary>What are the differences between the following system calls?: exec(), fork(), vfork() and clone()?</summary><br><b>
</b></details>

<details>
<summary>Explain Process Descriptor and Task Structure</summary><br><b>
</b></details>

<details>
<summary>What are the differences between threads and processes?</summary><br><b>
</b></details>

<details>
<summary>Explain Kernel Threads</summary><br><b>
</b></details>

<details>
<summary>What happens when socket system call is used?</summary><br><b>

This is a good article about the topic: https://ops.tips/blog/how-linux-creates-sockets
</b></details>

<details>
<summary>You executed a script and while still running, it got accidentally removed. Is it possible to restore the script while it's still running?</summary><br><b>
</b></details>


## Ansible

<a name="ansible-beginner"></a>
#### :baby: Beginner

<details>
<summary>Describe each of the following components in Ansible, including the relationship between them:

  * Task
  * Module
  * Play
  * Playbook
  * Role</summary><br><b>

Task – a call to a specific Ansible module
Module – the actual unit of code executed by Ansible on your own host or a remote host. Modules are indexed by category (database, file, network, …) and also referred as task plugins.

Play – One or more tasks executed on a given host(s)

Playbook – One or more plays. Each play can be executed on the same or different hosts

Role – Ansible roles allows you to group resources based on certain functionality/service such that they can be easily reused. In a role, you have directories for variables, defaults, files, templates, handlers, tasks, and metadata. You can then use the role by simply specifying it in your playbook.
</b></details>

<details>
<summary>Which Ansible best practices are you familiar with?. Name at least three</summary><br><b>
</b></details>

<details>
<summary>What is an inventory file and how you define one?</summary><br><b>

An inventory file defines hosts and/or groups of hosts on which Ansible tasks executed upon.

An example of inventory file:

192.168.1.2
192.168.1.3
192.168.1.4

[web_servers]
190.40.2.20
190.40.2.21
190.40.2.22
</b></details>

<details>
<summary>What is a dynamic inventory file? When you would use one?</summary><br><br>

A dynamic inventory file tracks hosts from one or more sources like cloud providers and CMDB systems.

You should use one when using external sources and especially when the hosts in your environment are being automatically<br>
spun up and shut down, without you tracking every change in these sources.
</b></details>

<details>
<summary>You want to run Ansible playbook only on specific minor version of your OS, how would you achieve that?</summary><br><b>
</b></details>

<details>
<summary>Write a task to create the directory ‘/tmp/new_directory’</summary><br><b>

```
- name: Create a new directory
  file:
      path: "/tmp/new_directory"
      state: directory
```
</b></details>

<details>
<summary>What would be the result of the following play?</summary><br><b>

```
---
- name: Print information about my host
  hosts: localhost
  gather_facts: 'no'                                                                                                                                                                           
  tasks:
      - name: Print hostname
        debug:
            msg: "It's me, {{ ansible_hostname }}"
```

When given a written code, always inspect it thoroughly. If your answer is “this will fail” then you are right. We are using a fact (ansible_hostname), which is a gathered piece of information from the host we are running on. But in this case, we disabled facts gathering (gather_facts: no) so the variable would be undefined which will result in failure.
</b></details>

<details>
<summary>Write a playbook to install ‘zlib’ and ‘vim’ on all hosts if the file ‘/tmp/mario’ exists on the system.</summary><br><b>

```
---
- hosts: all
  vars:
      mario_file: /tmp/mario
      package_list:
          - 'zlib' 
          - 'vim'
  tasks:
      - name: Check for mario file
        stat:
            path: "{{ mario_file }}"
        register: mario_f

      - name: Install zlib and vim if mario file exists
        become: "yes"
        package:
            name: "{{ item }}"
            state: present
        with_items: "{{ package_list }}"
        when: mario_f.stat.exists
```
</b></details>

<details>
<summary>Write a playbook to deploy the file ‘/tmp/system_info’ on all hosts except for controllers group, with the following content</summary><br><b>

  ```
  I'm <HOSTNAME> and my operating system is <OS>
  ```

  Replace <HOSTNAME> and  <OS> with the actual data for the specific host you are running on

The playbook to deploy the system_info file

```
--- 
- name: Deploy /tmp/system_info file
  hosts: all:!controllers
  tasks: 
      - name: Deploy /tmp/system_info
        template:
            src: system_info.j2 
            dest: /tmp/system_info
```

The content of the system_info.j2 template

```
# {{ ansible_managed }}
I'm {{ ansible_hostname }} and my operating system is {{ ansible_distribution }
```
</b></details>

<details>
<summary>The variable 'whoami' defined in the following places:

  * role defaults -> whoami: mario
  * extra vars (variables you pass to Ansible CLI with -e) -> whoami: toad
  * host facts -> whoami: luigi
  * inventory variables (doesn’t matter which type) -> whoami: browser

According to variable precedence, which one will be used?</summary><br><b>

The right answer is ‘toad’.

Variable precedence is about how variables override each other when they set in different locations. If you didn’t experience it so far I’m sure at some point you will, which makes it a useful topic to be aware of.

In the context of our question, the order will be extra vars (always override any other variable) -> host facts -> inventory variables -> role defaults (the weakest).

A full list can be found at the link above. Also, note there is a significant difference between Ansible 1.x and 2.x.
</b></details>

<details>
<summary>For each of the following statements determine if it's true or false:

  * A module is a collection of tasks
  * It’s better to use shell or command instead of a specific module
  * Host facts override play variables
  * A role might include the following: vars, meta, and handlers
  * Dynamic inventory is generated by extracting information from external sources
  * It’s a best practice to use indention of 2 spaces instead of 4
  * ‘notify’ used to trigger handlers
  * This “hosts: all:!controllers” means ‘run only on controllers group hosts</summary><br><b>
</b></details>

<details>
<summary>What is ansible-pull?  How it’s different compared to ansible-playbook?</summary><br><b>
</b></details>


<a name="ansible-advanced"></a>
#### :star: Advanced

<details>
<summary>What are filters? Do you have experience with writing filters?</summary><br><b>
</b></details>

<details>
<summary>Write a filter to capitalize a string</summary><br><b>

<code>
def cap(self, string):
    return string.capitalize()
</code>
</b></details>

<details>
<summary>How do you test your Ansible based projects?</summary><br><b>
</b></details>

<details>
<summary>What are callback plugins? What can you achieve by using callback plugins?</summary><br><b>
</b></details>


## Terraform

<a name="terraform-beginner"></a>
#### :baby: Beginner

<details>
<summary>Can you explain what is Terraform? How it works?</summary><br><b>

Read [here](https://www.terraform.io/intro/index.html#what-is-terraform-)
</b></details>

<details>
<summary>What benefits infrastructure-as-code has?</summary><br><b>

- fully automated process of provisioning, modifying and deleting your infrastructure
- version control for your infrastructure which allows you to quickly rollback to previous versions
- validate infrastructure quality and stability with automated tests and code reviews
- makes infrastructure tasks less repetitive
</b></details>

<details>
<summary>Why Terraform and not other technologies? (e.g. Ansible, Puppet, CloufFormation)</summary><br><b>

A common *wrong* answer is to say that Ansible and Puppet are configuration management tools
and Terraform is a provisioning tool. While technically true, it doesn't mean Ansible and Puppet can't
be used for provisioning infrastructure. Also, it doesn't explain why Terraform should be used over
CloudFormation if at all.

The benefits of Terraform over the other tools:

  * It follows the immutable infrastructure approach which has benefits like avoiding a configuration drift over time
  * Ansible and Puppet are more procedural (you mention what to execute in each step) and Terraform is declarative since you describe the overall desired state and not per resource or task. You can give the example of going from 1 to 2 servers in each tool. In Terraform you specify 2, in Ansible and puppet you have to only provision 1 additional server so you need to explicitly make sure you provision only another one server.
</b></details>

<details>
<summary>Explain what is "Terraform configuration"</summary><br><b>
</b></details>

<details>
<summary>Explain each of the following:

  * Provider
  * Resource
  * Provisioner
</b></details>

<details>
<summary>What <code>terraform.tfstate</code> file is used for?</summary><br><b> 

It keeps track of the IDs of created resources so that Terraform knows what it is managing.
</b></details>

<details>
<summary>Explain what the following commands do:

  * <code>terraform init</code>
  * <code>terraform plan</code>
  * <code>terraform validate</code>
  * <code>terraform apply</code>
</summary><br><b>

<code>terraform init</code> scans your code to figure which providers are you using and download them.
<code>terraform plan</code> will let you see what terraform is about to do before actually doing it.
<code>terraform apply</code> will provision the resources specified in the .tf files.
</b></details>

<details>
<summary>How to write down a variable which changes by an external source or during <code>terraform apply</code>?</summary><br><b>

You use it this way: <code>variable “my_var” {}</code>
</b></details>

<details>
<summary>Give an example of several Terraform best practices</summary><br><b>
</b></details>

<details>
<summary>Explain how implicit and explicit dependencies work in Terraform</summary><br><b>
</b></details>

<details>
<summary>What is <code>local-exec</code> and <code>remote-exec</code> in the context of provisioners?</summary><br><b>
</b></details>

<details>
<summary>What is a "tainted resource"?</summary><br><b>

It's a resource which was successfully created but failed during provisioning. Terraform will fail and mark this resource as "tainted".
</b></details>

<details>
<summary>What <code>terraform taint</code> does?</summary><br><b>
</b></details>

<details>
<summary>What types of variables are supported in Terraform?</summary><br><b>

String
Integer
Map
List
</b></details>

<details>
<summary>What are output variables and what <code>terraform output</code> does?</summary><br><b>
</b></details>

<details>
<summary>Explain Modules</summary>
</b></details>

<details>
<summary>What is the Terraform Registry?</summary><br><b>
</b></details>

<a name="terraform-advanced"></a>
#### :star: Advanced

<details>
<summary>Explain "Remote State". When would you use it and how?</summary><br><b>
</b></details>

<details>
<summary>Explain "State Locking"</summary><br><b>
</b></details>

## Docker

<a name="docker-beginner"></a>

#### :baby: beginner

<details>
<summary>What is Docker? What are you using it for?</summary><br><b>
Docker is a containerization platform which packages your application and all its dependencies together in the form of containers so as to ensure that your application works seamlessly in any environment be it development or test or production.

* Docker containers, wrap a piece of software in a complete filesystem that contains everything needed to run: code, runtime, system tools, system libraries etc. anything that can be installed on a server.
* This guarantees that the software will always run the same, regardless of its environment.
</b></details>

<details>
<summary>What is docker image?</summary><br><b>
Docker image is the source of Docker container. In other words, Docker images are used to create containers. Images are created with the build command, and they’ll produce a container when started with run. Images are stored in a Docker registry such as registry.hub.docker.com because they can become quite large, images are designed to be composed of layers of other images, allowing a minimal amount of data to be sent when transferring images over the network.
</b></details>

<details>
<summary> What is Docker container?</summary><br><b>
Docker containers include the application and all of its dependencies, but share the kernel with other containers, running as isolated processes in user space on the host operating system. Docker containers are not tied to any specific infrastructure: they run on any computer, on any infrastructure, and in any cloud. 
</b></details>

<details>
<summary>How to create a docker container?</summary><br><b>
Docker containers are basically runtime instances of Docker images.We can use Docker image to create Docker container by using the below command:
1
	docker run -t -i command name
	This command will create and start a container.
You should also add, If you want to check the list of all running container with the status on a host use the below command:
1
	docker ps -a
</b></details>

<details>
<summary>What is Docker hub?</summary><br><b>
Docker hub is a cloud-based registry service which allows you to link to code repositories, build your images and test them, stores manually pushed images, and links to Docker cloud so you can deploy images to your hosts. It provides a centralized resource for container image discovery, distribution and change management, user and team collaboration, and workflow automation throughout the development pipeline.
</b></details>


<details>
<summary>How is Docker different from other container technologies?</summary><br><b>
Docker containers are easy to deploy in a cloud. It can get more applications running on the same hardware than other technologies, it makes it easy for developers to quickly create, ready-to-run containerized applications and it makes managing and deploying applications much easier. You can even share containers with your applications.
If you have some more points to add you can do that but make sure the above the above explanation is there in your answer.
</b></details>

<details>
<summary>What is docker Swarm?</summary><br><b>
Docker Swarm is native clustering for Docker. It turns a pool of Docker hosts into a single, virtual Docker host. Docker Swarm serves the standard Docker API, any tool that already communicates with a Docker daemon can use Swarm to transparently scale to multiple hosts.
</b></details>

<details>
<summary> What is Dockerfile used for?</summary><br><b>
Docker can build images automatically by reading the instructions from a Dockerfile.

A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image. Using docker build users can create an automated build that executes several command-line instructions in succession.
Now, the next set of Docker interview questions will test your experience with Docker.
</b></details>

<details>
<summary>Can I use json instead of yaml for my compose file in Docker?</summary><br><b>
You can use json instead of yaml for your compose file, to use json file with compose, specify the filename to use for eg:
docker-compose -f docker-compose.json up
</b></details>

<details>
<summary> How to stop and restart the Docker container??</summary><br><b>
In order to stop the Docker container you can use the below command:
1
	docker stop container ID
	Now to restart the Docker container you can use:
1
	docker restart container ID
</b></details>

<details>
<summary> How far do Docker containers scale?</summary><br><b>
Large web deployments like Google and Twitter, and platform providers such as Heroku and dotCloud all run on container technology, at a scale of hundreds of thousands or even millions of containers running in parallel.
</b></details>

<details>
<summary> What platforms does Docker run on?</summary><br><b>
 * Ubuntu 12.04, 13.04 et al
   * Fedora 19/20+
   * RHEL 6.5+
   * CentOS 6+
   * Gentoo
   * ArchLinux
   * openSUSE 12.3+
   * CRUX 3.0+
Cloud:
   * Amazon EC2
   * Google Compute Engine
   * Microsoft Azure
   * Rackspace
</b></details>

<details>
<summary>How containers are different from VMs?</summary><br><b>

The primary difference between containers and VMs is that containers allow you to virtualize
multiple workloads on the operating system while in the case of VMs the hardware is being virtualized to
run multiple machines each with its own OS.
</b></details>

<details>
<summary> Do I lose my data when the Docker container exits?</summary><br><b>
no I won’t lose my data when Docker container exits, any data that your application writes to disk gets preserved in its container until you explicitly delete the container. The file system for the container persists even after the container halts.
</b></details>

<details>
<summary>In which scenarios would you use containers and in which you would prefer to use VMs?</summary><br><b>

You should choose VMs when:
  * you need run an application which requires all the resources and functionalities of an OS
  * you need full isolation and security

You should choose containers when:
  * you need a lightweight solution that quickly starts
  * Running multiple versions or instances of a single application
</b></details>

<details>
<summary>Explain Docker architecture</summary><br><b>
</b></details>

<details>
<summary>Describe in detail what happens when you run `docker run hello-world`?</summary><br><b>

Docker CLI passes your request to Docker daemon.
Docker daemon downloads the image from Docker Hub
Docker daemon creates a new container by using the image it downloaded
Docker daemon redirects output from container to Docker CLI which redirects it to the standard output
</b></details>

<details>
<summary>How do you run a container?</summary><br><b>
</b></details>

<details>
<summary>What best practices are you familiar related to working with containers?</summary><br><b>
</b></details>

<details>
<summary>What `docker commit` does?. When will you use it?</summary><br><b>
</b></details>

<details>
<summary>How would you transfer data from one container into another?</summary><br><b>
</b></details>

<details>
<summary>What happens to data of the container when a container exists?</summary><br><b>
</b></details>

<details>
<summary>Explain what each of the following commands do:

  * docker run
  * docker rm
  * docker ps
  * docker build
  * docker commit</summary><br><b>
</b></details>

<details>
<summary>How do you remove old, non running, containers?</summary><br><b>
</b></details>

##### Dockerfile

<details>
<summary>What is Dockerfile</summary><br><b>
</b></details>

<details>
<summary>What is the difference between ADD and COPY in Dockerfile?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between CMD and RUN in Dockerfile?</summary><br><b>
</b></details>

<details>
<summary>Explain what is Docker compose and what is it used for</summary><br><b>
</b></details>

<details>
<summary>What are the differences between Docker compose, Docker swarm and Kubernetes?</summary><br><b>
</b></details>

<details>
<summary>Explain Docker interlock</summary><br><b>
</b></details>

<details>
<summary>What is the difference between Docker Hub and Docker cloud?</summary><br><b>

Docker Hub is a native Docker registry service which allows you to run pull
and push commands to install and deploy Docker images from the Docker Hub.

Docker Cloud is built on top of the Docker Hub so Docker Cloud provides
you with more options/features compared to Docker Hub. One example is
Swarm management which means you can create new swarms in Docker Cloud.
</b></details>

<details>
<summary>Where Docker images are stored?</summary><br><b>
</b></details>

<details>
<summary>Explain image layers</summary><br><b>
</b></details>

<a name="docker-advanced"></a>
#### :star: Advanced

<details>
<summary>How do you manage persistent storage in Docker?</summary><br><b>
</b></details>

<details>
<summary>How can you connect from the inside of your container to the localhost of your host, where the container runs?</summary><br><b>
</b></details>

<details>
<summary>How do you copy files from Docker container to the host and vice versa?</summary><br><b>
</b></details>

## Kubernetes

<a name="kubernetes-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Kubernetes?</summary><br><b>
</b></details>

<details>
<summary>Why Docker isn't enough? Why do we need Kubernetes?</summary><br><b>
</b></details>

<details>
<summary>Describe the architecture of Kubernetes</summary><br><b>
</b></details>

<details>
<summary>How do you monitor your Kubernetes?</summary><br><b>
</b></details>

<details>
<summary>What is kubectl? How do you use it?</summary><br><b>
</b></details>

<details>
<summary>What is kubconfig? What do you use it for?</summary><br><b>
</b></details>

##### Users

<details>
<summary>How do you create users? Where user information is stored?</summary><br><b>
</b></details>

<details>
<summary>Do you know how to create a new user without using adduser/useradd command?</summary><br><b>
</b></details>

<details>
<summary>How to add a new user to the system without providing him the ability to log-in into the system?</summary><br><b>

  * adduser user_name --shell=/bin/false --no-create-home
</b></details>

<details>
<summary>What can you do if you lost/forogt the root password?</summary><br><b>

Re-install the OS IS NOT the right answer :)
</b></details>

<details>
<summary>What is sudo? How do you set it up?</summary><br><b>
</b></details>

## Coding

<a name="coding-beginner"></a>
#### :baby: Beginner

<details>
<summary>What programming language do you prefer to use for DevOps related tasks? Why specifically this one?</summary><br><b>
</b></details>

<details>
<summary>What is Object Oriented Programming? Why is it important?</summary><br><b>
</b></details>

<details>
<summary>Explain recursion</summary<br><b>
</b></details>

<details>
<summary>Explain what are design patterns and describe three of them in detail</summary><br><b>
</b></details>

<details>
<summary>Explain big O notation</summary><br><b>
</b></details>

##### Code Review

<details>
<summary>What are your code-review best practices?</summary><br><b>
</b></details>

<details>
<summary>Do you agree/disagree with each of the following statements and why?:

  * The commit message is not important. When reviewing a change/patch one should focus on the actual change</summary><br><b>
  * You shouldn't test your code before submitting it. This is what CI/CD exists for.
</b></details>

##### Strings

<details>
<summary>In any language you want, write a function to determine if a given string is a palindrome</summary><br><b>
</b></details>

<details>
<summary>In any language you want, write a function to determine if two strings are Anagrams </summary><br><b>
</b></details>

<a name="coding-advanced"></a>
#### :star: Advanced

<details>
<summary>Name 3 design patterns. Do you know how to implement (= provide an example) these design pattern in any language you'll choose?</summary><br><b>
</b></details>

## Python

<a name="python-beginner"></a>
#### :baby: Beginner

<details>
<summary>What are some characteristics of the Python programming language?</summary><br><b>

```
1. It is a high level general purpose programming language created in 1991 by Guido Van Rosum.
2. The language is interpreted, being the CPython (Written in C) the most used/maintained implementation.
3. It is strongly typed. The typing discipline is duck typing and gradual.
4. Python focuses on readability and makes use of whitespaces/identation instead of brackets { }
5. The python package manager is called PIP "pip installs packages", having more than 200.000 available packages.
6. Python comes with pip installed and a big standard library that offers the programmer many precooked solutions.
7. In python **Everything** is an object.

There are many other characteristics but these are the main ones that every python programmer should know.

```
</b></details>

<details>
<summary>What data types supported in Python and which of them are mutable? How can you show that a certain data type is mutable?</summary><br><b>

The mutable data types are:

    List
    Dictionary
    Set
    
The immutable data types are:

    Numbers (int, float, ...)
    String
    Bool
    Tuple
    Frozenset

You can usually use the function hash() to check an object mutability, if it is hashable it is immutable, although this does not always work as intended as user defined objects might be mutable and hashable
</b></details>

<details>
<summary>What is PEP8? Give an example of 3 style guidelines</summary><br><b>

PEP8 is a list of coding conventions and style guidelines for Python

5 style guidelines:

    1. Limit all lines to a maximum of 79 characters.
    2. Surround top-level function and class definitions with two blank lines.
    3. Use commas when making a tuple of one element
    4. Use spaces (and not tabs) for indentation
    5. Use 4 spaces per indentation level
</b></details>

<details>
<summary>Explain inheritance and how to use it in Python</summary><br><b>

```
By definition inheritance is the mechanism where an object acts as a base of another object, retaining all its
properties.

So if Class B inherits from Class A, every characteristics from class A will be also available in class B.
Class A would be the 'Base class' and B class would be the 'derived class'.

This comes handy when you have several classes that share the same functionalities.

The basic syntax is:

class Base: pass

class Derived(Base): pass

A more forged example:

class Animal:
    def __init__(self):
        print("and I'm alive!")

    def eat(self, food):
        print("ñom ñom ñom", food)

class Human(Animal):
    def __init__(self, name):
        print('My name is ', name)
        super().__init__()

    def write_poem(self):
        print('Foo bar bar foo foo bar!')

class Dog(Animal):
    def __init__(self, name):
        print('My name is', name)
        super().__init__()

    def bark(self):
        print('woof woof')


michael = Human('Michael')
michael.eat('Spam')
michael.write_poem()

bruno = Dog('Bruno')
bruno.eat('bone')
bruno.bark()

>>> My name is  Michael
>>> and I'm alive!
>>> ñom ñom ñom Spam
>>> Foo bar bar foo foo bar!
>>> My name is Bruno
>>> and I'm alive!
>>> ñom ñom ñom bone
>>> woof woof

Calling super() calls the Base method, thus, calling super().__init__() we called the Animal __init__.

There is a more advanced python feature called MetaClasses that aid the programmer to directly control class creation.

```

</b></details>

<details>
<summary> What is an error? What is an exception? What types of exceptions are you familiar with?</summary><br><b>

```

#  Note that you generally don't need to know the compiling process but knowing where everything comes from
#  and giving complete answers shows that you truly know what you are talking about.

Generally, every compiling process have a two steps.
    - Analysis
    - Code Generation.
    
    Analysis can be broken into:
        1. Lexical analysis   (Tokenizes source code)
        2. Syntactic analysis (Check whether the tokens are legal or not, tldr, if syntax is correct)
           
               for i in 'foo'
                          ^
             SyntaxError: invalid syntax
        
        We missed ':'
        
        
        3. Semantic analysis  (Contextual analysis, legal syntax can still trigger errors, did you try to divide by 0,
          hash a mutable object or use an undeclared function?)
          
                 1/0
                ZeroDivisionError: division by zero
        
    These three analysis steps are the responsible for error handlings.
    
    The second step would be responsible for errors, mostly syntax errors, the most common error.
    The third step would be responsible for Exceptions.
    
    As we have seen, Exceptions are semantic errors, there are many builtin Exceptions:
        
        ImportError
        ValueError
        KeyError
        FileNotFoundError
        IndentationError
        IndexError
        ...
    
    You can also have user defined Exceptions that have to inherit from the `Exception` class, directly or indirectly.

    Basic example:
        
    class DividedBy2Error(Exception):
        def __init__(self, message):
            self.message = message
    
    
    def division(dividend,divisor):
        if divisor == 2:
            raise DividedBy2Error('I dont want you to divide by 2!')
        return dividend / divisor
    
    division(100, 2)
    
    >>> __main__.DividedBy2Error: I dont want you to divide by 2!

```


</b></details>

<details>
<summary>Explain Exception Handling and how to use it in Python</summary><br><b>
</b></details>

<details>
<summary>Write a program which will revert a string (e.g. pizza -> azzip)</summary><br><b>

```
Shortest way is str[::-1] but not the most efficient.

"Classic" way:

foo = ''

for char in 'pizza':
    foo = char + foo

>> 'azzip'   

```
</b></details>

<details>
<summary>How to extract the unique characters from a string? for example given the input "itssssssameeeemarioooooo" the output will be "mrtisaoe"</summary><br><b>

```
x = "itssssssameeeemarioooooo"
y = ''.join(set(x))
```
</b></details>

<details>
<summary>Write a function to return the sum of one or more numbers. The user will decide how many numbers to use</summary><br><b>

First you ask the user for the amount of numbers that will be use. Use a while loop that runs until amount_of_numbers becomes 0 through subtracting amount_of_numbers by one each loop. In the while loop you want ask the user for a number which will be added a variable each time the loop runs.

```
def return_sum():
	amount_of_numbers = int(input("How many numbers? "))
	total_sum = 0
	while amount_of_numbers != 0:
		num = int(input("Input a number. "))
		total_sum += num
		amount_of_numbers -= 1
	return total_sum

```
</b></details>

<details>
<summary>How to merge two sorted lists into one sorted list?</summary><br><b>
</b></details>

<details>
<summary>How to merge two dictionaries?</summary><br><b>
</b></details>

<details>
<summary>How do you swap values between two variables?</summary><br><b>

x, y = y, x
</b></details>

<details>
<summary>How to check if all the elements in a given lists are unique? so [1, 2, 3] is unique but [1, 1, 2, 3] is not unique but we 1 twice</summary><br><b>
</b></details>

<details>
<summary>What _ is used for in Python?</summary><br><b>

1. Translation lookup in i18n
2. Hold the result of the last executed expression or statement in the interactive interpreter.
3. As a general purpose "throwaway" variable name. For example: x, y, _ = get_data() (x and y are used but since we don't care about third variable, we "threw it away").
</b></details>

<details>
<summary>How to check how much time it took to execute a certain script or block of code?</summary><br><b>
</b></details>

##### Algorithms Implementation

<details>
<summary>Can you implement "binary search" in Python?</summary><br><b>
</b></details>

##### Files

<details>
<summary>How to write to a file?</summary><br><b>

```
with open('file.txt', 'w') as file:
    file.write("My insightful comment")
```
</b></details>

<details>
<summary>How to reverse a file?</summary><br><b>
</b></details>

#### Regex

<details>
<summary>How do you perform regular expressions related operations in Python? (match patterns, substitute strings, etc.)</summary><br><b>

Using the re module
</b></details>

<details>
<summary>How to substitute the string "green" with "blue"?</summary><br><b>
</b></details>

<details>
<summary>How to find all the IP addresses in a variable? How to find them in a file?</summary><br><b>
</b></details>

<details>
<summary>Sort a list of lists by the second item of each nested list</summary><br><b>

```
li = [[1, 4], [2, 1], [3, 9], [4, 2], [4, 5]]

sorted(x, key=lambda l: l[1])
```
</b></details>

<details>
<summary>Can you write a function which will print all the file in a given directory? including sub-directories</summary><br><b>
</b></details>

<details>
<summary>You have the following list: <code>[{'name': 'Mario', 'food': ['mushrooms', 'goombas']}, {'name': 'Luigi', 'food': ['mushrooms', 'turtles']}]</code>
  Extract all type of foods. Final output should be: {'mushrooms', 'goombas', 'turtles'}</summary><br><b>

```
brothers_menu =  \
[{'name': 'Mario', 'food': ['mushrooms', 'goombas']}, {'name': 'Luigi', 'food': ['mushrooms', 'turtles']}]

# "Classic" Way
def get_food(brothers_menu) -> set:
    temp = []

    for brother in brothers_menu:
        for food in brother['food']:
            temp.append(food)

    return set(temp)

# One liner way (Using list comprehension)
set([food for bro in x for food in bro['food']])
```

</b></details>

<details>
<summary>What is List Comprehension? Is it better than a typical loop? Why? Can you demonstrate how to use it?</summary><br><b>
</b></details>

<details>
<summary>How to reverse a string?</summary><br><b>

Shortest way is: <code>my_string[::-1]</code> but it doesn't mean it's the most efficient one. <br>
Cassic way is:
```
def reverse_string(string):
    temp = ""
    for char in string:
        temp =  char + temp
    return temp
```
</b></details>

<details>
<summary>How to sort a dictionary by values?</summary><br><b>
</b></details>

<details>
<summary>How to sort a dictionary by keys?</summary><br><b>
</b></details>

<details>
<summary>Explain data serialization and how do you perform it with Python</summary><br><b>
</b></details>

<details>
<summary>How do you handle argument parsing in Python?</summary><br><b>
</b></details>

<details>
<summary>Explain what is GIL</summary><br><b>
</b></details>

<details>
<summary>What is a generator? Why using generators?</summary><br><b>
</b></details>

<details>
<summary>Explain the following types of methods and how to use them:

  * Static method
  * Class method
  * instance method</summary><br><b>
</b></details>

<details>
<summary>How to reverse a list?</summary><br><b>
</b></details>

<details>
<summary>How to combine list of strings into one string with spaces between the strings</summary><br><b>
</b></details>

<details>
<summary>What empty <code>return</code> returns?</summary><br><b>
</b></details>

##### Time Complexity

<details>
<summary>Describe what would be the time complexity of the operations <code>access</code>, <code>search</code> <code>insert</code> and <code>remove</code> for the following data structures:</summary><br><b>

  * Stack
  * Queue
  * Linked List
  * Binary Search Tree
</b></details>

<details>
<summary>What is the complexity for the best, worst and average cases of each of the following algorithms?:

  * Quick sort
  * Merge sort
  * Bucket Sort
  * Radix Sort
</b></details>

<a name="python-advanced"></a>
#### :star: Advanced

<details>
<summary>Explain what is a decorator</summary><br><b>
</b></details>

<details>
<summary>Can you show how to write and use decorators?</summary><br><b>
</b></details>

<details>
<summary>Write a script which will determine if a given host is accessible on a given port</summary><br><b>
</b></details>

<details>
<summary>Are you familiar with Dataclasses? Can you explain what are they used for?</summary><br><b>
</b></details>

<details>
<summary>Explain Context Manager</summary><br><b>
</b></details>

<details>
<summary>Explain the Buffer Protocol</summary><br><b>
</b></details>

<details>
<summary>Explain Descriptors</summary><br><b>
</b></details>

<details>
<summary>Do you have experience with web scraping? Can you describe what have you used and for what?</summary><br><b>
</b></details>

<details>
<summary>Can you implement Linked List in Python?<br><b>
</b></details>

<details>
<summary>You have created a web page where a user can upload a document. But the function which reads the uploaded files, runs for a long time, based on the document size and user has to wait for the read operation to complete before he/she can continue using the web site. How can you overcome this?</summary><br><b>
</b></details>

## Monitoring

<a name="monitoring-beginner"></a>
#### :baby: Beginner

<details>
<summary>Explain monitoring. What is it? What its goal?</summary><br><b>
</b></details>

<details>
<summary>What is wrong with the old approach of watching for a specific value and trigger an email/phone alert while value is exceeded?</summary><br><b>

This approach require from a human to always check why the value exceeded and how to handle it while today, it is more effective to notify people only when they need to take an actual action.
If the issue doesn't require any human intervention, then the problem can be fixed by some processes running in the relevant environment.
</b></details>

<details>
<summary>What types of monitoring outputs are you familiar with and/or used in the past?</summary><br><b>

Alerts
Tickets
Logging
</b></details>

<details>
<summary>What is the different between infrastructure monitoring and application monitoring? (methods, tools, ...)</summary><br><b>
</b></details>

## Prometheus

<a name="prometheus-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Prometheus? What are some of Prometheus's main features?</summary><br><b>
</b></details>

<details>
<summary>Describe Prometheus architecture and components</summary><br><b>
</b></details>

<details>
<summary>Can you compare Prometheus to other solutions like InfluxDB for example?</summary><br><b>
</b></details>

<details>
<summary>What is an Alert?</summary><br><b>
</b></details>

<details>
<summary>Describe the following Prometheus components:

  * Prometheus server
  * Push Gateway
  * Alert Manager</summary><br><b>

Prometheus server responsible for scraping the storing the data<br>
Push gateway is used for short-lived jobs<br>
Alert manager is responsible for alerts ;)
</b></details>

<details>
<summary>What is an Instance? What is a Job?</summary><br><b>
</b></details>

<details>
<summary>What core metrics types Prometheus supports?</summary><br><b>
</b></details>

<details>
<summary>What is an exporter? What is it used for?</summary><br><b>
</b></details>

<details>
<summary>Which Prometheus best practices are you familiar with?. Name at least three</summary><br><b>
</b></details>

<details>
<summary>How to get total requests in a given period of time?</summary><br><b>
</b></details>

<a name="prometheus-advanced"></a>
#### :star: Advanced

<details>
<summary>How do you join two metrics?</summary><br><b>
</b></details>

<details>
<summary>How to write a query that returns the value of a label?</summary><br><b>
</b></details>

<details>
<summary>How do you convert cpu_user_seconds to cpu usage in percentage?</summary><br><b>
</b></details>

## Git

<a name="git-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is the difference between <code>git pull</code> and <code>git fetch</code>?</summary><br><b>

Shortly, git pull = git fetch + git merge

When you run git pull, it gets all the changes from the remote or central
repository and attaches it to your corresponding branch in your local repository.

git fetch gets all the changes from the remote repository, stores the changes in
a separate branch in your local repository
</b></details>

<details>
<summary>Explain the following: <code>git directory</code>, <code>working directory</code> and <code>staging area</code></summary><br><b>

The Git directory is where Git stores the meta data and object database for your project. This is the most important part of Git, and it is what is copied when you clone a repository from another computer.

The working directory is a single checkout of one version of the project. These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.

The staging area is a simple file, generally contained in your Git directory, that stores information about what will go into your next commit. It’s sometimes referred to as the index, but it’s becoming standard to refer to it as the staging area.

This answer taken from [git-scm.com](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics#_the_three_states)
</b></details>

<details>
<summary>How to resolve git merge conflicts?</summary><br><b>

<p>
First, you open the files which are in conflict and identify what are the conflicts.
Next, based on what is accepted in your company or team, you either discuss with your
colleagues on the conflicts or resolve them by yourself
After resolving the conflicts, you add the files with `git add <file_name>`
Finally, you run `git rebase --continue`
</p>
</b></details>

<details>
<summary>What is the difference between <code>git reset</code> and <code>git revert</code>?</summary><br><b>

<p>

`git revert` creates a new commit which undoes the changes from last commit.

`git reset` depends on the usage, can modify the index or change the commit which the branch head
is currently pointing at.
</p>
</b></details>

<details>
<summary>You would like to move forth commit to the top. How would you achieve that?</summary><br><b>

Using <code>git rebase></code> command
</b></details>

<details>
<summary>In what situations are you using <code>git rebase</code>?</summary><br><b>
</b></details>

<details>
<summary>What merge strategies are you familiar with?</summary><br><b>

Mentioning two or three should be enough and it's probably good to mention that 'recursive' is the default one.

recursive
resolve
ours
theirs

This page explains it the best: https://git-scm.com/docs/merge-strategies
</b></details>

<details>
<summary>How can you see which changes have done before committing them?</summary><br><b>

<code>git diff</code>
</b></details>

<details>
<summary>How do you revert a specific file to previous commit?</summary><br><b>

```
git checkout HEAD~1 -- /path/of/the/file
```
</b></details>

<details>
<summary>What is the <code>.git</code> directory? What can you find there?</summary><br><b>
</b></details>

<details>
<summary>What are some Git anti-patterns? Things that you shouldn't do</summary><br><b>

  * Not waiting to long between commits
  * Not removing the .git directory :)
  
  </b></details>
  
 <details>
<summary> What is SubGitsumm?</ary><br><b>
 SubGit is software tool used for migrating SVN to Git.  It is very easy to use.  By using this we can create a writable Git mirror of a subversion repository
</b></details>

<details>
<summary>  How can we know if a branch is already merged into master in GIT??</ary><br><b>
  If a branch is already merged into master, we can use following commands 
  git branch --merged master.  This prints the branches merged into master
  git branch --merged lists.  This prints the branched merged into HEAD (i.e. tip of current branch)
  git branch --no-merged.  This prints the branches that have not been merged
  We can use -a flag to show both local and remote branches or we can use -r flag to show only the remote branches.
</b></details>
  
<details>
<summary> What is the purpose of git stash drop????</ary><br><b>
A:  In case we do not need a specific stash, we use git stash drop command to remove it from the list of stashes.
By default, this command removes the latest added stash.
To remove a specific stash we specify as argument in the git stash drop
<stashname> command.
</b></details>

<details>
<summary>   What is the HEAD in GIT? </ary><br><b>
A:  HEAD is a reference to the currently checked out commit.  It is a symbolic reference to the branch that we have checked out.  At any given time, one head is selected as the ‘current hear’.  This head is also known as HEAD (always in uppercase).
</b></details>

<details>
<summary>   What is the most popular branching strategy in GIT? <ary><br><b>
A:  There are many ways to do branching in GIT.  One of the popular ways is to maintain two branches.
Master:  This branch is used for production.  In this branch HEAD is always in production ready state.
Develop:  This branch is used for development.  In this branch, we store the latest code developed in project.  This is work in progress code.
GIT COMMANDS REFRESHER 1
We have captured popular GIT Commands for you to refresh your knowledge of GIT version control system.
Read about these commands to prepare well for GIT Interview.  Test yourself on which GIT commands you already know about.
git init
Use it to initialize a git repository.  It will create initial ‘.git’ directory in a new or in an existing project.
Eg. cd /Users/user/new git folder/ git init
git config
You can use it to set configuration values for your username, email address, key or preferred diff algorithm, file formats etc.
Eg.git config --global user.name "JohnDoe"
git config --global user.email "john@doe.com"
cat ~/.gitconfig [user] name = JohnDoe email = john@doe.com
git clone
We can make a copy of Git repository from a remote GIT source.  It adds the original location as a remote, so we can fetch from it again and push to it if we have permissions.
Eg. git clone git@github.com:user/john.git
</b></details>

<details>
<summary> 6)  What is SubGit? </ary><br><b>
A:  SubGit is software tool used for migrating SVN to Git.  It is very easy to use.  By using this we can create a writable Git mirror of a subversion repository
It creates a bi-directional mirror that can be used for pushing to Git as well as committing to Subversion.
SubGit also takes care of synchronization between Git and Subversion.
</b></details>

 <details>
 <summary> How can we see most recent commits in GIT??</ary><br><b>
   We can use git log command to see the latest commits.  To see the three most recent commits, we use following command git log -3
</b></details>

<details>
<summary> 7)  What is the use of git instaweb?</ary><br><b>
A:  Git-instaweb is a script by which we can browse a git repository in a web browser.
It sets up the gitweb and a web-server that makes the working repository available online.
</b></details>

<details>
<summary> What are git hooks? </ary><br><b>
A:  Git hooks are scripts that can run automatically on the occurrence of an event in a Git repository.
These are used for automation of workflow in GIT.
Git hooks also help in customizing the internal behavior of GIT.
These are generally used for enforcing a GIT commit policy.
</b></details>

<details>
<summary> What is a repository in GIT? </ary><br><b>
A:  A repository in GIT is the place in which we store our software work.
It contains a sub-directory called git.  There is only one git directory in the root of the project.
GIT stores all the metadata for the repository.  The contents of git directory are of internal use to GIT.
</b></details>

<details>
<summary> what is git? </ary><br><b>
A:  GIT is a mature Distributed Version Control System (DVCS).
It is used for Source Code Management (SCM).
It is open source software.  It was developed by Linus Torvalds, the creator of Linux operating system.
GIT works well with a large number of IDEs (Integrated Development Environments) like- Eclipse, Intelij etc.
GIT can be used to handle small and large projects.
</b></details>

<details>
<summary> What are the main benefits of GIT? </ary><br><b>
Main benefits of GIT.
   * Distributed system.
   * Flexible workflow.
   * Fast.
   * Data Integrity.
   * Free.
   * Collaboration.
Distributed System:  GIT is a Distributed Version Control System (DVCS).  So you can keep your private work in version control but completely hidden from others.  You can work offline as well.
Flexible Workflow:  GIT allows you to create your own workflow.  You can use the process that is suitable for your project.  You can go for centralized or master-slave or any other workflow.
Fast:  GIT is very fast when compared to other version control systems.
Data Integrity:  Since GIT uses SHA1, data is not easier to corrupt.
Free:  It is free for personal use.  So many amateurs use it for their initial projects.  It also works very well with large size project.
Collaboration:  GIT is very easy to use for projects in which collaboration is required.  Many popular open source software across the globe use GIT.
</b></details>

<details>
<summary> What are the disadvantages of GIT?
A:  Disadvantages of GIT
   * Binary Files
   * Steep Learning Curve
   * Slow remote speed
Binary Files:  If we have a lot binary files (non-text) in our project, then GIT becomes very slow.  Eg:  Projects with a lot of images or word documents.
Steep Learning Curve:  It takes some time for a newcomer to learn GIT.  Some of the GIT commands are non-intuitive to a fresher.
Slow remote speed:  Sometimes the use of remote repositories in slow due to network latency.  Still GIT is better than other VCS in speed.
GIT COMMANDS REFRESHER 2
We have captured popular GIT Commands for you to refresh your knowledge of GIT version control system.
Read about these commands to prepare well for GIT interview.  Test yourself on which GIT commands you already know about.
git add
This command is used to add any file changes in working directory to the index.
Eg.git add .
git rm
This command is used to remove files from our index and our local working directory.  Then these files will not be tracked.
Eg. git rm filename
git commit
We use this command to take all the changes done on the index, to create a new commit object pointing to it and to set the branch to point to the new commit.
Eg.
git commit -m ‘My changes’ 
git commit -a -m ‘My changes for git add and git commit’
</b></details>

<details>
<summary> 13)  What are the main differences between GIT and SVN? </ary><br><b>
 GIT Vs. SVN
   * Decentalized.
   * Complex to learn.
   * Unable to handle Binary files.
   * Internal directory.
   * User Interface.
Decentralized:  GIT is decentralized.  You have a local copy that is a repository in which you can commit.  In SVN you have to always connect to a central repository for check-in.
Complex to learn:  GIT is a bit difficult to learn for some developers.  It has more concepts and commands to learn.  SVN is much easier to learn.
Unable to handle Binary files :  GIT becomes slow it deals with large binary files that change frequently.  SVN can handle large binary files easily.
Internal directory:  GIT creates only .git directory.  SVN creates .svn directory in each folder.
User Interface:  GIT does not have good UT, but SVN has good user interfaces.
</b></details>

<details>
<summary>14)  How will you start GIT for your project? </ary><br><b>
A:  Start GIT for your project
We use git init command in an existing project directory to start version control for our project.
After this we can use git add and git commit commands to add files to out GIT repository.
</b></details>

<details>
<summary> 15)  What is git clone in GIT? </ary><br><b>
In GIT, we use git clone command to create a copy of an existing GIT repository in our local.
This is the most popular way to create a copy of the repository among developers.
It is similar to svn checkout, but in this case the working copy is a full-fledged repository.
</b></details>

<details>
<summary> 16)  How will you create a repository in GIT? </ary><br><b>
To create a new repository in GIT, first we create a directory for the project.
Then we run ‘git init’ command.
</b></details>

<details>
<summary> 17)  What are the different ways to start work in GIT? </ary><br><b>
  Star work in GIT
New Project:  To create a new repository we use git init command.
Existing Project:  To work on an existing repository we use git clone command.
</b></details>

<details>
<summary> GIT written in which language?</ary><br><b>
A:  GIT Language
Most of the GIT distributions are written in C language with Bourne shell.  Some of the commands are written in Perl language.
</b></details>

<details>
<summary>19)  What does ‘git pull’ command in GIT do internally?</ary><br><b>
A:  Pull command of GIT
In GIT, git pull internally does a git fetch first and then does a git merge.
So pull is a combination of two commands that is fetch and merge.
We use git pull command to bring our local branch up to date with its remote version.
</b></details>

<details>
<summary>20)  What does ‘git push’ command in GIT do internally?</ary><br><b>
A:  Push command of GIT
   * fetch
   * merge
Fetch:  First GIT, copies all the extra commits from server into local repo and move origin/master branch pointer to the end of commit chain.
Merge:  Then it merges the origin/master branch into the master branch.  Now the master branch pointer moves to the newly created commit.  But the origin/master pointer remains there
</b></details>

<details>
<summary> 21)  What is git Stash?</ary><br><b>
  git stash
In GIT, sometimes we do not want to commit our code, but we do not want to lose also the unfinished code.  In this case we use git stash command to record the current state of the working directory and index in a stash.
This stores the unfinished work in a strash, and cleans the current branch from uncommitted changes.
Now we can work on a clean working directory.
Later we can use the stash and apply those changes back to our working directory.  At times we are in the middle of some work and do not want to lose the unfinished work, we use git stash command.
</b></details>

<details>
<summary> 22)  What is the meaning of ‘stage’ in GIT?</ary><br><b>
A:  Meaning of ‘stage’ in GIT
In GIT, stage is a step before commit.  To stage means that the files are ready for commit.
Let say, you are working on two features in GIT.  One of the features is finished and the other is not yet ready.  You want to commit and leave for home in the evening.
GIT COMMANDS REFRESHER 3
We have captured popular GIT Commands for you to refresh your knowledge of GIT version control system.
Read about these commands to prepare well for GIT interview. Test yourself on which GIT commands you already know about.
Git status
This command can shows the status of files in index compared with the working directory.  It lists out the files that are untracked, modified (tracked but not yet updated in the index), and staged (added to the index and ready for commit).
Eg. 
git status 
# On branch master 
# # Initial commit 
# # Untracked files: # (use "git add <file>..." to include in what will be committed) 
# # README nothing added to commit but untracked files present (use "git add" to track)
git branch
This command is used to list existing branches.  It will include remote branches if ‘-a’ is passed as parameter.
It can create a new branch if a branch name is provided.
Eg. git branch -a * master remotes/origin/master
git checkout
When we want to work on a branch, we use git checkout to check out that branch. 
It switches branch by updating the index, working tree, and HEAD to reflect the chosen branch.                                                                                                                                      Eg. git checkout myNewBranch
</b></details>

<details>
<summary>  What is the purpose of git config command?</ary><br><b>
A:  git config command
We can set the configuration options for GIT installation by using git config command.
</b></details>

<details>
<summary>How can we see the configuration settings of GIT installation?</ary><br><b>
A:  Configuration settings of GIT
We can use ‘git config --list’ command to print all the GIT configuration settings in GIT installation.
</b></details>

<details>
<summary> how will you write a message with commit command in GIT?</ary><br><b>
A:  Write a message with commit.
We call following command for commit with a message:
$/> git commit –m <message>
</b></details>

<details>
<summary>26)  What is stored inside a commit object in GIT?</ary><br><b>
A:  Inside a commit object.
   * SHA1 name
   * Files
   * Reference
SHA1 name:  A 40 character string to identify a commit.
Files:  List of files that represent the state of a project at a specific point of time.
Reference:  Any reference to parent commit objects.
</b></details>

<details>
<summary>27)  How many heads can you create in a GIT repository?</ary><br><b>
A:  There can be any number of heads in a repository.
By default there is one head known as HEAD in each repository in GIT.
</b></details>

<details>
<summary> 28)  Why do we create branches in GIT?</ary><br><b>
A:  If we are simultaneously working on multiple tasks, projects, defects or features, we need multiple branches.  In GIT, we can create a separate branch for each separate purpose.
Let say we are working on a feature, we create a feature branch for that.  In between we get a defect to work on then we create another branch for defect to work on then we create another branch for defect and work on it.  Once the defect work is done, we merge that branch and come back to work on feature branch again.
</b></details>

<details>
<summary> What are the different kinds of branches that can be created in GIT?</ary><br><b>
A:  Different kinds of branches in GIT
Feature branches:  These are used for developing a feature.
Release branches:  These are used for releasing code to production.
Hotfix branches:  These are used for releasing a hotfix to production for a defect or emergency fix.
</b></details>

<details>
<summary>30)  How will you create a new branch in GIT?</ary><br><b>
A:  Create a new branch
We use following command to create a new branch in GIT:
$/> git checkout –b <branchname>
</b></details>

<details>
<summary>31)  How will you add a new feature to the main branch?</ary><br><b>
A:  Add a new feature to the main
We do the development work on a feature branch that is created from master branch.  Once the development work is ready we use git merge command to merge it into master branch.
</b></details>

<details>
<summary>32)  What is a pull request in GIT?</ary><br><b>
A:  Pull request in GIT
A pull request in GIT is the list of changes that have been pushed to GIT repository.  Generally these changes are pushed in a feature branch or hotfix branch.
After pushing these changes we create a pull request that contains the changes between master and our feature branch.  This pull request is sent to reviewers for reviewing the code and then merging it into develop or release branch.
</b></details>

<details>
<summary> 33)  What is merge conflict in GIT?</ary><br><b>
A:  A merge conflict in GIT is the result of merging two commits.  Sometimes the commit to be merged and current commit have changes in same location.
In this scenario, GIT is not able to decide which change is more important.  Due to this GIT reports a merge conflict.  It means merge is not successful.  We may have to manually check and resolve the merge conflict.


GIT COMMANDS REFRESHER 4
We have captured popular GIT Commands for you to refresh your knowledge of GIT version control system.
Read about these commands to prepare well for GIT interview.  Test yourself on which GIT commands you already know about.
git merge
This command merges one or more branches into current branch.  It automatically creates a new commit if there is no merge conflict.
Eg. git merge myNewBranch
git reset
We use this command to reset the index and working directory to the state of last commit.
Eg. git reset --hard HEAD
git stash
Temporarily saves changes that you don’t want to commit immediately.  You can apply the changes later.
</b></details>

<details>
<summary>34)  How can we resolve a merge conflict in GIT?</ary><br><b>
A:  Resolve a merge conflict.
To resolve the merge conflict in a file, we edit the file and fix the conflicting change.
To resolve the merge conflict in a file, we edit the file and fix the conflicting change. In above example we can either keep five or six.
After editing the file we rungit add command followed by git commit command.  Since GIT is aware that it was merge conflict, it links this change to the correct commit.
</b></details>

<details>
<summary>35)  What command will you use to delete a branch? </ary><br><b>
A:  Delete a branch
git branch –d <branchname?
</b></details>

<details>
<summary>36)  What command will you use to delete a branch that has unmerged changes? </ary><br><b>
A:  Delete branch with unmerged changes.
Git branch –D <branchname>
</b></details>

<details>
<summary> 37)  What is the alternative command to merging in GIT?</ary><br><b>
A:  Alternative to merging
Another alternative of merging in GIT is rebasing.  It is done by git rebase command.
</b></details>

<details>
<summary>38)  What is Rebasing in GIT?</ary><br><b>
A:  Rebasing in GIT.
Rebasing is the process of moving a branch to a new base commit.
It is like rewriting the history of a branch.
In Rebasing, we move a branch from one commit to another.
By this we can maintain linear project history.
Once the commits are pushed to a public repository, it is not a good practice to use Rebasing.
</b></details>

<details>
<summary> 39)  What is the ‘Golden Rule of Rebasing’ in GIT? </ary><br><b>
A:  Golden Rule of Rebasing.
The golden rule of Rebasing is that we should never use git rebase on public branches.  If other people are using the same branch then they may get confused by looking at the changes in Master branch after GIT rebasing.
</b></details>

<details>
<summary>  Why do we use Interactive Rebasing in place of Auto Rebasing?</ary><br><b>
A:  Interactive Rebasing.
By using Interactive rebasing we can alter the commits before moving them to a new branch.
This is more powerful than an automated rebase.
It gives us complete control over the branch’s commit history.
</b></details>

<details>
<summary> 41)  What is the command for Rebasing in Git?</ary><br><b>
A:  Command for Rebasing
Git command for rebasing is:
Git rebase <new-commit>
</b></details>

<details>
<summary> What is the main difference between git clone and git remote? </ary><br><b>
A:  git clone vs. git remote
The main difference between git clone and git remote is that git is used to create a new local repository whereas git remote is used in an existing repository.
git remote adds a new reference to existing remote repository for tracking further changes.
Git clone creates a new local repository by copying another repository from a URL.
</b></details>

<details>
<summary> 43)  What is GIT version control?</ary><br><b>
A:  GIT version control helps us in managing the changes to source code over time by a software team.  It keeps track of all the changes in a special king of database.  If we make a mistake, we can go back in time and see previous changes to fix the mistake.
GIT version control helps the team in collaborating on developing a software and work efficiently.  Everyone can merge the changes with confidence that everything is tracked and remains intact in GIT version control.  Any bug introduced by a change can be discovered and reverted back by going back to a working version.
</b></details>

<details>
<summary> What GUI do you use of working on GIT?</ary><br><b>
A:  GUI for GIT
* GitHub Desktop.
* GITX-dev.
* Gitbox.
* Git-cola.
* Source Tree.
* Git Extentions.
* SmartGit.
</b></details>

<details>
<summary>45)  What is the use of git diff command in GIT?</ary><br><b>
A:  In GIT, git diff command is used to display the differences between 2 versions, or the differences between 2 versions, or between working directory and an index, or between index and most recent commit.
It can also display changes between two blob objects, or between two files on disk in GIT.
It helps in finding the changes that can be used for code review for a feature or bug fix.
GIT COMMANDS REFRESHER 5
We have captured popular GIT Commands for you to refresh your knowledge of GIT version control system.
Read about these commands to prepare well for GIT interview. Test yourself on which GIT commands you already know about.
git tag
We use this command to tag a specific commit with a simple, human readable handle that will never move.
Eg. git tag -a v5.0 -m 'version 5.0 tag'
git fetch
Use this command to fetch all the objects from remote repository that are not present in local repository.
Eg. git fetch origin
git pull
This command fetches the files from remote repository and merges it with local repository. This command is equal to git fetch and git merge sequence.
Eg. git pull origin
git push
We use it to push all the modified local objects to remote repository and advance the branch.
Eg. git push origin master
</b></details>
  
<details>
<summary> 46)  What is git rerere? </ary><br><b>
A:  git rerere
In GIT, rerere is a hidden feature.  The full form of rerere is “reuse recorded resolution”.
By using rerere, GIT remembers how we’ve resolved a hunk conflict.  The next time GIT sees the same conflict, it can automatically resolve it for us.
In GIT, rerere is a hidden feature.  The full form of rerere is “reuse recorded resolution”.
47)  What are the three most popular version of git diff command?
A:  Popular version of git diff is.
* git diff
* git diff –cached
* git diff HEAD
git diff:  It displays the differences between working directory and the index.
git diff –cached : It displays the differences between the index and the most recent commit.
Git diff HEAD:  It displays the differences between working directory and the most recent commit.
</b></details>

<details>
<summary>48)  What is the use of git status command?</ary><br><b>
A:  git status command
The paths that have differences between the index file and the current HEAD commit.
The paths that have differences between the working tree and the index file.
The paths in the working tree that are not tracked by GIT.
Among the above three items, first item is the one that we commit by using git commit command.  Item two and three can be committed only after running git add command.
</b></details>

<details>
<summary>  What is the main differemce between git diff and git status?</ary><br><b>
A:  git diff  vs.  git status
In GIT, git diff shows the differences between commits or between the working directory and index.
Whereas, git status command just shows the current status of working tree.
</b></details>

<details>
<summary>What is the use of git rm command in GIT?</ary><br><b>
A:  git rm command
In GIT, git rm command is used for removing a file from the working tree and the index.
We use git rm –r to recursively remove all files from a leading directory.
</b></details>

<details>
<summary>What is the command to apply a stash?</ary><br><b>
A:  Command to apply a stash
Sometimes we want to save our unfurnished work.  For this purpose we use git stash command.  Once we want to come back and continue working from the last place where we left, we use git stash apply command to bring back the unfinished work.
So the command to apply a stash is:
git stash apply or we can use:
git stash apply <stashname>
</b></details>

<details>
<summary>Why do we use git log command?
A:  git log command
We use git log command to search for specific commits in project history.
We can search git history by author, date or content.  It can even list the commits that were done x days before or after a specific date.
</b></details>

<details>
<summary> Why do we need git add command in GIT?</ary><br><b>
A:  git add command
GIT gives us a very good feature of staging our changes before commit.  To stage the changes we use git add command.  This adds our changes from working directory to the index.
When we are working on multiples tasks and we want to just commit the finished tasks, we first add finished changes to staging area and then commit it.  At this time git add command is very helpful.
</b></details>

<details>
<summary>Why do we use git reset command?</ary><br><b>
A:  git reset command
We use git reset command to reset current HEAD to a specific state.  By default it reverses the action of git add command.
So we use git reset command to undo the changes of git add command.
</b></details>

<details>
<summary>How can we convert git log messages to a different format?</ary><br><b>
A:  We can use pretty option in git log command for this.
Git log –pretty
This option converts the output format from default to other formats.  There are pre-built formats available for our use.
Git log –pretty=oneline
E.g. git log --pretty=format:”%h  - %an, %ar : %s”
bc71a6c – Smith John, 3 years ago : changed the version number
</b></details>

<details>
<summary>What are the programming languages in which git hooks can be written?</ary><br><b>
A:  programming languages for git hooks
* Perl.
* Shell script.
* Python.
* Other languages.
</b></details>

<details>
<summary>What is a commit message in GIT?</ary><br><b>
A:  commit message in GIT
A commit message is a comment that we add to a commit.
We can provide meaningful information about the reason for commit by using a commit message.
In most of the organizations, it is mandatory to put a commit message along with each commit.
Often, commit messages contain JIRA ticket, bug id, defect id etc. for a project.
GIT COMMANDS REFRESHER 6
We have captured popular GIT Commands for you to refresh your knowledge of GIT version control system.
Read about these commands to prepare well for GIT interview. Test yourself on which GIT commands you already know about.
git remote
It will show all the remote versions of repository.
Eg. git remote origin
git log
It is used to show a listing of commits on a branch with corresponding details.
git show
This command shows information about a git object.
</b></details>

<details>
<summary>>How GIT protects the code in a repository?</ary><br><b>
A:  GIT is made very secure since it contains the source code of an organization.  All the objects in a GIT repository are encrypted with a hashing algorithm called SHA1.
This algorithm is quite strong and fast.  It protects source code and other contents of repository against the possible malicious attacks.
This algorithm also maintains the integrity of GIT repository by protecting the change history against accidental changes.
</b></details>

<details>
<summary>How GIT provides flexibility in version control?</ary><br><b>
A:  How GIT provides flexibility 
GIT is very flexible version control system.  It supports non-linear development workflows.  It supports flows that are compatible with external protocols and existing systems.
GIT also supports both branching and tagging that promotes multiple kinds of workflows in version control.
</b></details>

<details>
<summary>How can we change a commit message in GIT?</ary><br><b>
A:  If a commit has not been pushed to GitHub, we can use git commit --ammend command to change the commit message.
When we push the commit, a new message appears on GitHub.
</b></details>

<details>
<summary>Why is it advisable to create an additional commit instead of amending an existing commit?</ary><br><b>
A:  Additional commit vs. amend
Git amend internally creates a new commit and replaces the old commit.  If commits have already been pushed to central repository, it should not be used to modify the previous commits.
</b></details>

<details>
<summary> How will you delete a branch in GIT?</ary><br><b>
A:  Delete a branch 
We use git branch –d <branchname> command to delete a branch in GIT.
In case a local branch is not fully merged, but we want to delete it by force, then we use git branch –D <branchname> command.
</b></details>

<details>
<summary> What is a bare repository in GIT?</ary><br><b>
A:  Bare repository in GIT
A repository created with git init –bare command is a bare repository in GIT.
The bare repository does not contain any working or checked out copy of source files.  A bare repository stores git revision history in the root folder of repository instead of in a .git subfolder.
It is mainly used for sharing and collaborating with other developers.
We can create a bare repository in which all developers can push their code.
There is no working tree in bare repository, since no one directly edits files in a bare repository.
</b></details>

<details>
<summary>How do we put a local repository on GitHub server?</ary><br><b>
A:  Put a local repository on GitHub
To put a local repository on GitHub, we first add all the files of working directory into local repository and commit the changes.  After that we call git remote add <Remote Repo URL> command to add the local repository on GitHub server.
Once it is added, we use git push command to push the contents of local repository to remote GitHub server.
</b></details>

<details>
<summary> How can we set up a Git repository to run code sanity checks and UAT tests just before a commit ?</ary><br><b>
A:  Run checks before commit
We can use git hooks for this kind of purpose.  We can write the code sanity checks in script.  This script can be called by pre-commit hook of the repository.
</b></details>

<details>
<summary> How can we revert a commit that was pushed earlier and it public now?</ary><br><b>
A:  We can use git revert command for this purpose.
Internally, git revert command creates a new commit with patches that reverse the changes done in previous commits.
The other optionis to checkout a previous commit version and then commit it as a new commit.
</b></details>

<details>
<summary>In GIT, how will you compress last n commits into a single commit?</ary><br><b>
A:  Compress last n commits
To compress last n commits a single commit, we use git rebase command.  This command compresses multiple commits and creates a new commit.  It overwrites the history of commits.
</b></details>

<details>
<summary> How will you switch from one branch to a new branch in GIT?</ary><br><b>
A:  Switch branch in GIT
In GIT, we can use:
Git checkout <new branchname>
Command to switch to a new branch.
</b></details>

<details>
<summary> How can we clean unwanted files from our working directory in GIT?</ary><br><b>
A:  GIT provides git clean command to recursiverly clean the working tree.  It removes the files that are not under version control in GIT.
If we use git clean –x, then ignored files are also removed.
GIT COMMANDS REFRESHER 7
We have captured popular GIT Commands for you to refresh your knowledge of GIT version control system.
Read about these commands to prepare well for GIT interview. Test yourself on which GIT commands you already know about.
git ls-tree
We use this command to show a tree object.  It includes mode and name of each item and SHA-1 value of blob or tree that it points to.
Eg. git ls-tree master^{tree} 100644 blob 6dd2c056e96b40d8a69df110062f5b2473d74eba HELLO
git cat-file
This command is used to view the type of an object through SHA-1 value.
Eg. git cat-file -t 6dd2c056e96b40d8a69df110062f5b2473d74eba blob
git grep
We use this command to search through trees of content for words and phrases. 
Eg. git grep "www.github.com" -- *.java
</b></details>

<details>
<summary>  What is the purpose of git tag command?</ary><br><b>
A:  git tag command
We use git tag command to add, delete, list or verify a tag object in GIT.
Tag objects created with options –a, -s, -u are also known as annotated tags.
Annotated tags are generally used for release.
</b></details>

<details>
<summary>What is cherry-pick in GIT?</ary><br><b>
A:  A git cherry-pick is a very useful feature in GIT.
By using this command we can selectively apply the changes done by existing commits.
In case we want to selectively release a feature, we can remove the unwanted files and apply only selected commits.
</b></details>

<details>
<summary>What is shortlog in GIT?</ary><br><b>
A:  A shortlog in GIT is a command that summarizes the git log output.
The output of git shortlog is in a format suitable for release announcements.
</b></details>

<details>
<summary>How can you find the names of files that were changed in a specific commit?</ary><br><b>
A:  Find names of files in commit
Every commit in GIT has a hash code.  This hash code uniquely represents the GIT commit object.
We can use git diff-tree command to list the name of files that were changed in a commit.
The command will be as follows:
git diff-tree –r <hash of commit>
By using –r flag, we just get the list of individual files.
</b></details>

<details>
<summary>How can we attach an automated script to run on the event of a new commit by push command?</ary><br><b>
A:  Attach an automated script.
In GIT we can use a hook to run an automated script on a specific event.  We can choose between pre-receive, update or post-receive hook and attach our script on any of these hooks.
GIT will automatically run the script on the event of any of these hooks.
</b></details>

<details>
<summary> What is the difference between pre-receive, update and post-receive hooks in GIT?</ary><br><b>
A:  pre-receive hooks
Pre-receive hook is invoked when a commit is pushed to a destination repository.  Any script attached to this hooks is executed before updating any reference.  This is mainly used to enforce development best practices and policies.        
Update hooks
Update hook is similar to pre-receive hook.  It is triggered just before any updates are done.  This hook is invoked once for every commit that is pushed to a destination repository.
post-receive hooks
Post-receive hook is invoked after the updates have been done and accepted by a destination repository.  This is mainly used to configure deployment scripts.  It can also invoke Continuous Integration (CI) systems and send notification emails to relevant parties of a repository.
</b></details>

<details>
<summary> Do we have to store scripts for GIT hooks within same repository?</ary><br><b>
A:  Store scripts for GIT hooks
A hook is local to a GIT repository.  But the script attached to a hook can be created either inside the hooks directory or it can be stored in a separate repository.  But we have to link the script to a hook in our local repository.
In this way we can maintain versions of a script in a separate repository, but use them in our repository where hooks are stored.[Tomcat interview questions.docx.txt](https://github.com/raghuk134/devops-interview-questions/files/6179923/Tomcat.interview.questions.docx.txt)

Also when we store scripts in a separate common repository,  we can reuse same scripts for different purposes in multiple repositories.
</b></details>

<details>
<summary>How can we determine the commit that is the source of a bug in GIT?</ary><br><b>
A:  Determine the commit
In GIT we can use git bisect command to find the commit that has introduced a bug in the system.
GIT bisect command internally uses binary search algorithm to find the commit that introduced a bug.
We first tell a bad commit that contains the bug and a good commit that was present before the bug was introduced.
Then git bisect picks a commit between those two endpoints and asks us whether the selected commit is good or bad.
It continues to narrow down the range until it discovers the exact commit responsible for introducing the bug.
</b></details>

<details>
<summary> How can we see differences between two commits in GIT ?</ary><br><b>
A:  See differences between two commits
We can use git diff command to see the differences between two commits.  The syntax for a simple git diff command to compare two commits is:
git diff <commit#1><commit#2>
</b></details>

<details>
<summary> What are the different ways to identify a commit in GIT ?</ary><br><b>
A:  Different ways to identify a commit
Each commit object in GIT has a unique hash.  This hash is a 40 characters checksum hash.
It is base on SHA1 hashing algorithm.  We can use a hash to uniquely identify a GIT commit.
GIT also provides support for creating an alias for a commit.  This alias is known as refs.  Every tag in GIT is a ref.  These refs can also be used to identify a commit.  Some of the special tags in GIT are HEAD, FETCH_HEAD and MERGE_HEAD.
</b></details>

<details>
<summary> When we run git branch <branchname>, how does GIT know the SHA-1 of the last commit?</ary><br><b>
A:  How does GIT know SHA-1
GIT uses the reference named HEAD for this purpose.  The HEAD file in GIT is a symbolic reference to the current branch we are working on.
A symbolic reference is not a normal reference that contains a SHA-1 value.
A symbolic reference contains a pointer to another reference.
When we open head file we see:
$ cat .git/HEAD
ref: refs/heads/master
If we run git checkout branchA, Git updates the file to look like this:
$ cat .git/HEAD
ref: refs/heads/branchA
</b></details>

<details>
<summary>What are the different types of Tags you can create in GIT ?</ary><br><b>
A:  Types of Tags
* Lightweight Tag
* Annotated Tag
Lightweight Tag:  A lightweight tag is a reference that never moves.  We can make a light weight tag by running a command similar to following:
$ git update-ref refs/tags/v1.0                                                                                                             dad0dab538c970e37ea1e769cbbde608743bc96d
Annotated Tag : An annotated tag is more complex object in GIT.  When we create an annotated tag, GIT creates a tag object and writes a reference to point to it rather than directly to the commit.  We can create an annotated tag as follows :
$ git tag –a v1.1                                                                                                                          1d410eabc13591cb07496601ebc7c059dd55bfe9 –m ‘test tag’82) 

<details>
<summary>How can we rename a remote repository?</ary><br><b>
A:  Rename a remote repository
We can use command git remote rename for changing the name of a remote repository.  This changes the short name associated with a remote repository in your local.
Command would look as follows:
%> git remote rename repoOldName repoNewName
GIT COMMANDS REFRESHER 8
We have captured popular GIT Commands for you to refresh your knowledge of GIT version control system.
Read about these commands to prepare well for GIT interview. Test yourself on which GIT commands you already know about.
git diff
Use this command to generate patch files or statistics of differences between paths or files in a git repository, or an index or the working directory.
Eg. git diff
gitk
This is a graphical Tcl/Tk based interface for local Git repository.
Eg. gitk
git instaweb
We can use it to run a web server with an interface in our local repository and automatically direct a web browser to it.
Eg. 
git instaweb --httpd=webrick 
git instaweb --stop
</b></details>

<details>
<summary> Some people use git checkout and some use git co for checkout.  How is that possible?</ary><br><b>
A:  git co for checkout
Can create aliases in GIT for commands by modifying the git configuration.
In case of calling git co instead of git checkout we can run following command:
git config --global alias.co checkout
</b></details>

<details>
<summary> How can we see the last commit on each of our branch in GIT?</ary><br><b>
A:  When we run git branch command, it lists all the branches in our local repository.  To see the latest commit associated with each branch,  we use option –v.
Exact command for this is as follows:
git branch –v
It lists branches as:
Issue72 82b676c fix issue                                                                                                             *master 7a97605 Merge branch ‘issue72’                                                                                testing 931ac34 add joe to developer list


</b></details>

<details>
<summary> Is origin a special branch in GIT?</ary><br><b>
A:  Is origin a special branch
No, origin is not a special branch in GIT.
Branch origin is similar to branch master.  It does not have any special meaning in GIT.
Master is the default name for a starting branch when we run git init command.
Origin is the default name for a remote when we run git clone command.  If we run git clone –o myOrigin instead, then we will have myOrigin/master as out default remote branch.
</b></details>

<details>
<summary>How can we configure GIT to not ask for password every time?</ary><br><b>
A:  When we use HTTPS URL to push, the GIT server asks for username and password for authentication.  It prompts us on the terminal for this information.
If we don’t want to type username/password with every single time push, we can set up a “credential cache”.
It is kept in memory for a few minutes.
We can set it by running:
git config --global credential.helper cache
</b></details>

<details>
<summary> What are the four major protocols used by GIT for data transfer?</ary><br><b>
A:  Four major porotcols used by GIT
* Local.
* HTTP.
* Secure Shell (SSH).
* Git.
</b></details>

<details>
<summary> What is GIT protocol?</ary><br><b>
A:  Git protocol is a mechanism for transferring data in GIT.  It is a special daemon.  It comes pre-packaged with GIT.  It listens on a dedicated port 9418.  It provides services similar to SSH protocol.
But Git protocol does not support any authentication.
So on plus side, this is a very fast network transfer protocol.  But it lacks authentication.
</b></details>

<details>
<summary> How can we work on a project where we do not have push access?</ary><br><b>
A:  In case of projects where we do not have push access, we can just fork the repository.
By running git fork command, GIT will create a personal copy of the repository in our namespace.  Once our work is done, we can create a pull request to merge our changes on the real project.
</b></details>

<details>
<summary> What is git grep?</ary><br><b>
A:  GIT is shipped along with a grep command that allows us to search for a string or regular expression in any committed tree or the working directory.
By default, it works on the files in your current working directory.
</b></details>

<details>
<summary> How can your recorder commits in GIT?</ary><br><b>
A:  Recorder commits in GIT
We can use git rebase command to reorder commits in GIT.  It can work interactively and you can also select the ordering of commits.
</b></details>

<details>
<summary>  How will you split a commit into multiple commits?</ary><br><b>
A:  To split a commit, we have to use git rebase command in interactive mode.  Once we reach the commit that needs to be split, we reset that commit and take the changes that have been reset.  Now we can create multiple commits our of that.
</b></details>

<details>
<summary> What is filter-branch in GIT?</ary><br><b>
A:  In GIT, filter-branch is another option to rewrite history.  It can scrub the entire history.  When we have large number of commits, we can use this tool.
It gives many options like removing the commit related changes to a specific file from history.  You can even set your name and email in the commit history by using filter-branch.
</b></details>

<details>
<summary> What are the three main trees maintained by GIT?</ary><br><b>
A:  Three main trees maintained by GIT.
HEAD:  This is the last commit snapshot.
Index:  This is the proposed next commit snapshot.
Working Directory:  This is the sandbox for doing changes.
</b></details>

<details>
<summary> What are the three main steps of working in GIT?</ary><br><b>
A:  Checkout the project from HEAD to Working Directory.
Stage the files from Working Directory to Index.
Commit the changes form Index to HEAD.
GIT COMMANDS REFRESHER 9
We have captured popular GIT Commands for you to refresh your knowledge of GIT version control system.
Read about these commands to prepare well for GIT interview. Test yourself on which GIT commands you already know about.
git archive
Use this command to create a tar or zip file including the contents of a single tree from local repository. 
Eg. git archive --format=zip master^ HELLO >filename.zip
git gc
We can use this command to do garbage collection for repository. It cleans unnecessary files. It optimizes the repository. It should be run occasionally.
Eg. git gc Counting objects: 10, done. Delta compression using up to 4 threads. Compressing objects: 100% (10/10), done. Writing objects: 100% (10/10), done. Total 10 (delta 1), reused 0 (delta 0)
git fsck
This command performs an integrity check of the Git file system, identifying corrupted objects.
Eg. git fsck
git prune
This command is used to remove objects that are no longer pointed to by any object in any reachable branch.
Eg. git prune
</b></details>

<details>
<summary> What are ours and theirs merge options in GIT?</ary><br><b>
A:  In GIT, we get two simple options for resolving merge conflicts:  ours and theirs 
These options tell the GIT which side to favor in merge conflicts.
In ours, we run a command like git merge –Xours branchA
As the name suggests, in ours, the changes in our branch are favored over the other branch during a merge conflict.
</b></details>

<details>
<summary> How can we ignore merge conflicts due to whitespace?</ary><br><b>
A:  Ignore merge conflicts due to whitespace
GIT provides an option ignore-space-change in git merge command to ignore the conflicts related to whitespaces.
The command to do so is as follows:
Git merge –Xignore-space-change   


<                                                                                    whitespace
</b></details>

<details>
<summary>What is git blame?</ary><br><b>
A:  In Git,  git blame is a very good option to find the person who changed a specific line.  When we call git blame on a file, It displays the commit and name of a person responsible for making change in that line.
</b></details>

<details>
<summary> What is a submodule in GIT ?</ary><br><b>
A:  submodule in GIT
In GIT, we can create sub modules inside a repository by using git submodule command.
By using submodule command, we can keep a Git repository as a subdirectory of another Git repository.
It allows us to keep our commits to submodule separate from the commits to main Git repository
</b></details>


<a name="git-advanced"></a>
#### :star: Advanced

<details>
<summary>Explain Git octopus merge</summary><br><b>

Probably good to mention that it's:

  * It's good for cases of merging more than one branch (and also the default of such use cases)
  * It's primarily meant for bundling topic branches together 

This is a great article about Octopus merge: http://www.freblogg.com/2016/12/git-octopus-merge.html
</b></details>

## Go

<a name="go-beginner"></a>

#### :baby: Beginner

<details>
<summary>What are some characteristics of the Go programming language?</summary><br><b>

  * Strong and static typing - the type of the variables can't be changed over time and they have to be defined at compile time
  * Simplicity 
  * Fast compile times
  * Built-in concurrency
  * Garbage collected
  * Platform independent
  * Compile to standalone binary - anything you need to run your app will be compiled into one binary. Very useful for version management in run-time. 

Go also has good community.
</b></details>

<details>
<summary>What is the difference between <code>var x int = 2</code> and <code>x := 2</code>?</summary><br><b>

The result is the same, a variable with the value 2.

With <code>var x int = 2</code> we are setting the variable type to integer while with <code>x := 2</code> we are letting Go figure out by itself the type.
</b></details>

<details>
<summary>True or False? In Go we can redeclare variables and once declared we must use it.</summary>

False. We can't redeclare variables but yes, we must used declared variables.
</b></details>

<details>
<summary>What libraries of Go have you used?</summary><br><b>

This should be answered based on your usage but some examples are:

  * fmt - formatted I/O
</b></details>

<details>
<summary>What is the problem with the following block of code? How to fix it?

```
func main() {
    var x float32 = 13.5
    var y int
    y = x
}
```
</summary><br><b>
</b></details>

<details>
<summary>The following block of code tries to convert the integer 101 to a string but instead we get "e". Why is that? How to fix it?

```
package main

import "fmt"

func main() {
    var x int = 101
    var y string
    y = string(x)
    fmt.Println(y)
}
```
</summary><br><b>

It looks what unicode value is set at 101 and uses it for converting the integer to a string.
If you want to get "101" you should use the package "strconv" and replace <code>y = string(x)</code> with <code>y = strconv.Itoa(x)</code>
</b></details>

<details>
<summary>What is wrong with the following code?:

```
package main

func main() {
    var x = 2
    var y = 3
    const someConst = x + y
}
```
</summary><br><b>
</b></details>

<details>
<summary>What will be the output of the following block of code?:

```
package main

import "fmt"

const (
	x = iota
	y = iota
)
const z = iota

func main() {
	fmt.Printf("%v\n", x)
	fmt.Printf("%v\n", y)
	fmt.Printf("%v\n", z)
}
```
</summary><br><b>
</b></details>

<details>
<summary>What _ is used for in Go?</summary><br><b>
</b></details>

<details>
<summary>What will be the output of the following block of code?:

```
package main

import "fmt"

const (
	_ = iota + 3
	x
)

func main() {
	fmt.Printf("%v\n", x)
}
```
</summary><br><b>
</b></details>

## Mongo

<a name="mongo-beginner"></a>
#### :baby: Beginner

<details>
<summary>What are the advantages of MongoDB? Or in other words, why choosing MongoDB and not other implementation of NoSQL?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between SQL and NoSQL?</summary><br><b>

The main difference is that SQL databases are structured (data is stored in the form of
tables with rows and columns - like an excel spreadsheet table) while NoSQL is 
unstructured, and the data storage can vary depending on how the NoSQL DB is set up, such
as key-value pair, document-oriented, etc.
</b></details>

<details>
<summary>In what scenarios would you prefer to use NoSQL/Mongo over SQL?</summary><br><b>

  * Heterogeneous data which changes often
  * Data consistency and integrity is not top priority
  * Best if the database needs to scale rapidly
</b></details>

<details>
<summary>What is a document? What is a collection?</summary><br><b>
</b></details>

<details>
<summary>What is an aggregator?</summary><br><b>
</b></details>

<details>
<summary>What is better?. Embedded documents or referenced?</summary><br><b>
</b></details>

##### Queries

<details>
<summary>Explain this query: <code>db.books.find({"name": /abc/})</code></summary><br><b>
</b></details>

<details>
<summary>Explain this query: <code>db.books.find().sort({x:1})</code></summary><br><b>
</b></details>

## OpenShift

<a name="openshift-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is OpenShift? Did you use it? If yes, how?</summary><br><b>
</b></details>

<details>
<summary>Can you explain the difference between OpenShift and Kubernetes?</summary><br><b>
</b></details>

<details>
<summary>Define Pods and explain what are stateful pods</summary><br><b>
</b></details>

<details>
<summary>What types of build strategies are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Explain what are labels and what they are used for</summary><br><b>
</b></details>

<details>
<summary>Explain what are annotations and how they are different from labels</summary><br><b>
</b></details>

<details>
<summary>Explain what is Downward API</summary><br><b>
</b></details>

## Shell Scripting

<a name="shell-scripting-beginner"></a>
#### :baby: Beginner

<details>
<summary>Tell me about your experience with shell scripting</summary><br><b>
</b></details>

<details>
<summary>What this line in scripts mean?: <code>#!/bin/bash</code></summary><br><b>
</b></details>

<details>
<summary>What do you tend to include in every script you write?</summary><br><b>

Few example:

  * Comments on how to run it and/or what it does
  * Adding "set -e" since I want the script to exit if a certain command failed 

You can have an entirely different answer. It's based only on your experience.
</b></details>

<details>
<summary>True or False?: when a certain command/line fails, the script, by default, will exit and will no keep running</summary><br><b>

Depends on the language and settings used.
When a script written in Bash fails to run a certain command it will keep running and will execute all other commands mentioned after the command which failed.
Most of the time we would actually want the opposite to happen. In order to make Bash exist when a specific command fails, use 'set -e' in your script.
</b></details>

<details>
<summary>Today we have tools and technologies like Ansible. Why would someone still use shell scripting?</summary><br><b>

  * Speed
  * The module we need doesn't exist
  * We are delivering the scripts to customers who don't have access to the public network and don't necessarily have Ansible installed on their systems.
</b></details>

<details>
<summary>Explain what would be the result of each command:

  * <code>echo $0</code>
  * <code>echo $?</code>
  * <code>echo $$</code>
  * <code>echo $@</code>
  * <code>echo $#</code></summary><br><b>
</b></details>

<details>
<summary>How do you debug shell scripts?</summary><br><b>

Answer depends on the language you are using for writing your scripts. If Bash is used for example then:

  * Adding -x to the script I'm running in Bash
  * Old good way of adding echo statements

If Python, then using pdb is very useful.
</b></details>

<details>
<summary>How do you get input from the user in shell scripts?</summary><br><b>

Using the keyword <code>read</code> so for example <code>read x</code> will wait for user input and will store it in the variable x.
</b></details>

<details>
<summary>Explain conditionals and how do you use them</summary><br><b>
</b></details>

<details>
<summary>What is a loop? What types of loops are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Explain <code>continue</code> and <code>break</code>. When do you use them if at all?</summary><br><b>
</b></details>

<details>
<summary>How to store the output of a command in a variable?</summary><br><b>
</b></details>

<details>
<summary>How do you check variable length?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between single and double quotes?</summary><br><b>
</b></details>

<details>
<summary>Write a script which will list the differences between two directories</summary><br><b>
</b></details>

<a name="shell-scripting-advanced"></a>
#### Advanced

<details>
<summary>Explain the following code:

<code>:(){ :|:& };:</code>

</summary><br><b>
</b></details>

<details>
<summary>Can you give an example to some Bash best practices?</summary><br><b>
</b></details>

<details>
<summary>What is the ternary operator? How do you use it in bash?</summary><br><b>

A short way of using if/else. An example:

[[ $a = 1 ]] && b="yes, equal" || b="nope"
</b></details>

<details>
<summary>What does the following code do and when would you use it?
	
<code>diff <(ls /tmp) <(ls /var/tmp)</code>

</summary><br>
It is called 'process substitution'. It provides a way to pass the output of a command to another command when using a pipe <code>|</code> is not possible. It can be used when a command does not support <code>STDIN</code> or you need the output of multiple commands. 
https://superuser.com/a/1060002/167769
</details>


## SQL

<a name="sql-beginner"></a>
#### :baby: Beginner

<details>
<summary>What does SQL stand for?</summary><br><b>

Structured Query Language

</b></details>

<details>
<summary>How is SQL Different from NoSQL</summary><br><b>

The main difference is that SQL databases are structured (data is stored in the form of
tables with rows and columns - like an excel spreadsheet table) while NoSQL is 
unstructured, and the data storage can vary depending on how the NoSQL DB is set up, such
as key-value pair, document-oriented, etc.
</b></details>

<details>
<summary>What does it mean when a database is ACID compliant?</summary><br>

ACID stands for Atomicity, Consistency, Isolation, Durability. In order to be ACID compliant, the database much meet each of the four criteria

**Atomicity** - When a change occurs to the database, it should either succeed or fail as a whole. 

For example, if you were to update a table, the update should completely execute. If it only partially executes, the 
update is considered failed as a whole, and will not go through - the DB will revert back to it's original
state before the update occurred. It should also be mentioned that Atomicity ensures that each 
transaction is completed as it's own stand alone "unit" - if any part fails, the whole statement fails.

**Consistency** - any change made to the database should bring it from one valid state into the next.

For example, if you make a change to the DB, it shouldn't corrupt it. Consistency is upheld by checks and constraints that
are pre-defined in the DB. For example, if you tried to change a value from a string to an int when the column
should be of datatype string, a consistent DB would not allow this transaction to go through, and the action would
not be executed

**Isolation** - this ensures that a database will never be seen "mid-update" - as multiple transactions are running at
the same time, it should still leave the DB in the same state as if the transactions were being run sequentially.

For example, let's say that 20 other people were making changes to the database at the same time. At the
time you executed your query, 15 of the 20 changes had gone through, but 5 were still in progress. You should
only see the 15 changes that had completed - you wouldn't see the database mid-update as the change goes through.

**Durability** - Once a change is committed, it will remain committed regardless of what happens
(power failure, system crash, etc.). This means that all completed transactions 
must be recorded in non-volatile memory. 

Note that SQL is by nature ACID compliant. Certain NoSQL DB's can be ACID compliant depending on 
how they operate, but as a general rule of thumb, NoSQL DB's are not considered ACID compliant
</details>

<details>
<summary>When is it best to use SQL? NoSQL?</summary><br><b>

SQL - Best used when data integrity is crucial. SQL is typically implemented with many
businesses and areas within the finance field due to it's ACID compliance.

NoSQL - Great if you need to scale things quickly. NoSQL was designed with web applications 
in mind, so it works great if you need to quickly spread the same information around to 
multiple servers

Additionally, since NoSQL does not adhere to the strict table with columns and rows structure
that Relational Databases require, you can store different data types together.
</b></details>

<details>
<summary>What is a Cartesian Product?</summary><br>

A Cartesian product is when all rows from the first table are joined to all rows in the second
table. This can be done implicitly by not defining a key to join, or explicitly by 
calling a CROSS JOIN on two tables, such as below:

Select * from customers **CROSS JOIN** orders;

Note that a Cartesian product can also be a bad thing - when performing a join
on two tables in which both do not have unique keys, this could cause the returned information
to be incorrect. 
</details>

##### SQL Specific Questions

For these questions, we will be using the Customers and Orders tables shown below:

**Customers**

Customer_ID | Customer_Name | Items_in_cart | Cash_spent_to_Date
------------ | ------------- | ------------- | -------------
100204 | John Smith | 0 | 20.00
100205 | Jane Smith | 3 | 40.00
100206 | Bobby Frank | 1 | 100.20

**ORDERS**

Customer_ID | Order_ID | Item | Price | Date_sold
------------ | ------------- | ------------- | ------------- | -------------
100206 | A123 | Rubber Ducky | 2.20 | 2019-09-18
100206 | A123 | Bubble Bath | 8.00 | 2019-09-18
100206 | Q987 | 80-Pack TP | 90.00 | 2019-09-20
100205 | Z001 | Cat Food - Tuna Fish | 10.00 | 2019-08-05
100205 | Z001 | Cat Food - Chicken | 10.00 | 2019-08-05
100205 | Z001 | Cat Food - Beef | 10.00 | 2019-08-05
100205 | Z001 | Cat Food - Kitty quesadilla | 10.00 | 2019-08-05
100204 | X202 | Coffee | 20.00 | 2019-04-29

<details>
<summary>How would I select all fields from this table?</summary><br><b>

Select * <br>
From Customers;
</b></details>

<details>
<summary>How many items are in John's cart?</summary><br><b>

Select Items_in_cart <br>
From Customers <br>
Where Customer_Name = "John Smith";
</b></details>

<details>
<summary>What is the sum of all the cash spent across all customers?</summary><br><b>

Select SUM(Cash_spent_to_Date) as SUM_CASH <br>
From Customers;
</b></details>

<details>
<summary>How many people have items in their cart?</summary><br><b>

Select count(1) as Number_of_People_w_items <br>
From Customers <br>
where Items_in_cart > 0;
</b></details>

<details>
<summary>How would you join the customer table to the order table?</summary><br><b>

You would join them on the unique key. In this case, the unique key is Customer_ID in
both the Customers table and Orders table
</b></details>

<details>
<summary>How would you show which customer ordered which items?</summary><br><b>

Select c.Customer_Name, o.Item <br>
From Customers c <br>
Left Join Orders o <br>
  On c.Customer_ID = o.Customer_ID;

</b></details>

<a name="sql-advanced"></a>
#### Advanced

<details>
<summary>Using a with statement, how would you show who ordered cat food, and the total amount of money spent?</summary><br><b>

with cat_food as ( <br>
Select Customer_ID, SUM(Price) as TOTAL_PRICE <br>
From Orders <br>
Where Item like "%Cat Food%" <br>
Group by Customer_ID <br>
) <br>
Select Customer_name, TOTAL_PRICE <br>
From Customers c <br>
Inner JOIN cat_food f <br>
  ON c.Customer_ID = f.Customer_ID <br>
where c.Customer_ID in (Select Customer_ID from cat_food);

Although this was a simple statement, the "with" clause really shines when 
a complex query needs to be run on a table before joining to another. With statements are nice, 
because you create a pseudo temp when running your query, instead of creating a whole new table.

The Sum of all the purchases of cat food weren't readily available, so we used a with statement to create
the pseudo table to retrieve the sum of the prices spent by each customer, then join the table normally.
</b></details>

## Azure

<a name="azure-beginner"></a>
#### :baby: Beginner

<details>
<summary>Explain Azure's architecture</summary><br><b>
</b></details>

<details>
<summary>Explain availability sets and availability zones</summary><br><b>
</b></details>

<details>
<summary>What is the Azure Resource Manager? Can you describe the format for ARM templates?</summary><br><b>
</b></details>

<details>
<summary>Explain Azure managed disks</summary><br><b>
</b></details>

## GCP

<a name="gcp-beginner"></a>
#### :baby: Beginner

<details>
<summary>Explain GCP's architecture</summary><br><b>
</b></details>

<details>
<summary>What are the main components and services of GCP?</summary><br><b>
</b></details>

<details>
<summary>What GCP management tools are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Tell me what do you know about GCP networking</summary><br><b>
</b></details>

## OpenStack

<a name="openstack-beginner"></a>
#### :baby: Beginner

<details>
<summary>Tell me about your experience with OpenStack. What do you think are the advantages and disadvantages of OpenStack?</summary><br><b>
</b></details>

<details>
<summary>What components/projects of OpenStack are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Can you tell me what each of the following components/projects is responsible for?:

  * Nova
  * Neutron
  * Cinder
  * Glance
  * Keystone</summary><br><b>
</b></details>

<details>
<summmary>Describe in detail how you bring up an instance with an IP you can reach from outside the cloud</summary><br><b>
</b></details>

<details>
<summary>You get a call from a customer saying: "I can ping my instance but can't connect (ssh) it". What might be the problem?</summary><br><b>
</b></details>

<details>
<summary>What types of networks OpenStack supports?</summary><br><b>
</b></details>

<details>
<summary>How do you debug OpenStack storage issues? (tools, logs, ...)</summary><br><b>
</b></details>

<details>
<summary>How do you debug OpenStack compute issues? (tools, logs, ...)</summary><br><b>
</b></details>

<details>
<summary>Are you familiar with TripleO? What benefits it has?</summary><br><b>
</b></details>

##### Networking

<details>
<summary>What is a provider network?</summary><br><b>
</b></details>

<details>
<summary>What components and services exist in L2 and L3?</summary><br><b>
</b></details>

<details>
<summary>What is the ML2 plug-in? Explain its architecture</summary><br><b>
</b></details>

<details>
<summary>What is the L2 agent? How it works and what is it responsible for?</summary><br><b>
</b></details>

<details>
<summary>What is the L3 agent? How it works and what is it responsible for?</summary><br><b>
</b></details>

<details>
<summary>Explain what the Metadata agent is responsible for</summary><br><b>
</b></details>

<details>
<summary>How do you debug OpenStack networking issues? (tools, logs, ...)</summary><br><b>
</b></details>

<a name="openstack-advanced"></a>
#### :baby: Advanced

##### Networking

<details>
<summary>Explain BGP dynamic routing</summary>
</b></details>

## Security

<a name="security-beginner"></a>
#### :baby: Beginner

<details>
<summary>Can you describe the DevSecOps core principals?</summary><br><b>
</b></details>

<details>
<summary>What DevOps security best practices are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>What security techniques are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>How do you manage passwords in different tools and platforms?</summary><br><b>
</b></details>

<details>
<summary>Explain the following:

  * Vulnerability
  * Exploits
  * Risk
  * Threat</summary><br><b>
</b></details>

<details>
<summary>What is XSS?</summary><br><b>
</b></details>

<details>
<summary>What is an SQL injection? How to manage it?</summary><br><b>
</b></details>

<details>
<summary>What is Certification Authority?</summary><br><b>
</b></details>

<details>
<summary>How do you identify and manage vulnerabilities?</summary><br><b>
</b></details>

<details>
<summary>Explain "Privilege Restriction"</summary><br><b>
</b></details>

<details>
<summary>How HTTPS is different from HTTP?</summary><br><b>
</b></details>

<details>
<summary>What types of firewalls are there?</summary><br><b>
</b></details>

<details>
<summary>What is DDoS attack? How do you deal with it?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between asynchronous and synchronous encryption?</summary><br><b>
</b></details>

<details>
<summary>Explain Man-in-the-middle attack</summary><br><b>
</b></details>

<details>
<summary>Explain CVE and CVSS</summary><br><b>
</b></details>

<details>
<summary>What is ARP Poisoning?</summary><br><b>
</b></details>

<details>
<summary>Describe how do you secure public repositories</summary>
</b></details>

<details>
<summary>How do cookies work?</summary><br><b>
</b></details>

<details>
<summary>Do you think open source project is more secured when compared to a proprietary software?</summary><br><b>
</b></details>

<details>
<summary>Explain OAuth</summary><br><b>
<a name="puppet-advanced"></a>
</b></details>

<details>
<summary>Explain "Format String Vulnerability"</summary><br><b>
</b></details>

<details>
<summary>Explain "Buffer Overflow"</summary><br><b>
</b></details>

<details>
<summary>Explain DMZ</summary><br><b>
</b></details>

<details>
<summary>Explain TLS</summary><br><b>
</b></details>

<details>
<summary>What is CSRF? How to handle CSRF?</summary><br><b>
</b></details>

<details>
<summary>Explain HTTP Header Injection vulnerability</summary><br><b>
</b></details>

<details>
<summary>What security sources are you using to keep updated on latest news?</summary><br><b>
</b></details>

<details>
<summary>What TCP and UDP vulnerabilities are you familiar with?</summary><br><b>
</b></details>

<details>
<summary>Do using VLANs contribute to network security?</summary><br><b>
</b></details>

<details>
<summary>What are some examples of security architecture requirements?</summary><br><b>
</b></details>

##### Containers

<details>
<summary>What security measures are you taking when dealing with containers?</summary><br><b>
</b></details>

<details>
<summary>Explain what is Docker Bench</summary><br><b>
</b></details>

<a name="security-advanced"></a>
#### :baby: Advanced

<details>
<summary>Explain MAC flooding attack</summary><br><b>
</b></details>

<details>
<summary>What is "Diffie-Hellman key exchange" and how does it work?</summary><br><b>
</b></details>

<details>
<summary>Explain "Forward Secrecy"</summary><br><b>
</b></details>

## Puppet

<a name="puppet-beginner"></a>
#### :baby: Beginner

<details>
<summary>What is Puppet? How it works?</summary><br><b>
</b></details>

<details>
<summary>Explain Puppet architecture</summary><br><b>
</b></details>

<details>
<summary>Can you compare Puppet to other configuration management tools? Why did you chose to use Puppet?</summary><br><b>
</b></details>

<details>
<summary>Explain the following:

  * Module
  * Manifest
  * Node</summary><br><b>
</b></details>

<details>
<summary>Explain Facter</summary><br><b>
</b></details>

<details>
<summary>What is MCollective?</summary><br><b>
</b></details>

<a name="puppet-advanced"></a>
#### :baby: Advanced

<details>
<summary>Do you have experience with writing modules? Which module have you created and for what?</summary><br><b>
</b></details>

<details>
<summary>Explain what is Hiera</summary><br><b>
</b></details>

## General

Although the following questions are not DevOps related, they are still quite common so it's better to prepare for them as well.

<details>
<summary>Tell us little bit about yourself</summary><br><b>
</b></details>

<details>
<summary>Tell me about your last big project/task you worked on</summary><br><b>
</b></details>

## Scenarios

Scenarios are questions which don't have verbal answer and require you one of the following:

  * Set up environments
  * Write scripts
  * Design and/or develop infrastructure projects

These questions usually given as an home task to the candidate and they can combine several topics together.
Below you can find several scenario questions:

* [Writing a Dockerfile and running a container](scenarios/write_dockerfile_run_container.md)
* [Elasticsearch & Kibana on AWS](scenarios/elk_kibana_aws.md)
* [Ansible, Minikube and Docker](scenarios/ansible_minikube_docker.md)
* [Cloud Slack bot](scenarios/cloud_slack_bot.md)
* [Writing Jenkins Scripts](scenarios/jenkins_scripts.md)
* [Writing Jenkins Pipelines](scenarios/jenkins_pipelines.md)


## Tomcat

<a name="tomcat beginner"></a>

<details>
<summary>1. What is Tomcat?</summary><br><b>
Tomcat is a Java Servlet container and web server from the Apache software foundation. It can be used as standalone or it can be used behind traditional web servers such as Apache httpd.
Recent versions of Tomcat can serve static content as fast as httpd. A web server uses the request/response message exchange pattern to serve web pages. Tomcat provides Servlet, JSP technologies and static content as well.
</b></details>

<details>
<summary>what is Apache Tomcat?</summary><br><b>
Apache Tomcat is an open-source web server and Servlet/JSP container developed by the Apache Software Foundation. Tomcat implements several Java EE specifications including Java Servlet, Java Server Pages (JSP), Java EL, and WebSocket, and provides a "pure Java" HTTP web server environment for Java code to run in.
</b></details>

<details>
<summary>Who is responsible of Tomcat?</summary><br><b>
The Apache Software Foundation. The Apache Software Foundation is an umbrella organization that looks after a number of Open Source projects.
Jakarta is the group name for the Java based projects of the Apache Software foundation.
Tomcat is a Web Server that handles server side Java (in the form of Servlets and JSPs), and it’s a part of the Apache Jakarta project group. Tomcat is the “reference” implementation of the Servlet and JSP standards – in other words, if it runs under Tomcat, it should run under any compliant Servlet / JSP container.
</b></details>

<details>
<summary> What do you know about Tomcat history?</summary><br><b>
Tomcat started off as a servlet reference implementation by James Duncan Davidson, a software architect at Sun Microsystems. He later helped make the project open source and played a key role in its donation by Sun Microsystems to the Apache Software Foundation. The Apache Ant software build automation tool was developed as a side-effect of the creation of Tomcat as an open source project.
</b></details>

<details>
<summary>Name some Tomcat features?</summary><br><b>
Tomcat 7.x implements the Servlet 3.0 and JSP 2.2 specifications. It requires Java version 1.6. Tomcat 8.x implements the Servlet 3.1 and JSP 2.4 Specifications. Tomcat 8.5.x is intended to replace 8.0.x and includes new features pulled forward from Tomcat 9.0.x. Tomcat 8.5 is designed to run on Java SE 7 and later.
</b></details>

<details>
<summary> Explain Directory Structure Of Tomcat?</summary><br><b>
Directory structure of Tomcat are:
bin - contain startup, shutdown, and other scripts (*.sh for UNIX and *.bat for Windows systems) and some jar files also there.
conf - Server configuration files (including server.xml) and related DTDs. The most important file in here is server.xml. It is the main configuration file for the container.
lib - contains JARs those are used by container and Servlet and JSP application programming interfaces (APIs).
logs - Log and output files.
webapps – deployed web applications reside in it .
work - Temporary working directories for web applications and mostly used during in JSP compilation where JSP is converted to a Java servlet.
temp - Directory used by the JVM for temporary files .
</b></details>

<details>
<summary>What is the Tomcat default port?</summary><br><b>
The default port for Tomcat is 8080. You can change the default port by editing the file server.xml under the conf folder in the Tomcat installed directory. Change the property Connector port=”8080″ to the desired port and restart Tomcat so the changes can take effect.
</b></details>

<details>
<summary> How to deploy War web applications in Tomcat?</summary><br><b>
You can drop the WAR file inside the webapps folder or use the Tomcat manager to deploy War files.
</b></details>

<details>
<summary> Can Tomcat use SSL?</summary><br><b>
Yes, you need to make additional configurations to make Tomcat use SSL. In resume you need to do these tasks
Generate Keystore
Add a conector in server.xml
Restart Tomcat
</b></details>

<details>
<summary> How do I override the default home page loaded by Tomcat?</summary><br><b>
Inside $TOMCAT_HOME/conf/web.xml there is a section called <welcome-file-list> and it looks like this:
welcome-file-list
1
	<welcome-file-list>
	2
	    <welcome-file>index.html</welcome-file>
	

3
	    <welcome-file>index.htm</welcome-file>
	4
	    <welcome-file>index.jsp</welcome-file>
	

5
	</welcome-file-list>
	The default servlet attempts to load the index.* files in the order listed. You may easily override the index.jsp file by creating an index.html file at $TOMCAT_HOME/webapps/ROOT.
</b></details>


<details>
<summary>What services are provided by Tomcat?</summary><br><b>
Tomcat server provides a host of services which are not provided by normal web servers like Apache Web Server. Those are:
Servlet Life cycle
Handle Web Requests
Database connection pooling
Clustering
High availability
</b></details>

<details>
<summary>Explain How Running Tomcat As A Windows Service Provides Benefits?</summary><br><b>
Running Tomcat as a windows service provides benefits like:
Automatic startup: It is crucial for environment where you may want to remotely re-start a system after maintenance
Server startup without active user login: Tomcat is run oftenly on blade servers that may not even have an active monitor attached to them. Windows services can be started without an active user
Security: Tomcat under window service enables you to run it under a special system account, which is protected from the rest of the user accounts
</b></details>


<details>
<summary>Explain what is Tomcat Valve?</summary><br><b>
A tomcat valve- a new technology is introduced with Tomcat 4 which enables you to link an instance of a Java class with a specific Catalina container.
</b></details>

<details>
<summary> Mention with how many valves does Tomcat configured with?</summary><br><b>
Four types of valves Tomcat is configured with
Access Log
Remote Address Filter
Remote Host Filter
Request Dumper
</b></details>

<details>
<summary>Explain how servlet life cycles?</summary><br><b>
The life-cycle of a typical servlet running on Tomcat
Tom-cat receives a request from a client through one of its connectors
For processing, this request Tomcat maps this request to appropriate
Once the request has been directed to the appropriate servlet, Tomcat verifies that servlet class has been loaded. If it is not than Tomcat wraps the servlet into Java Bytecode, that is executable by the JVM and forms an instance of the servlet
Tomcat initiates the servlet by calling its init The servlet contains code that is able to screen Tomcat configuration files and act accordingly, as well as declare any resources it might require
Once the servlet has been started, Tomcat can call the servlet’s service method to proceed the request
Tomcat and the servlet can co-ordinate or communicate through the use of listener classes during the servlet’s lifecycle, which tracks the servlet for a variety of state changes.
To remove the servlet, Tomcat calls the servlets destroy method.
</b></details>

<details>
<summary>Explain what is the purpose of NAT protocol?</summary><br><b>
The purpose of NAT protocol is to hide private IP address from public IP address and give a certain level of security to the organization.
</b></details>

<details>
<summary> What is a servlet container?</summary><br><b>
he servlet container is the component of a web server that interacts with Java servlets. The servlet container is responsible for managing the lifecycle of servlets, mapping a URL to a particular servlet and ensuring that the URL requester has the correct access-rights.
The servlet container handles requests to servlets, JavaServer Pages (JSP) files, and other types of files that include server-side code. The Web container creates servlet instances, loads and unloads servlets, creates and manages request and response objects, and performs other servlet-management tasks.
The servlet container implements the web component contract of the Java EE architecture, specifying a runtime environment for web components that includes security, concurrency, lifecycle management, transaction, deployment, and other services.
A servlet life cycle can be defined as the entire process from its creation till the destruction.
Life cycle steps followed by a servlet
The servlet receives a request from a client through one of its connectors then is initialized by calling the init() method.
The servlet calls service() method to process a client’s request and send the response.
The servlet is terminated by calling the destroy() method.
The servlet is garbage collected by the garbage collector of the JVM.
</b></details>

<details>
<summary> What is the server server.xml configuration file?</summary><br><b>
The server.xml file is Tomcat main configuration file, and it is responsible for specifying Tomcat configuration on startup.
</b></details>

<details>
<summary>What is web.xml configuration file?</summary><br><b>
The web.xml file is derived from the Servlet specification, and contains information used to deploy and configure the components of your web applications.
</b></details>

<details>
<summary>What is Tomcat-users.xml configuration file?</summary><br><b>
It is where the Tomcat users are defined and it is located in the conf folder of the Tomcat server root.
</b></details>

<details>
<summary> Where do you configure a database connection pool in Tomcat server?</summary><br><b>
The Configure pool is in the context.xml inside the conf folder of tomcat.
</b></details>

<details>
<summary> What is a connector and why it is used in Tomcat?</summary><br><b>
The Apache Tomcat Connectors project is a part of the Tomcat project and provides web server plug-ins to connect web servers with Tomcat and other back-ends.
The supported web servers are:
The Apache HTTP Server with a plugin named mod_jk.
Microsoft IIS with a plugin named ISAPI redirector.
The iPlanet Web Server with a plugin named NSAPI redirector.
In Tomcat, two types of connectors are used
HTTP Connectors: It has many attributes that can be changed to determine exactly how it works and access functions such as redirects and proxy forwarding
AJP Connectors: It works in the same manner as HTTP connectors, but they practice the AJP protocol in place of HTTP. AJP connectors are commonly implemented in Tomcat through the plug-in technology mod_jk.
</b></details>

<details>
<summary> What is the difference between Tomcat and an Application server?</summary><br><b>
Tomcat is a servlet container that supports servlets and the JSP technology. An Application server supports many other Java EE technologies.
</b></details>

<details>
<summary>What Application server is based on Tomcat ?</summary><br><b>
TomEE.
</b></details>

24.What is TomEE?</summary><br><b>
Apache TomEE (pronounced “Tommy”) is the Java Enterprise Edition of Apache Tomcat (Tomcat + Java EE = TomEE) that combines several Java enterprise projects including Apache OpenEJB, Apache OpenWebBeans, Apache OpenJPA, Apache MyFaces and others.
</b></details>

<details>
<summary>What is Jasper?</summary><br><b>
Jasper is Tomcat’s JSP Engine. Jasper parses JSP files to compile them into Java code as servlets. At runtime, Jasper detects changes to JSP files and recompiles them. Jasper is the Java Server pages handler in Tomcat; internally, it deals with any compiling that’s neccessary, and converts JSPs into Servlets for Catalina to handle.
</b></details>

<details>
<summary>What is Catalina ?</summary><br><b>
Catalina is Tomcat’s servlet container. Catalina implements specifications for servlet and JavaServer Pages. Catalina is the Java Engine (JRE / JVM) that’s built into Tomcat and provides an environment in which Servlets can be run.
Catalina consists of configuration files are
policy
properties
properties
xml
xml
Tomcat-users.xml
Xml
</b></details>

<details>
<summary> What is Coyote ?</summary><br><b>
Coyote is a Connector component for Tomcat that supports the HTTP 1.1 protocol as a web server. This allows Catalina, nominally a Java Servlet or JSP container, to also act as a plain web server that serves local files as HTTP documents.
Coyote listens for incoming connections to the server on a specific TCP port and forwards the request to the Tomcat Engine to process the request and send back a response to the requesting client.
Coyote is the HTTP connector that’s built into Tomcat and provides Tomcat with an interface that browsers can connect to.
</b></details>

<details>
<summary>What is a Tomcat cluster ?</summary><br><b>
This component is used to manage large applications. It is used for load balancing and can be achieved through many techniques. Apache Tomcat cluster is used to manage more traffic. It provides multiples instances of the Tomcat server with its content balanced between these instances.
</b></details>

<details>
<summary>What is a Tomcat High availability ?</summary><br><b>
A high-availability feature has been added to facilitate the scheduling of system upgrades without affecting the live environment. This is done by dispatching live traffic requests to a temporary server on a different port while the main server is upgraded on the main port. It is very useful in handling user requests on high-traffic web applications.
</b></details>

<details>
<summary>What is the server?</summary><br><b>
A Server element represents the entire Catalina servlet container. Therefore, it must be the single outermost element in the conf/server.xml configuration file. Its attributes represent the characteristics of the servlet container as a whole.
</b></details>

<details>
<summary> What is the Service?</summary><br><b>
A Service element represents the combination of one or more Connector components that share a single Engine component for processing incoming requests. One or more Service elements may be nested inside a Server element.
</b></details>

<details>
<summary> What is the engine ?</summary><br><b>
The Engine element represents the entire request processing machinery associated with a particular Catalina Service. It receives and processes all requests from one or more Connectors, and returns the completed response to the Connector for ultimate transmission back to the client.
Exactly one Engine element MUST be nested inside a Service element, following all of the corresponding Connector elements associated with this Service.
</b></details>

<details>
<summary>What is the host ?</summary><br><b>
The Host element represents a virtual host, which is an association of a network name for a server.
</b></details>

<details>
<summary>What is the Connector ?</summary><br><b>
A Connector represents an end point in which requests are received.
</b></details>

<details>
<summary>What is the Context ?</summary><br><b>
The Context element represents a web application, which is run within a particular virtual host. Each web application is based on a Web Application Archive (WAR) file, or a corresponding directory containing the corresponding unpacked contents, as described in the Servlet Specification.
</b></details>

<details>
<summary>what is a difference between Apache and Nginx web server?</summary><br><b>
Both are categorized as a Web Server and here are some of the main differences.
Nginx is event-based web server where Apache is process based
Nginx is known for better performance than Apache
Apache supports wide range of OS where Nginx doesn’t support OpenVMS and IBMi
Apache has large number of modules integration with backend application server where Nginx is still catching up
Nginx is lightweight and capturing the market share rapidly. If you are new to Nginx, then you may be interested in checking out my articles on Nginx.
</b></details>

<details>
<summary>How to disable trace HTTP request?</summary><br><b>
Add the following in httpd.conf file and restart the instance
TraceEnable off
</b></details>

<details>
<summary>What are the HTTP error codes?</summary><br><b>
Informational – 1XX
Success – 2XX
Redirection – 3XX
Client Error – 4XX
Server Error – 5XX
Success Response
200 – OK: The standard HTTP response for successful HTTP requests. In another way, the web server will return 200 when requested content is served successfully.
202 – Accepted: The server has accepted your request and yet to process them.
206 – Partial Content: Only partial content is delivered due to the range header sent by a client like wget.
Redirection Response
301 – Moved permanently: Your requested page has been moved permanently to a new location. This instructs search engine bot to crawl new location.
302 – Moved temporarily: Your requested is served from a different location but that is temporary arrangement. This instructs search engine bot to crawl the original location.
305 – Use proxy: The requested resource is only available through a proxy. That means you must use a relevant proxy to get the requested page successfully.
304 – Not modified: Usually when cached page is served when a resource has not been modified.
Client Error
400 – Bad request: The server is confused what you have requested. Probably bad syntax or trying to include characters in URI which server doesn’t understand.
401 – Not authorised: The requested page is protected and requires authentication. You must login in order to get the requested page successfully.
403 – Forbidden: You have to try to access which you don’t have permission. This, not necessary resource is protected by the password; it could also be when files/folder permission doesn’t allow viewing the requested page.
404 – Not found: Probably the most famous one – your requested page is not found on the server. You are trying to access something, which doesn’t exist.
405 – Method not allowed: You are requesting a page with the wrong method. For example, you are doing GET on POST data. Or you are trying the method, which is disabled for example – TRACE, PUT, DELETE.
408 – Request timeout: The server timed out waiting for the request
411 – Length required: Your request doesn’t meet the length of its content, which is required by the requested resource.
Server Error
500 – Internal server error: A very generic error when server encountered an error due to various reasons. Logs must be examined to see why the server has responded internal error.
502 – Bad gateway: The server was acting as a gateway or proxy and received an invalid response from the upstream server like Tomcat, WebSphere.
503 – Service unavailable: The server can’t serve your request. This could be due to either server is too busy in other stuff or almost dead.
</b></details>

<details>
<summary>How can Apache act a Proxy Server?</summary><br><b>
You can use a mod_proxy module to use as a proxy server. The mod_proxy module can be used to connect to the backend server like Tomcat, WebLogic, WebSphere, etc.
</b></details>

<details>
<summary>What’s a difference between Apache Web Server and Apache Tomcat?</summary><br><b>
Apache Web is HTTP server to serve static contents where Tomcat is servlet container to deploy JSP files.
You can always integrate Apache HTTP with Tomcat, however, based on the requirement you need to choose either one. If you need proper web server, then Apache HTTP else Tomcat for JSP-Servlet Container.
</b></details>


<details>
<summary>Where can be set roles,username and password?</summary><br><b>
/conf/tomcat-users.xml
</b></details>

<details>
<summary>What Is Default Session Time Out In Tomcat?</summary><br><b>
The default session timeout 30 minutes in tomcat and can change in $TOMCAT_HOME/conf/web.xml via modify below entry.
</b></details>

<details>
<summary>What are the configuratiopn file in tomcat server?</summary><br><b>
Tomacat XML Configuration Files:
server.xml(TOMCAT-HOME/conf/server.xml)
web.xml (TOMCAT-HOME/conf/web.xml)
tomcat-users.xml (TOMCAT-HOME/conf/tomcat-users.xml)
</b></details>

<details>
<summary> How to start and shutdown to tomcat server?</summary><br><b>
Tomacat XML Configuration Files:
There are two .sh file in cd $CATALINA_HOME/bin dir or in /usr/share/tomcat7/bin/
./startup.sh
./shutdown.sh
</b></details>

<details>
<summary> What are the HTTP requests?</summary><br><b>
GET: The GET method is used to retrieve information from the given server using a given URI. Requests using GET should only retrieve data and should have no other effect on the data.


HEAD: Same as GET, but it transfers the status line and the header section only.


POST: A POST request is used to send data to the server, for example, customer information, file upload, etc. using HTML forms.


PUT: Replaces all the current representations of the target resource with the uploaded content.


DELETE: Removes all the current representations of the target resource given by URI.


CONNECT: Establishes a tunnel to the server identified by a given URI.


OPTIONS: Describe the communication options for the target resource.


TRACE: Performs a message loop back test along with the path to the target resource.
</b></details>
