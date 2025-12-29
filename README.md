# Secure Enterprise Network Lab

## 1. Overview
This project focuses on designing and implementing a secure enterprise network architecture following real-world security practices.

## 2. Objectives
- Design a segmented enterprise network using VLANs and security zones
- Implement firewall policies based on least privilege
- Provide secure remote access via VPN
- Enable centralized logging and security monitoring

## 3. Architecture (High-level)
_To be designed_

## 4. Technology Stack
- WSL2 (Ubuntu)
- Git & GitHub

## 5. Security Design Principles

### Phase 2 – Network Segmentation & Trust Boundaries

This phase focuses on reducing attack surface and enforcing trust boundaries between system components, following enterprise security design principles.

#### Implemented Security Controls
- Network-level segmentation between frontend, backend, and database services
- Dedicated networks to isolate services and prevent unnecessary exposure
- Explicit trust boundaries with a default-deny mindset
- Controlled inter-service communication (least privilege networking)
- Boundary-focused firewall rule design to protect critical assets (database)

#### Security Mindset & Design Decisions
- Database services are isolated from frontend-facing networks
- Firewall rules are enforced closer to high-value assets (DB-first protection)
- Lateral movement is limited through segmentation and strict allow rules
- System design prioritizes “secure by design” rather than “works by default”

#### Security Outcomes
- Reduced blast radius if a web-facing service is compromised
- Prevention of unauthorized access to backend and database layers
- Clear trust boundaries aligned with enterprise network security models
- Improved readiness for monitoring and detection in later phases (SOC)


## 6. What I Learned
_To be updated_
