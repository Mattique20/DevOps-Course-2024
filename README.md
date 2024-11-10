## DevOps-Course-2024
This repository contains all the work required for the DevOps Assignment. 
-  A guide to your learning and contribution to this field
-  Summaries of recent blogs.
-  A sample repo that was used online with applied DevOps.
-  Expanded guidance based on existing knowledge

##  A Guide to Learning and Contribution:
---
### Gaining and sharing Fundamental knowledge of DevOps
During the course, we weren't just told to consume knowledge via the instructor's lectures. We were instructed to show initiative, research topics that we found interesting, and write articles about them. This not only helped us gain better insight but also helped future students looking to improve their DevOps skills.
Some of the articles are listed below.
- [Building and Optimizing Beowulf Clusters with Docker on Windows](https://medium.com/@mattique02/building-and-optimizing-beowulf-clusters-with-docker-on-windows-1b1e83532c27)
- [An Introduction to Kubernetes: Simplifying Container Orchestration](https://medium.com/@mattique02/an-introduction-to-kubernetes-simplifying-container-orchestration-d7cd9f3a4c7f)
---
### Growing on the fundamentals 
The next logical step was to build on the knowledge gained so far and move on to more complex topics. Such skills and topics are mentioned below. 

<h3>1. Kubernetes</h3>
<p>I’ve developed a comprehensive understanding of <strong>Kubernetes</strong> as an essential tool for orchestrating containerized applications. With Kubernetes, I can efficiently manage complex applications by automating deployment, scaling, and operational tasks across clusters. By leveraging features like <em>Deployments</em>, <em>Services</em>, and <em>ConfigMaps</em>, I can ensure application consistency and resilience even as workloads scale up or down. Kubernetes’ self-healing capabilities are invaluable, automatically handling issues by restarting containers or redistributing workloads across nodes. Additionally, I’ve explored <em>Helm</em> for managing Kubernetes applications as packages, which simplifies deployments and allows for easy version control of application states. Overall, Kubernetes has empowered me to handle applications at scale with a focus on reliability and high availability.</p>
<h3>2. Knative</h3>
<p>Working with <strong>Knative</strong> has broadened my perspective on serverless computing within Kubernetes environments. Knative streamlines serverless deployment, allowing applications to automatically scale to zero when not in use, saving resources while still being responsive to demand. This has been particularly useful for building event-driven applications where resource usage fluctuates. Knative’s <em>Serving</em> and <em>Eventing</em> components allow me to create serverless services that react to events and scale based on incoming traffic. By simplifying the serverless model on Kubernetes, Knative enables me to focus on application logic rather than infrastructure concerns, making it easier to deploy and manage applications that need to scale dynamically based on user demand or event triggers.</p>
<h3>3. Terraform</h3> 
<p><strong>Terraform</strong> introduced me to the world of Infrastructure as Code (IaC), allowing me to define, deploy, and manage infrastructure through code. With Terraform’s declarative syntax, I can specify the desired state of infrastructure, making provisioning consistent and repeatable. This approach not only improves version control for infrastructure setups but also enables collaboration by sharing infrastructure configurations with teams. My experience with Terraform extends to managing cloud resources across multiple providers like AWS, Azure, and Google Cloud. By utilizing <em>modules</em> and <em>variables</em>, I can create reusable and scalable infrastructure templates that simplify the setup of complex, multi-environment configurations. Additionally, Terraform’s <em>state management</em> and <em>plan and apply</em> capabilities provide visibility into changes before they happen, reducing the risk of unintended modifications and improving infrastructure reliability.</p> 
<h3>4. Docker and Containerization</h3> 
<p>Docker has been foundational to my understanding of containerization, offering a standardized way to package and deploy applications in isolated environments. By creating Docker images, I can bundle applications with all their dependencies, ensuring that they run consistently across different environments, from development to production. This consistency has been crucial for multi-environment deployments and has reduced the “works on my machine” issues significantly. Combining Docker with Kubernetes allows me to take containerized applications to the next level, leveraging Kubernetes for orchestration, scaling, and high availability. I’ve also used Docker Compose to define and run multi-container Docker applications locally, providing an efficient way to develop and test complex microservices before deploying them. The portability and flexibility that Docker provides make it an invaluable tool for modern application development.</p> 
<h3>5. GitHub Actions</h3> 
<p><strong>GitHub Actions</strong> has transformed my approach to automation, enabling me to build robust CI/CD pipelines that streamline various workflows. By creating custom workflows for testing, building, and deploying code, I’ve minimized manual intervention and improved consistency across deployment cycles. GitHub Actions supports conditional workflows, allowing me to trigger actions based on specific events such as commits, pull requests, or tag releases. This has been instrumental in automating testing and deployment across multiple branches, ensuring that code quality is maintained without delay. I’ve also integrated GitHub Actions with third-party services, providing notifications and analytics for pipeline runs. Using Actions has allowed me to automate processes, maintain a high standard of quality control, and deliver features faster by reducing the overhead associated with manual deployment and testing.</p> 
<h2>Challenges and Solutions</h2> 
<p>Throughout my DevOps journey, I’ve encountered various challenges that tested my problem-solving skills. Setting up Kubernetes was initially daunting, with steep learning curves around managing clusters, configuring network policies, and ensuring secure access. Through persistent troubleshooting and researching best practices, I was able to grasp Kubernetes' underlying principles and leverage them to their full potential. Containerization also posed challenges, especially when managing dependencies across different environments. By adopting multi-stage builds and optimizing image sizes, I was able to mitigate issues with resource usage and runtime performance. Lastly, setting up CI/CD pipelines required balancing flexibility with stability, but over time, I learned to configure pipelines that are resilient, scalable, and maintainable. These experiences strengthened my skills in configuration management, debugging, and process optimization, which are now invaluable to my DevOps toolkit.</p>

---

<h3>Future Goals</h3>
<p>Looking ahead, I am eager to continue advancing my DevOps expertise by achieving several key goals:</p> 
  <ul> 
    <li>Pursuing certifications like the <em>Kubernetes and Cloud Native Associate (KCNA)</em> to formally validate my skills and deepen my knowledge of cloud-native technologies.</li> 
    <li>Focusing on advanced topics, such as monitoring and observability, which are critical for maintaining highly available applications, as well as exploring service mesh integrations and cloud-native security to ensure secure, reliable systems.</li> 
    <li>Contributing to open-source projects related to DevOps to further hone my skills, collaborate with the community, and share my knowledge with others.</li> 
  </ul>
  
---

<h3>Additional Resources</h3>
<p>If you’re interested in learning more about DevOps, here are some helpful resources that I frequently refer to:</p>
  <ul> 
    <li><a href="https://kubernetes.io/docs/">Kubernetes Documentation</a> - A comprehensive guide to Kubernetes, covering everything from basic concepts to advanced deployment scenarios.</li> 
    <li><a href="https://developer.hashicorp.com/terraform/docs">Terraform Documentation</a> - Essential reading for anyone looking to understand Infrastructure as Code and use Terraform effectively.</li> 
    <li><a href="https://docs.github.com/en/actions">GitHub Actions Documentation</a> - Detailed documentation that covers every aspect of creating, managing, and optimizing CI/CD workflows on GitHub.</li> <li><a href="https://docs.docker.com/">Docker Documentation</a> - The definitive resource for understanding Docker, containerization, and building multi-container applications.</li> 
  </ul>

  
## Summary of the blogs
### [Building and Optimizing Beowulf Clusters with Docker on Windows](https://medium.com/@mattique02/building-and-optimizing-beowulf-clusters-with-docker-on-windows-1b1e83532c27)
In today’s tech landscape, high-performance computing (HPC) is increasingly necessary for tasks like AI model training and big data analysis. Beowulf clusters, which link multiple computers to function as a single computing system, provide a scalable, efficient solution for these computational needs. This blog post explores how Docker simplifies the process of creating and managing Beowulf clusters on Windows.

**The Beowulf Cluster Concept:** Beowulf clusters distribute complex tasks across multiple nodes, achieving faster computation through parallel processing. Each node, connected via high-speed networks, executes subtasks simultaneously, making it ideal for large or time-consuming tasks.

**Synergy between Docker and Beowulf Clusters:** Docker enhances Beowulf clusters by packaging required software into Docker images, making deployment and maintenance easier. Its portability allows containers to be transferred between machines, improving cluster flexibility. Docker’s lightweight nature means higher processing power with less overhead, and its isolation feature ensures stable, predictable node operations. Scaling Dockerized clusters is also straightforward, as containers can be easily added or removed based on computational needs.

**Building a Beowulf Cluster on Windows:** The guide uses the Windows Subsystem for Linux (WSL) to create a Linux environment on Windows for Docker and the cluster setup.

**Conclusion:** Dockerized Beowulf clusters present a powerful yet accessible HPC solution. By combining distributed computing with Docker’s strengths, complex computational problems can be tackled more effectively and efficiently.

---
### [An Introduction to Kubernetes: Simplifying Container Orchestration](https://medium.com/@mattique02/an-introduction-to-kubernetes-simplifying-container-orchestration-d7cd9f3a4c7f)
In today’s shift from monolithic to microservices-based applications, Kubernetes has emerged as a key tool for container orchestration. Developed by Google, Kubernetes simplifies the deployment and management of containerized applications, automating scaling and self-healing.

**What is Kubernetes?**  
Kubernetes is an open-source platform that automates the deployment, scaling, and management of containerized applications, making it ideal for handling microservices architectures.

**Architecture Overview:**  
Kubernetes uses a distributed architecture with a Master Node and multiple Worker Nodes, designed for scalability, resilience, and automation. The Master Node manages scheduling, monitoring, and maintaining the desired state of applications through core components like the API Server, Scheduler, and Controller Manager. Worker Nodes run applications within Pods, managed by Kubelet and Kube-proxy, which handle pod functionality and networking.

**Container Resource Monitoring:**  
Kubernetes offers tools like the Metrics Server to monitor CPU, memory, and other resources, ensuring efficient resource usage. This system allows Kubernetes to allocate resources dynamically based on demand, preventing both bottlenecks and resource wastage. Real-time monitoring also enables Kubernetes to autoscale applications based on traffic and workload.

**Personalized Resource Management:**  
Through YAML configurations, Kubernetes allows developers to set resource requests and limits for each container, optimizing resource allocation. This customization helps ensure applications use resources effectively without exceeding defined limits.

**Conclusion:**  
Kubernetes has revolutionized container orchestration, enabling seamless deployment and management of microservices with automated resource allocation and scaling. Its distributed architecture and advanced resource monitoring make it essential for modern, cloud-native applications, providing programmers and organizations with a powerful tool to enhance application efficiency, flexibility, and scalability.

---
## Sample repo from the internet and applying DevOps tooling
### FTP Deploy Action
#### Deploys a GitHub project to a FTP server using GitHub actions
The main purpose of the repository is to demonstrate and allow for easy-to-use deployment of projects to FTP servers using GitHub Actions.
**Project Repository:** [FTP Deploy Action](https://github.com/SamKirkland/FTP-Deploy-Action)

--- 
### Requirements
- You must have ftp access to your server. If your host allows or requires ssh please use my [web-deploy](https://github.com/SamKirkland/web-deploy) action
- Some web hosts change the default port (21), check with your host for your port number

---

### Setup Steps
1. Select the repository you want to add the action to
2. Select the `Actions` tab
3. Select `Blank workflow file` or `Set up a workflow yourself`, if you don't see these options manually create a yaml file `Your_Project/.github/workflows/main.yml`
4. Paste the example above into your yaml file and save
5. Now you need to add a key to the `secrets` section in your project. To add a `secret` go to the `Settings` tab in your project then select `Secrets`. Add a new `Secret` for `password`
6. Update your yaml file settings
7. If you appreciate this github action give it a :star: or show off with one of the [badges below](#badge).

---
This will now allow you to launch projects safely and securely onto an FTP server using GitHub Actions.

---

## My Resume 
You can view my Resume by using the link below:

[Resume](https://github.com/Mattique20/DevOps-Course-2024/blob/main/Mohammad_Attique_Resume.pdf)

