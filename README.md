# Challenges table with the related tools and explanations

| **Identified Challenges** | **How it can be improved** | **Suitable Tools** | **Explanation** |
|--------|----------|--------|---------|
| Frequent outages |	Implement monitoring and alerting to proactively detect issues and prevent outages. |	Kubernetes, Prometheus, Grafana	| Kubernetes can manage containerized applications, Prometheus can monitor system health, and Grafana can visualize performance metrics. These tools combined help in detecting and resolving issues quickly. |
| Slow response time |	Optimize system performance, analyze and improve code and database performance. |	Docker, Jenkins |	**Docker** allows lightweight containerization   **Jenkins** supports continuous integration for automated builds and testing, enabling faster code deployment and improvements in response time. |
| Lack of defined SLOs (Service Level Objectives) |	Define and establish specific SLOs for services, and set up monitoring and measurement. |	SLO, SLI, Prometheus, Grafana |	**SLIs (Service Level Indicators)** provide measurable indicators for SLOs (Service Level Objectives). **Prometheus** and **Grafana** can monitor and visualize these indicators to ensure services meet defined objectives. |
| High toil (manual, repetitive tasks) |	Automate repetitive tasks using infrastructure as code (IaC) and automation tools. |	Git, Jenkins, SRE |	**Git** version control helps manage IaC, **Jenkins** facilitates continuous integration and delivery, and **SRE** principles guide the reduction of manual toil through automation and error reduction. |
| Ineffective incident response |	Implement a structured incident management process and conduct post-incident analysis for improvements. |	SRE, Git, Jenkins |	**SRE** principles provide a structured approach to incident response. **Git** and **Jenkins** help manage code changes and automated deployments. |
| Lack of transparency and post-incident knowledge sharing | Conduct systematic post-incident reviews and document findings to facilitate knowledge sharing and prevent recurring incidents. |	Git, SRE |	**Git** allows version control for postmortem documentation. **SRE** principles encourage learning from incidents for better future response. |
| Absence of automatic recovery mechanisms |	Implement backup, resilience, and automatic recovery mechanisms to minimize downtime. |	Kubernetes, Docker, Jenkins, SRE |	**Kubernetes** and **Docker** facilitate containerization and portability, **Jenkins** supports automated recovery procedures, and **SRE** principles guide designing resilient systems. |


# The table outlining the topics of the presentation, the corresponding tools used, resons for their use, and how they were used

| **Presentation Topic** |	**Tools and Concepts** |	**Reasons for Use** |	**How They Were Used** |
|--------|----------|--------|---------|
| **1. Pipeline and Deployment** |	Jenkins, Docker |	Automate CI/CD, speed improvements |	**Jenkins** used for continuous integration and deployment, **Docker** for containerizing applications |
| **2. Automation** |	Kubernetes, Jenkins |	Streamline deployment and management |	**Kubernetes** used for container orchestration and automated scaling of services, **Jenkins** can be configured to automatically run test scripts and parse the results. |
| **3. Monitoring** |	Grafana, Prometheus |	Visualize and alert on system metrics |	**Grafana** used to create dashboards for monitoring, **Prometheus** for time-series data collection |
| **4. Documentation** |	GitHub |	Centralized documentation repository |	**GitHub** used to store and organize documentation |
| **5. Incident Management** |	Jira, Postmortem process |	Track incidents and postmortems |	**Jira** used for issue tracking and incident management, **postmortem process** defined for handling incidents  |
| **6.Project Planning, Bug Tracking** |	Jira, OpenProject, ServiceNow |	Manage project tasks and bug tracking |	**Jira** and **OpenProject/ServiceNow** used for project management and bug tracking |
| **7. Capacity and Performance** |	Load testing tools |	Test system capacity and performance |	Load testing tools used to simulate increased load and identify bottlenecks |
| **8. SLOs and SLIs** |	SLI and SLO definitions |	Define and measure service objectives |	**SLIs** defined to measure system performance, **SLOs** set to meet client needs|
| **9. Toil** | Automation tools |	Automate repetitive tasks |	**Automation tools** used to eliminate manual toil and increase system efficiency |
