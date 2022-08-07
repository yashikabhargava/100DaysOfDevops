Yesterday we learned that -

 >DevOps is the combination of cultural philosophies, practices and tools that increases an organization's ability to deliver applications and services at high velocity.

But wait, what on earth does that mean and how does it work in practice?

Since it's not specific enough so naturally, different companies started implementing DevOps in different ways. Hence, the actual implementation of DevOps looked pretty different from company to company but, since companies started adopting it. It gradually got a more concrete form with some of the common patterns across many companies. One of these patterns was that DevOps evolved in an actual role called a DevOps Engineer.

Where either - 
- Developers are doing DevOps as a job next to development or Operations is doing it.
- Or someone is doing it exclusively as their only job.

Now the main question is how to become a DevOps Engineer.

<br>

## DevOps in Practice 


### Tools and concepts one needs to learn as a DevOps Engineer -
<br>

- **Concepts of Software Development -** As a DevOps Engineer, you are not Going to build an application but you need to understand the concept of -
   * how developers work 
   * which git workflow they are using
   * how the application is configured
   * concepts of automated testing and so on.

<br>

- **Operating System and Linux basics -** Now that application needs to be deployed on a server so that eventually users can access it. Hence we need some kind of infrastructure, and you as DevOps Engineer might be responsible for preparing the infrastructure to run the application. Since most servers run on the Linux Operating system, Hence you need -
   * Basic understanding of Linux
   * to be comfortable using CLI
   * Shell Commands
   * Understanding Linux file system
   * Understanding of server management

<br>

- **Networking and Security -** Also need to have a basic understanding of Networking and Security -
   * Firewall, Proxy Servers
   * Load Balancer
   * HTTP/HTTPS
   * IP, DNS Name Resolution

   However to draw a line between IT Operations and DevOps one does not have to have advanced Networking and security skills.

<br>

- **Containers -** Nowadays as containers have become the new Standard for software packaging models. This means you need to generally understand the concept of -
   * Virtualization & containers
   * managing containerized applications on a server
   * Docker as it is one of the most popular container technology

   <br>



   ## Responsibility of a DevOps Engineer -
   So now on one side, we have Developers who are creating new features and bug fixes and on the other side, we have infrastructure or servers which are managed and configured to run the application.

   but the question is how to get these features and bug fixes from the development team to the operation team to make them available to the end users.

   So how do we release the new application versions?

   That's the main task and responsibility of the DevOps Engineer, and with DevOps, the question is not just how to do this in any possible way but how we do this continuously and in an efficient, fast and automated way. Therefore we need to learn how to -
    * Build Automation & CI/CD pipelines

<br>

- **Infrastructure as a Service -** Nowadays many companies are using virtual infrastructure on the cloud instead of creating and managing their physical infrastructure these are infrastructure as service platforms like AWS, Google Cloud, Asure etc, you need to learn at least one of those.

<br>

- **Container Orchestration -** Now our application will run as a container and containers need to be managed. for smaller applications, docker-compose is enough but if you have a lot of containers, you need a more powerful Container Orchestration tool most powerful of which is Kubernetes. So you need to understand -
  * How Kubernetes work  
  * How to administer and manage the cluster
  * How to deploy the application in it

<br>

- **Monitoring -** One of your responsibility as a DevOps Engineer may be to set up monitoring for your running application, the underlying Kubernetes cluster and the servers on which the cluster is running to track performance and discover problems.

- **Infrastructure as Code -** In our project we will need the same deployment environment multiple times for Production, testing and development. Creating infrastructure for one environment already takes a lot of time and is very error-prone. So, we don't want to do it manually multiple times. Since we want to automate as much as possible.

   Now, this can be done using the combination of two types of Infrastructure as code tools -
    * Infrastructure provisioning tools like Terraform
    * Configuration management tools like Ansible, CHEF etc

   So you as a DevOps engineer should now one of these tools to make your work more efficient as well as to make your environment more transparent so that you know exactly in which state it is so that it's easy to replicate & recover.

In addition to all the above things you also need to learn -
- one Scripting language as you will be working closely with developers and system administrators
- Version control to manage your code  

<br>

## Resource 
[What is DevOps? - TechWorld with Nana](https://youtu.be/0yWAtQ6wYNM)

















