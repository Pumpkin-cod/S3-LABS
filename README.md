# Amazon S3 Labs - Comprehensive Study

This repository contains three hands-on labs exploring key Amazon S3 features including lifecycle management, versioning with MFA delete, and cross-region replication.

## Lab Overview

### Lab 1: Amazon S3 Lifecycle Management
**Objective**: Configure and implement S3 lifecycle policies to automatically transition objects between storage classes and manage object deletion.

**Key Features Explored**:
- Lifecycle policy creation and configuration
- Storage class transitions (Standard → IA → Glacier → Deep Archive)
- Object expiration rules
- Cost optimization through automated storage management

**Files**:
- `Lab 1 Report – Amazon S3 Lifecycle Management.pdf` - Detailed lab report
- `Lab1 screenshots/` - Visual documentation of the lab process
- `text1.txt`, `test2.txt`, `test3.txt` - Test files for lifecycle management

### Lab 2: Versioning & MFA Delete
**Objective**: Implement S3 object versioning and configure Multi-Factor Authentication (MFA) delete protection for enhanced data security.

**Key Features Explored**:
- S3 object versioning configuration
- MFA delete protection setup
- Version management and restoration
- Security best practices for data protection

**Files**:
- `Lab 2_ Versioning & MFA Delete.pdf` - Comprehensive lab documentation
- `Lab2 screenshots/` - Step-by-step visual guide
- `version-test.txt` - Test file for versioning experiments

### Lab 3: Cross-Region Replication (CRR)
**Objective**: Configure Cross-Region Replication to automatically replicate S3 objects across different AWS regions for disaster recovery and compliance.

**Key Features Explored**:
- Cross-region replication setup
- IAM role configuration for replication
- Replication rules and filters
- Multi-region data durability and availability

**Files**:
- `Lab 3_ Cross-Region Replication (CRR).pdf` - Complete lab analysis
- `Lab3 screenshots/` - Implementation screenshots

## Key Learning Outcomes

### Technical Skills Developed
- **S3 Lifecycle Management**: Automated cost optimization through intelligent storage class transitions
- **Data Security**: Implementation of versioning and MFA delete for data protection
- **Disaster Recovery**: Cross-region replication for business continuity
- **IAM Configuration**: Proper role and policy setup for S3 operations
- **Cost Management**: Understanding storage costs and optimization strategies

### AWS Services Utilized
- Amazon S3 (Simple Storage Service)
- AWS IAM (Identity and Access Management)
- AWS CLI (Command Line Interface)

## Prerequisites
- AWS Account with appropriate permissions
- Basic understanding of AWS S3 concepts
- Familiarity with AWS IAM roles and policies
- AWS CLI configured (optional but recommended)

## Lab Execution Summary

Each lab was designed to provide hands-on experience with critical S3 features:

1. **Lab 1** focused on cost optimization through lifecycle policies
2. **Lab 2** emphasized data protection and security measures
3. **Lab 3** addressed disaster recovery and compliance requirements

## Cost Implications

Throughout these labs, various cost factors were observed and analyzed:
- Storage class pricing differences
- Data transfer costs for cross-region replication
- Request pricing for different operations
- Long-term cost benefits of lifecycle management

## Best Practices Learned

- Always enable versioning for critical data
- Implement MFA delete for additional security
- Use lifecycle policies to optimize storage costs
- Configure cross-region replication for disaster recovery
- Monitor and audit S3 operations regularly
- Apply least privilege principle for IAM roles

## Future Enhancements

Potential areas for further exploration:
- S3 Transfer Acceleration
- S3 Event Notifications
- S3 Analytics and Insights
- Integration with AWS Lambda for automated processing
- S3 Access Points for simplified access management

## Documentation

Each lab includes:
- Detailed PDF reports 
- Screenshots documenting the implementation process
- Analysis of challenges encountered and solutions applied
- Cost implications and optimization recommendations

---
