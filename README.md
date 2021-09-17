# Designing-an-AWS-Cloud-Solution-Architecture-for-a-Medical-Company
In this project it is assumed that a cloud architecture has to be designed using cloud best practices for a medical company since they are moving their entire on-premises infrastructure to AWS cloud. However, we only design and create the architecture diagram.
The description and requirements of the company is as follows - 

A Medical Company is a startup software as a service (SaaS) company. It has built an online medical social networking and diagnosis assistance application for users in APAC, the US, and Europe.

The application connects patients and doctors to: 
Allow online appointments, remote consultation, remote diagnosis, electronic prescription transfer, and payment services.
Allow customers to upload documents and images. Text is extracted from documents, and images are converted into multiple formats.

The application has not yet been launched publicly.

The customer has provided this information on their current environment. A Medical Company:
- Deployed it’s current development and test infrastructure with a server hosting company
- Uses Microsoft Windows servers to host their web and application tiers with Microsoft SQL Server Standard Edition backend databases
- The application launch date is coming soon and they expect many users to start using the application
- Believes it would be best to use cloud technologies to support its rapid growth
- Thinks the new cloud platform could host the development, test, and production environments

The current architecture has three tiers: a web tier, a database tier, and an application tier. They are configured as follows:
- Web Tier
- Two physical servers (Two CPUs / 4-GB memory)
- Microsoft Windows 2016 Base with Internet Information Services (IIS)
- High Availability Proxy load balancer used to balance traffic between the web servers
- Application Tier
- Two physical servers (Four CPUs / 16-GB memory)
- Microsoft Windows 2016 Base with Internet Information Services (IIS)
- High Availability Proxy load balancer used to balance traffic between app servers
- Database Tier
- One physical server (Eight CPUs / 32-GB memory / 5-TB storage)
- SQL Server Standard Edition with Microsoft Windows 2016 Base
- DBAs access and manage the database, but no RDMBS or advanced configuration is required.

The cloud design solution for the above requirements can be found on the Cloud Solution Design report file.




