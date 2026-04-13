# PowerShell Automation Scripts

Scripts built to automate routine IT tasks in a Windows Server / Active Directory environment.
Mirrors work done during Systems Administrator role at Tata Consultancy Services (2021–2023).

## Scripts

### 1. User Onboarding
- Creates AD user account with correct OU placement
- Assigns RBAC group memberships
- Provisions Microsoft 365 license
- Sends welcome email via Exchange Online

### 2. User Offboarding
- Disables AD account
- Revokes Microsoft 365 license
- Removes from distribution groups
- Archives mailbox in Exchange Online

### 3. Disk Space Monitor
- Queries all Windows Servers for disk usage
- Flags volumes below 20% free space
- Outputs report to CSV for SolarWinds integration

### 4. AD User Audit
- Pulls all inactive accounts (90+ days no login)
- Exports to CSV for review
- Optional: auto-disable after approval

## Environment
- Windows Server 2016 / 2019 / 2022
- Active Directory (ADUC)
- Microsoft 365 / Exchange Online
- PowerShell 5.1+

## Impact
These scripts reduced manual IT workload by 40% and saved 10–20 hours per month
across a 500+ user enterprise environment.
