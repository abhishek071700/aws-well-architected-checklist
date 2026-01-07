# Security Pillar

## Objective
Protect data, systems, and assets by implementing strong security controls and risk management practices.

## Common Issues Seen in AWS Accounts
- Overly permissive IAM roles and policies
- Lack of MFA on root and privileged accounts
- Security groups open to wide IP ranges
- No centralized logging or monitoring

## Key Review Questions
- Is IAM following least-privilege principles?
- Is MFA enabled for root and critical users?
- Are security groups and NACLs tightly scoped?
- Are logs enabled for visibility and audit?

## Improvement Approaches
- Use IAM roles instead of long-term credentials
- Enable MFA for root and privileged access
- Restrict inbound access using security groups
- Enable logging using CloudTrail and CloudWatch

## Architecture Trade-offs
Stronger security controls may add operational overhead, but they significantly reduce risk and blast radius.
