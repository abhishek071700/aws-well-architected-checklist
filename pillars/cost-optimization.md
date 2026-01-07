# Cost Optimization Pillar

## Objective
Design workloads that deliver required business outcomes at the lowest possible cost.

## Common Issues Seen in AWS Accounts
- EC2 instances running continuously with low utilization
- Unused EBS volumes, snapshots, or Elastic IPs
- No tagging strategy for cost visibility
- Lack of periodic cost reviews

## Key Review Questions
- Are resources right-sized based on actual usage?
- Are cost allocation tags applied consistently?
- Are Savings Plans or Reserved Instances evaluated?
- Is unused infrastructure identified and removed regularly?

## Improvement Approaches
- Review spend using AWS Cost Explorer
- Analyze CloudWatch metrics before right-sizing
- Use auto scaling or scheduling for non-production workloads
- Apply Savings Plans only after usage stabilizes

## Architecture Trade-offs
Reducing cost can impact performance or availability. Decisions should align with business criticality, not just pricing.
