# Interview

**Tell me about yourself**

Hi, my name is Sunidhi Pandey, and I have cummulative 4 plus years of experience in the IT industry and relevent experinece in  DevOps .field is 3 years. My journey began at Hastree Technologies as Devops and QA.  
Currently, I’m working as a Software Engineer at WhizHack Technologies, where my focus is on automation and application deployment. Here, I’ve deepened my experience with tools like GitHub Actions, Docker, Kubernetes, as well as bash scripting and working in Linux environments.
Over the years, I’ve developed a strong foundation in cloud infrastructure, CI/CD pipelines, and system automation. I'm passionate about solving problems, improving deployment efficiency, and working on scalable cloud solutions.

***Roles & Responsibilities***


In my current role as a DevOps Engineer, my responsibilities are mainly focused around cloud infrastructure management, CI/CD automation, and application deployment and support.

1) Cloud Platform Management:
I’m responsible for building and managing cloud infrastructure using platforms like GCP and AWS. This includes setting up and configuring VPCs, virtual machines, and firewall rules to ensure secure and scalable environments. I also manage users and permissions through IAM policies and handle private container registries for storing and accessing Docker images securely. These tasks are essential to ensure that our infrastructure is reliable, secure, and well-organized.

2) CI/CD Pipeline Automation:
I design and implement CI/CD pipelines using GitHub Actions, which helps our teams to automate code testing, build, and deployment. I also actively look for repetitive or manual tasks and automate them to save time and reduce the chances of human error. This has helped speed up our development cycles and improve consistency in deployments.

3) Deployment Management:
I manage deployments across four environments — dev, QA, staging, and production — for over 5 products and 15+ services. We use Docker and Kubernetes for containerized deployments. I ensure deployments are smooth and consistent across all environments, and that updates are delivered without downtime or service impact.

4) Troubleshooting & Support:
I also handle production issue troubleshooting. This includes analyzing logs, identifying root causes, and fixing issues quickly to minimize downtime. This responsibility is critical for maintaining application reliability and ensuring smooth user experiences.

****How do you start your day as a DevOps Engineer?****

 I typically begin my day by:

1)  Checking Pending Tickets or Tasks:
  I review my assigned tickets in Jira or the task board in teams shift app and plan my work for the day — whether it’s infrastructure changes, automation tasks, deployment requests, or troubleshooting issues.

 2) Checking Monitoring Dashboards and Alerts:
I first check system monitoring tools and alert channels — like email, Slack, or ELK dashboards — to ensure that all services are running smoothly and there are no critical issues in production or other environments.

3) Daily Stand-up Meeting:
If there’s a daily stand-up or team sync meeting, I join to align with developers, QA, or other team members on the current tasks, priorities, and any blockers.


**HAVE YOU EVEN DONE WRONG IN PRODUCTION ENVIRONMENT AND HOW IS YOU APPROUCH TO SLOVE THE PRODUCTION RELATED ISSUES**

Yes, I’ve faced a production issue during one of our routine release activities — and I believe how you respond to such issues really defines your capability as a DevOps Engineer.

In one case, during a Kubernetes release, I accidentally added a whitespace in the database name while updating the configuration. When the deployment happened, the DB pod failed to connect, and the application couldn’t establish a connection.

In the first attempt, I checked the logs and saw the error message saying that the database named "xyz" does not exist. At first glance, it looked correct, but because of the trailing whitespace in the DB name, the system treated it as a different, non-existent database.

During the second review, I noticed the extra whitespace in the config file. I immediately corrected the value and re-ran the GitHub Actions pipeline, which resolved the issue and brought the service back up.

To prevent this in the future, I enhanced the GitHub Actions workflow by adding a dropdown menu using workflow_dispatch inputs. Now, when users trigger the release workflow, they can select the correct DB name from a predefined list, instead of typing it manually. This simple change has helped us avoid manual input errors and made the release process more reliable.


