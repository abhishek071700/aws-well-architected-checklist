# Cost Optimization Pillar

## Objective
Help AWS environments deliver required business value with minimal cost.

## Common Issues Observed
- EC2 instances running with low utilization  
- Idle or orphaned storage volumes  
- Lack of cost allocation tags for tracking  
- No regular cost review cadence

## Key Review Questions
- Are resources right-sized based on usage data?
- Are cost allocation tags applied consistently?
- Are Savings Plans or Reserved Instances evaluated?
- Are unused or idle resources identified and removed?

## Improvement Approaches
- Use AWS Cost Explorer reports to understand spend
- Rightsize instances based on CloudWatch utilization
- Use autoscaling and instance scheduling for non-prod workloads
- Evaluate Savings Plans / RIs if long-term

## High-Value Notes
Cost optimization is not one-time — it’s ongoing. Balance cost vs performance vs availability.
