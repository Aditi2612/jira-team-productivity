# Jira Issue Tracking & Team Productivity Analysis

Analyzed Jira issue data from open-source Apache projects to evaluate:
- 🧑‍💻 Team workload and issue assignment
- ⏱️ Average resolution time
- 📈 Sprint velocity (issues resolved/month)
- 🐞 Bottlenecks by issue status, type, and priority

## Key Insights
- Certain team members were overloaded with 10x more issues than others.
- Some high-priority bugs took longer to resolve than medium-priority ones.
- Sprint velocity fluctuated heavily around deadlines.

## Tech Stack
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Dataset: [Apache Jira Issues on Kaggle](https://www.kaggle.com/datasets)

## 📊 Key Visuals

### 🔹 Top 10 Assignees by Issue Count
![Assignees](assignee_issue_count.png)

### 🔹 Avg. Resolution Time by Assignee (≤ 1000 days)
![Avg Resolution by Assignee](avg_resolution_per_assignee.png)

### 🔹 Sprint Velocity – Issues Resolved per Month
![Sprint Velocity](sprint_velocity.png)

### 🔹 Avg. Resolution Time by Issue Type
![Issue Type](issue_type_resolution.png)

### 🔹 Avg. Resolution Time by Priority
![Priority](priority_resolution.png)

