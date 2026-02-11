# Devops-task-13
 DevOps Internship - Task 13  
 Monitoring Basics using Prometheus & Grafana
 Overview

In this task, I set up a basic monitoring system using Prometheus and Grafana. The goal was to understand how system monitoring works and how we can visualize server performance metrics like CPU, memory, and disk usage.

Tools Used

- Prometheus
- Node Exporter
- Grafana
- Ubuntu Linux



 What I Did

1. Installed Node Exporter to collect system metrics such as CPU, memory, and disk usage.
2. Installed Prometheus and configured it to scrape metrics from Node Exporter.
3. Verified that Prometheus was successfully collecting data.
4. Installed Grafana and connected it to Prometheus as a data source.
5. Imported the Node Exporter dashboard (ID: 1860) in Grafana.
6. Monitored CPU, memory, and disk usage in real time.
7. Simulated CPU load using the stress command to observe changes in graphs.
8. Took a screenshot of the monitoring dashboard as proof of completion.



### Key Learnings

- Understood how Prometheus follows a pull-based model.
- Learned how metrics are collected and stored as time-series data.
- Understood the difference between Prometheus (data collection) and Grafana (visualization).
- Learned the basics of system observability.
- Gained hands-on experience in monitoring server performance.



 Dashboard Screenshot

The screenshot of the Grafana monitoring dashboard is added inside the `screenshots` folder.


### Final Outcome

After completing this task, I now understand how monitoring works in a real DevOps environment and how tools like Prometheus and Grafana help in tracking system health.

