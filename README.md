# MYSE Autoscaling Framework

MYSE (Make Your Service Elastic) is a proactive autoscaling framework for distributed services.
Specifically, MYSE enables automatic horizontal scaling by monitoring input requests patterns and the service times delivered by the replicated service, MYSE learns over time through Artificial Neural Networks (ANN) how input load and service times vary, and produces estimations to enable early decisions about reconfiguration. A queuing model M/M/S of the replicated service is used to compute the expected response time given the current configuration (number of replicas) and the distributions of both input requests and service times.

Get the full paper at: https://pdfs.semanticscholar.org/81ce/33746af45149b395e5ac57e8c4110f117b4b.pdf
