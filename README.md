# aws-sre-monitoring-project
# AWS SRE Monitoring Project - Serverless Hello App

Simple serverless API built with **AWS Lambda + API Gateway + CloudWatch** to practice core SRE principles.

## Project Overview
- Built a production-like serverless HTTP API
- Implemented observability using CloudWatch Metrics and Logs
- Created custom dashboard for key SLIs
- Configured alerting based on SLOs
- Practiced incident simulation and blameless postmortems

## Architecture
- **Compute**: AWS Lambda (Python 3.12)
- **API**: API Gateway (REST)
- **Monitoring**: CloudWatch Metrics + Logs + Alarms
- **Observability**: Custom dashboard showing Invocations, Errors, Duration, and Error Rate

## SRE Practices Demonstrated
- Defined **SLIs** (Success Rate, Latency)
- Defined **SLO**: 99.5% successful requests with p95 latency < 500ms
- Set up proactive alerting on error rate
- Simulated failures and analyzed impact
- Wrote blameless postmortems

## Screenshots
(Upload these 4 images to your repo)
1. Lambda function working
<img width="1912" height="874" alt="image" src="https://github.com/user-attachments/assets/059708c0-1880-4a5f-a523-060253943e85" />

2. CloudWatch Dashboard
 <img width="1905" height="698" alt="image" src="https://github.com/user-attachments/assets/a3399eac-59e7-4199-b270-b1cfb24fc4bb" />

4. CloudWatch Alarm configuration
   <img width="1908" height="721" alt="image" src="https://github.com/user-attachments/assets/83f5f82f-8feb-4746-86b8-1a8268caff79" />

6. Error simulation + alert triggering

## Lessons Learned
- Importance of correct Lambda handler configuration
- Value of structured logging and metrics
- How to translate reliability requirements into alerts and dashboards
