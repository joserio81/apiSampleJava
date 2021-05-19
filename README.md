**Description of the best practices you would implement to improve application observability. What would you do to enable quick and easy debug of the application? What would you propose to measure and ensure SLA, SLOs are accomplished?**
To improve application observability, I would implement:
1. ELK stack
2. Istio service mesh to monitor the Kubernetes cluster networking
3. Prometheus/ Grafana

to measure and ensure SLA:
I would implement a 'devops docker' with running scripts monitoring the system, combined with Pagerduty to provide reliable notifications, automatic escalations, on-call scheduling, and other functionality to help teams detect and fix infrastructure problems quickly. SLOs 99.5% of requests will be completed in 5ms
