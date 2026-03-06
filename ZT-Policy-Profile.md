# 1. ZTA Component Definitions

## Policy Engine (PE):
The Policy Engine is the decision-making component in a Zero Trust Architecture. It evaluates signals such as user identity, device security, and network context to decide whether access to a resource should be allowed or denied.

## Policy Administrator (PA):
The Policy Administrator is responsible for applying the decision made by the Policy Engine. It communicates the decision and prepares the system so the request can be allowed or blocked according to the policy.

## Policy Enforcement Point (PEP):
The Policy Enforcement Point is the component that actually enforces the access decision. It sits between the user and the resource and allows or denies the connection based on the decision from the Policy Engine.

# 2. Core Principle Application

## Selected Principle: Verify Explicitly

In this scenario, the Policy Engine enforces the Verify Explicitly principle by checking multiple signals before allowing access to the HR employee PII database. The Policy Engine evaluates the user’s identity, the device being used, and the network location of the request. If all conditions meet the security policy, access is allowed. If any condition fails, access is denied to protect the sensitive HR data.

# 3. Simplified Policy Table

| Policy Requirement (Signal) | Condition to be Met by User | Action if Condition is Met |
|-----------------------------|-----------------------------|----------------------------|
| User Identity | User must log in with company credentials and multi-factor authentication | Allow access request |
| Device Posture | Device must be a registered company device with updated security patches | Allow access to HR database |
| Network Context | Access must come from the internal network or company VPN | Allow connection to HR system |

# Git Repository Metadata

Filename: ZT-Policy-Profile.md

Commit Message: 
Created Zero Trust Policy Profile for HR PII Database - # 1. ZTA Component Definitions

Policy Engine (PE):
The Policy Engine is the decision-making component in a Zero Trust Architecture. It evaluates signals such as user identity, device security, and network context to decide whether access to a resource should be allowed or denied.

Policy Administrator (PA):
The Policy Administrator is responsible for applying the decision made by the Policy Engine. It communicates the decision and prepares the system so the request can be allowed or blocked according to the policy.

Policy Enforcement Point (PEP):
The Policy Enforcement Point is the component that actually enforces the access decision. It sits between the user and the resource and allows or denies the connection based on the decision from the Policy Engine.

# 2. Core Principle Application

Chosen Principle: Verify Explicitly

In this scenario, the Policy Engine enforces the Verify Explicitly principle by checking multiple signals before allowing access to the HR employee PII database. The Policy Engine evaluates the user’s identity, the device being used, and the network location of the request. If all conditions meet the security policy, access is allowed. If any condition fails, access is denied to protect the sensitive HR data.

# 3. Simplified Policy Table

| Policy Requirement (Signal) | Condition to be Met by User | Action if Condition is Met |
|-----------------------------|-----------------------------|----------------------------|
| User Identity | User must log in with company credentials and multi-factor authentication | Allow access request |
| Device Posture | Device must be a registered company device with updated security patches | Allow access to HR database |
| Network Context | Access must come from the internal network or company VPN | Allow connection to HR system |

# 4. Submission Details

# Git Repository Metadata

Filename: ZT-Policy-Profile.md

Commit Message: Add ZTA Policy Profile lab - # 1. ZTA Component Definitions

Policy Engine (PE):
The Policy Engine is the decision-making component in a Zero Trust Architecture. It evaluates signals such as user identity, device security, and network context to decide whether access to a resource should be allowed or denied.

Policy Administrator (PA):
The Policy Administrator is responsible for applying the decision made by the Policy Engine. It communicates the decision and prepares the system so the request can be allowed or blocked according to the policy.

Policy Enforcement Point (PEP):
The Policy Enforcement Point is the component that actually enforces the access decision. It sits between the user and the resource and allows or denies the connection based on the decision from the Policy Engine.

# 2. Core Principle Application

Chosen Principle: Verify Explicitly

In this scenario, the Policy Engine enforces the Verify Explicitly principle by checking multiple signals before allowing access to the HR employee PII database. The Policy Engine evaluates the user’s identity, the device being used, and the network location of the request. If all conditions meet the security policy, access is allowed. If any condition fails, access is denied to protect the sensitive HR data.

# 3. Simplified Policy Table

| Policy Requirement (Signal) | Condition to be Met by User | Action if Condition is Met |
|-----------------------------|-----------------------------|----------------------------|
| User Identity | User must log in with company credentials and multi-factor authentication | Allow access request |
| Device Posture | Device must be a registered company device with updated security patches | Allow access to HR database |
| Network Context | Access must come from the internal network or company VPN | Allow connection to HR system |

# 4. Submission Details

# Git Repository Metadata

Filename: ZT-Policy-Profile.md

Commit Message: Add ZTA Policy Profile lab - https://github.com/yalanazii/zta/-policy-lab
