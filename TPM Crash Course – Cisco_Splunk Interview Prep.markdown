# 🚀 TPM Crash Course – Cisco/Splunk Interview Prep (Francisco Gomez)

---

## 🔁 1. Software Development Lifecycle (SDLC)
- **Phases**: Requirements → Design → Development → Testing → Deployment → Maintenance
- **Models**: 
  - **Waterfall**: Sequential, best for fixed requirements (e.g., regulated industries).
  - **Agile**: Iterative, emphasizes flexibility and collaboration.
  - **DevOps**: Continuous integration and delivery for rapid, reliable releases.
- **TPM Role**: Align cross-functional teams, track milestones, resolve blockers, and ensure traceability from requirements to delivery.

✅ **TPM Speak**:  
“I bridge gaps between engineering, product, and stakeholders, ensuring requirements are clear, sprints are on track, and deployments meet SLAs.”

📚 [Atlassian SDLC Overview](https://www.atlassian.com/continuous-delivery/software-development-lifecycle)

---

## 🌀 2. Agile / Scrum / Kanban
- **Scrum**: Fixed-length sprints (1-4 weeks), roles (Product Owner, Scrum Master, Dev Team), ceremonies (standup, sprint planning, demo, retrospective).
- **Kanban**: Visual workflow with Work-in-Progress (WIP) limits, ideal for continuous delivery.
- **Waterfall**: Linear approach, suitable for projects with stable requirements.

✅ **TPM Speak**:  
“I tailor frameworks to project needs—Scrum for feature-driven teams, Kanban for maintenance workflows, or hybrid models for complex programs.”

📚 [Agile vs Waterfall – Atlassian](https://www.atlassian.com/agile/agile-vs-waterfall)  
📹 [Scrum in 10 Minutes – YouTube](https://www.youtube.com/watch?v=XfvQWnRgxG0)

---

## 🐍 3. Python for TPMs
- **Use Cases**: Automate repetitive tasks (e.g., log parsing, report generation), query APIs, process data.
- **Key Concepts**: Variables, loops, conditionals, functions, error handling, libraries (e.g., pandas, requests).

```python
import pandas as pd
# Example: Filter failed test cases from a report
df = pd.read_csv('test_report.csv')
failed_tests = df[df['Status'] == 'Failed']
print(failed_tests[['Test_ID', 'Error_Message']])
```

✅ **TPM Speak**:  
“I leverage Python to streamline operations, like automating build log analysis or generating KPI dashboards, saving teams hours weekly.”

📚 [Python Cheat Sheet](https://www.pythoncheatsheet.org/)  
📹 [Python for PMs – YouTube](https://www.youtube.com/watch?v=2i2CSf7AIhw)

---

## ☁️ 4. Cloud Platforms (AWS, Azure, GCP)

| Capability        | AWS                     | Azure                    | GCP                     |
|-------------------|-------------------------|--------------------------|-------------------------|
| Compute           | EC2, Lambda             | Virtual Machines, Azure Functions | Compute Engine, Cloud Functions |
| Storage           | S3, EBS                 | Blob Storage, Disk Storage | Cloud Storage, Persistent Disk |
| IAM               | IAM, Cognito            | Azure AD, RBAC           | IAM, Identity Platform   |
| Containers        | EKS, ECS                | AKS                      | GKE                     |

✅ **TPM Speak**:  
“I’ve coordinated cloud migrations, mapping services across AWS, Azure, and GCP to meet scalability and compliance needs while optimizing costs.”

📹 [Cloud Comparison – YouTube](https://www.youtube.com/watch?v=0fZHT2rEd2k)  
📚 [AWS Overview](https://aws.amazon.com/what-is-aws/)  
📚 [Azure Overview](https://azure.microsoft.com/en-us/overview/what-is-azure/)  
📚 [GCP Overview](https://cloud.google.com/docs/overview)

---

## ☸️ 5. Kubernetes + Terraform + CI/CD
- **Kubernetes**: Orchestrates containers; key concepts: Pods, Deployments, Services, Ingress.
- **Terraform**: Infrastructure as Code (IaC) for provisioning cloud resources declaratively.
- **CI/CD**: Automates build, test, and deployment; tools include GitHub Actions, Jenkins, GitLab CI.

✅ **TPM Speak**:  
“I’ve overseen CI/CD pipeline optimizations, using Terraform for consistent environments and Kubernetes for high-availability deployments.”

📹 [Kubernetes in 10 Minutes – YouTube](https://www.youtube.com/watch?v=YzngpEA1kwY)  
📚 [Terraform Introduction – HashiCorp](https://www.hashicorp.com/resources/what-is-terraform)

---

## 🧠 6. Program Management Best Practices
- **Risk Management**: Proactively identify risks, assign owners, and track mitigation plans.
- **Stakeholder Communication**: Tailor updates—executives get high-level KPIs, engineers get actionable priorities.
- **Tools**: Jira (task tracking), Confluence (documentation), Power BI (dashboards), Excel (RAG reports).

✅ **TPM Speak**:  
“I drive program success with clear communication, risk forecasting, and data-driven status reports, keeping teams aligned and stakeholders informed.”

📚 [Project Management Guide – Smartsheet](https://www.smartsheet.com/content/project-management-guide)

---

## 📊 7. Splunk (Bonus)
- **Purpose**: Centralized platform for log aggregation, monitoring, and analytics.
- **Use Cases**: Security incident detection, performance monitoring, troubleshooting.
- **Benefit**: Accelerates root-cause analysis and reduces Mean Time to Resolution (MTTR).

✅ **TPM Speak**:  
“I’ve collaborated with teams using Splunk for observability, ensuring real-time insights inform debugging and post-incident reviews.”

📚 [What is Splunk?](https://www.splunk.com/en_us/data-insider/what-is-splunk.html)  
📹 [Splunk Basics – YouTube](https://www.youtube.com/watch?v=1L7uCnF44wY)

---

## 🧾 Final Tips
- **STAR Method**: Structure behavioral answers (Situation, Task, Action, Result) to showcase impact.
- **Demonstrate Versatility**: Highlight technical depth, leadership, and cross-functional collaboration.
- **Prepare Questions**: Ask about team challenges, tech stack, or program goals to show engagement.

🎯 **Good luck, Francisco! You’re ready to ace this!** 💪🔥